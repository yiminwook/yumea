<script lang="ts">
	import { onMount } from 'svelte';
	import Swiper from 'swiper';
	import { Navigation, Pagination, Autoplay } from 'swiper/modules';

	// Swiper 모듈 설정
	Swiper.use([Navigation, Pagination, Autoplay]);

	// 샘플 데이터
	const slides = [
		{
			id: 1,
			title: '전문적인 두피 진단',
			description: '개인별 두피 상태를 정확히 분석하여 맞춤형 케어 프로그램을 제공합니다.',
			image: 'https://images.unsplash.com/photo-1560066984-138dadb4c035?w=800&h=600&fit=crop',
			color: 'bg-blue-50'
		},
		{
			id: 2,
			title: '따뜻한 케어 서비스',
			description: '마음까지 편안해지는 따뜻한 서비스로 진정한 휴식을 경험하세요.',
			image: 'https://images.unsplash.com/photo-1571019613454-1cb2f99b2d8b?w=800&h=600&fit=crop',
			color: 'bg-green-50'
		},
		{
			id: 3,
			title: '효과적인 결과',
			description: '과학적이고 체계적인 관리로 건강하고 아름다운 모발을 만들어드립니다.',
			image: 'https://images.unsplash.com/photo-1522337360788-8b13dee7a37e?w=800&h=600&fit=crop',
			color: 'bg-purple-50'
		},
		{
			id: 4,
			title: '프리미엄 헤어 케어',
			description: '최고급 제품과 전문 기술로 당신의 모발을 특별하게 관리해드립니다.',
			image: 'https://images.unsplash.com/photo-1562322140-8baeececf3df?w=800&h=600&fit=crop',
			color: 'bg-pink-50'
		}
	];

	let swiperContainer: HTMLElement;
	let swiper: Swiper;

	onMount(() => {
		swiper = new Swiper(swiperContainer, {
			modules: [Navigation, Pagination, Autoplay],
			spaceBetween: 30,
			slidesPerView: 1,
			navigation: {
				nextEl: '.swiper-button-next',
				prevEl: '.swiper-button-prev'
			},
			pagination: {
				el: '.swiper-pagination',
				clickable: true
			},
			autoplay: {
				delay: 3000,
				disableOnInteraction: false
			},
			breakpoints: {
				640: {
					slidesPerView: 1
				},
				768: {
					slidesPerView: 2
				},
				1024: {
					slidesPerView: 3
				}
			}
		});
	});
</script>

<div class="py-20">
	<div class="container mx-auto px-4">
		<div class="mb-16 text-center">
			<h2 class="mb-4 text-3xl font-bold text-black md:text-4xl">유메아의 특별한 서비스</h2>
			<p class="mx-auto max-w-2xl text-lg text-gray-700">
				전문적인 케어와 따뜻한 서비스로 당신의 아름다움을 찾아드립니다
			</p>
		</div>

		<!-- Swiper 컨테이너 -->
		<div class="relative">
			<div class="swiper-container" bind:this={swiperContainer}>
				<div class="swiper-wrapper">
					{#each slides as slide}
						<div class="swiper-slide">
							<div
								class="group relative overflow-hidden rounded-2xl bg-white shadow-lg transition-all duration-300 hover:shadow-xl"
							>
								<!-- 이미지 -->
								<div class="relative h-64 overflow-hidden">
									<img
										src={slide.image}
										alt={slide.title}
										class="h-full w-full object-cover transition-transform duration-300 group-hover:scale-105"
									/>
									<div class="absolute inset-0 bg-linear-to-t from-black/50 to-transparent"></div>
									<div class="absolute right-4 bottom-4 left-4">
										<h3 class="text-xl font-bold text-white">{slide.title}</h3>
									</div>
								</div>

								<!-- 콘텐츠 -->
								<div class="p-6">
									<p class="leading-relaxed text-gray-700">{slide.description}</p>

									<!-- 버튼 -->
									<div class="mt-6">
										<button
											class="inline-flex items-center rounded-full border-2 border-black px-6 py-3 font-semibold text-black transition-all duration-300 hover:bg-black hover:text-white"
										>
											자세히 보기
											<svg class="ml-2 h-4 w-4" fill="currentColor" viewBox="0 0 20 20">
												<path
													fill-rule="evenodd"
													d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
													clip-rule="evenodd"
												></path>
											</svg>
										</button>
									</div>
								</div>
							</div>
						</div>
					{/each}
				</div>

				<!-- 네비게이션 버튼 -->
				<div class="swiper-button-next"></div>
				<div class="swiper-button-prev"></div>

				<!-- 페이지네이션 -->
				<div class="swiper-pagination"></div>
			</div>
		</div>
	</div>
</div>

<style>
	:global(.swiper-container) {
		padding: 20px 0 60px 0;
	}

	:global(.swiper-button-next),
	:global(.swiper-button-prev) {
		color: #000;
		background: rgba(255, 255, 255, 0.9);
		border-radius: 50%;
		width: 50px;
		height: 50px;
		margin-top: -25px;
		box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
		transition: all 0.3s ease;
	}

	:global(.swiper-button-next:hover),
	:global(.swiper-button-prev:hover) {
		background: #000;
		color: white;
		transform: scale(1.1);
	}

	:global(.swiper-button-next:after),
	:global(.swiper-button-prev:after) {
		font-size: 18px;
		font-weight: bold;
	}

	:global(.swiper-pagination-bullet) {
		background: rgba(0, 0, 0, 0.3);
		opacity: 1;
		width: 12px;
		height: 12px;
		margin: 0 6px;
		transition: all 0.3s ease;
	}

	:global(.swiper-pagination-bullet-active) {
		background: #000;
		transform: scale(1.2);
	}
</style>
