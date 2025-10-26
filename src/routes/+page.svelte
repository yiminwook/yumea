<script lang="ts">
	// import Counter from './Counter.svelte';
	// import welcome from '$lib/images/svelte-welcome.webp';
	// import welcomeFallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Yumea | 유메아 - 꿈을 꾸는 곳</title>
	<meta
		name="description"
		content="꿈을 꾸는 곳, 유메아에서 하루의 피로를 내려놓으세요. 전문적인 두피 케어와 모발 관리를 제공합니다."
	/>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="anonymous" />
	<link
		href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;500;600;700&display=swap"
		rel="stylesheet"
	/>
</svelte:head>

<!-- 종이질감 배경 -->
<div class="relative min-h-screen bg-white">
	<!-- 종이질감 텍스처 -->
	<div
		class="absolute inset-0 opacity-20"
		style="background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAiIGhlaWdodD0iMTAwIiB2aWV3Qm94PSIwIDAgMTAwIDEwMCI+PGRlZnM+PHBhdHRlcm4gaWQ9InBhcGVyIiBwYXR0ZXJuVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCI+PHJlY3Qgd2lkdGg9IjEwMCIgaGVpZ2h0PSIxMDAiIGZpbGw9IiNmZmZmZmYiLz48cGF0aCBkPSJNMCAwaDEwMHYxSDB6TTAgMmgxMDB2MUgwek0wIDRoMTAwdjFIMHpNMCA2aDEwMHYxSDB6TTAgOGgxMDB2MUgwek0wIDEwaDEwMHYxSDB6TTAgMTJoMTAwdjFIMHpNMCAxNGgxMDB2MUgwek0wIDE2aDEwMHYxSDB6TTAgMThoMTAwdjFIMHpNMCAyMGgxMDB2MUgwek0wIDIyaDEwMHYxSDB6TTAgMjRoMTAwdjFIMHpNMCAyNmgxMDB2MUgwek0wIDI4aDEwMHYxSDB6TTAgMzBoMTAwdjFIMHpNMCAzMmgxMDB2MUgwek0wIDM0aDEwMHYxSDB6TTAgMzZoMTAwdjFIMHpNMCAzOGgxMDB2MUgwek0wIDQwaDEwMHYxSDB6TTAgNDJoMTAwdjFIMHpNMCA0NGgxMDB2MUgwek0wIDQ2aDEwMHYxSDB6TTAgNDhoMTAwdjFIMHpNMCA1MGgxMDB2MUgwek0wIDUyaDEwMHYxSDB6TTAgNTRoMTAwdjFIMHpNMCA1NmgxMDB2MUgwek0wIDU4aDEwMHYxSDB6TTAgNjBoMTAwdjFIMHpNMCA2MmgxMDB2MUgwek0wIDY0aDEwMHYxSDB6TTAgNjZoMTAwdjFIMHpNMCA2OGgxMDB2MUgwek0wIDcwaDEwMHYxSDB6TTAgNzJoMTAwdjFIMHpNMCA3NGgxMDB2MUgwek0wIDc2aDEwMHYxSDB6TTAgNzhoMTAwdjFIMHpNMCA4MGgxMDB2MUgwek0wIDgyaDEwMHYxSDB6TTAgODRoMTAwdjFIMHpNMCA4NmgxMDB2MUgwek0wIDg4aDEwMHYxSDB6TTAgOTBoMTAwdjFIMHpNMCA5MmgxMDB2MUgwek0wIDk0aDEwMHYxSDB6TTAgOTZoMTAwdjFIMHpNMCA5OGgxMDB2MUgwek0wIDEwMGgxMDB2MUgweiIgZmlsbD0iI2Y1ZjVmNSIgb3BhY2l0eT0iMC4xIi8+PC9wYXR0ZXJuPjwvZGVmcz48cmVjdCB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgZmlsbD0idXJsKCNwYXBlcikiLz48L3N2Zz4='); background-size: 100px 100px;"
	></div>

	<!-- 메인 콘텐츠 -->
	<div class="relative z-10 flex min-h-screen flex-col">
		<!-- 헤더 -->
		<header class="container mx-auto px-4 py-6">
			<nav class="flex items-center justify-between">
				<div class="text-2xl font-bold text-black">유메아</div>
				<div class="hidden space-x-8 md:flex">
					<a href="/" class="text-gray-700 transition-colors hover:text-black">홈</a>
					<a href="/menu" class="text-gray-700 transition-colors hover:text-black">메뉴</a>
					<a href="/about" class="text-gray-700 transition-colors hover:text-black">소개</a>
				</div>
			</nav>
		</header>

		<!-- 메인 히어로 섹션 -->
		<main class="flex flex-1 items-center justify-center">
			<div class="container mx-auto px-4 text-center">
				<!-- 메인 타이틀 -->
				<h1 class="mb-6 text-5xl font-bold text-black md:text-7xl">
					<span class="block">유메아</span>
					<span class="mt-2 block text-3xl font-normal text-gray-600 md:text-4xl">꿈을 꾸는 곳</span
					>
				</h1>

				<!-- 서브 타이틀 -->
				<p class="mx-auto mb-12 max-w-2xl text-xl leading-relaxed text-gray-700">
					하루의 피로를 내려놓고, 당신만의 특별한 시간을 경험해보세요.<br />
					전문적인 두피 케어와 모발 관리로 건강한 아름다움을 찾아드립니다.
				</p>

				<!-- CTA 버튼들 -->
				<div class="flex flex-col items-center justify-center gap-4 sm:flex-row">
					<a
						href="/menu"
						class="group inline-flex items-center rounded-full border-2 border-black px-8 py-4 font-semibold text-black shadow-lg transition-all duration-300 hover:-translate-y-1 hover:bg-black hover:text-white hover:shadow-xl"
					>
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M3 4a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zm0 4a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zm0 4a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zm0 4a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z"
								clip-rule="evenodd"
							></path>
						</svg>
						메뉴 보기
						<svg
							class="ml-2 h-4 w-4 transition-transform group-hover:translate-x-1"
							fill="currentColor"
							viewBox="0 0 20 20"
						>
							<path
								fill-rule="evenodd"
								d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z"
								clip-rule="evenodd"
							></path>
						</svg>
					</a>
					<a
						href="/about"
						class="inline-flex items-center rounded-full border-2 border-gray-300 px-8 py-4 font-semibold text-gray-700 transition-all duration-300 hover:-translate-y-1 hover:border-black hover:text-black"
					>
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M18 10a8 8 0 11-16 0 8 8 0 0116 0zm-7-4a1 1 0 11-2 0 1 1 0 012 0zM9 9a1 1 0 000 2v3a1 1 0 001 1h1a1 1 0 100-2v-3a1 1 0 00-1-1H9z"
								clip-rule="evenodd"
							></path>
						</svg>
						더 알아보기
					</a>
				</div>
			</div>
		</main>

		<!-- 특징 섹션 -->
		<section class="py-20">
			<div class="container mx-auto px-4">
				<div class="mb-16 text-center">
					<h2 class="mb-4 text-3xl font-bold text-black md:text-4xl">왜 유메아인가요?</h2>
					<p class="mx-auto max-w-2xl text-lg text-gray-700">
						전문적인 케어와 따뜻한 서비스로 당신의 아름다움을 찾아드립니다
					</p>
				</div>

				<div class="mx-auto grid max-w-6xl grid-cols-1 gap-12 md:grid-cols-3">
					<!-- 특징 1 -->
					<div class="border-b-2 border-gray-200 pb-8 text-center">
						<div
							class="mx-auto mb-6 flex h-16 w-16 items-center justify-center rounded-full border-2 border-black"
						>
							<svg class="h-8 w-8 text-black" fill="currentColor" viewBox="0 0 20 20">
								<path d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path>
							</svg>
						</div>
						<h3 class="mb-4 text-xl font-bold text-black">전문적인 진단</h3>
						<p class="text-gray-700">
							개인별 두피 상태를 정확히 분석하여 맞춤형 케어 프로그램을 제공합니다.
						</p>
					</div>

					<!-- 특징 2 -->
					<div class="border-b-2 border-gray-200 pb-8 text-center">
						<div
							class="mx-auto mb-6 flex h-16 w-16 items-center justify-center rounded-full border-2 border-black"
						>
							<svg class="h-8 w-8 text-black" fill="currentColor" viewBox="0 0 20 20">
								<path
									fill-rule="evenodd"
									d="M3.172 5.172a4 4 0 015.656 0L10 6.343l1.172-1.171a4 4 0 115.656 5.656L10 17.657l-6.828-6.829a4 4 0 010-5.656z"
									clip-rule="evenodd"
								></path>
							</svg>
						</div>
						<h3 class="mb-4 text-xl font-bold text-black">따뜻한 케어</h3>
						<p class="text-gray-700">
							마음까지 편안해지는 따뜻한 서비스로 진정한 휴식을 경험하세요.
						</p>
					</div>

					<!-- 특징 3 -->
					<div class="border-b-2 border-gray-200 pb-8 text-center">
						<div
							class="mx-auto mb-6 flex h-16 w-16 items-center justify-center rounded-full border-2 border-black"
						>
							<svg class="h-8 w-8 text-black" fill="currentColor" viewBox="0 0 20 20">
								<path
									fill-rule="evenodd"
									d="M11.3 1.046A1 1 0 0112 2v5h4a1 1 0 01.82 1.573l-7 10A1 1 0 018 18v-5H4a1 1 0 01-.82-1.573l7-10a1 1 0 011.12-.38z"
									clip-rule="evenodd"
								></path>
							</svg>
						</div>
						<h3 class="mb-4 text-xl font-bold text-black">효과적인 결과</h3>
						<p class="text-gray-700">
							과학적이고 체계적인 관리로 건강하고 아름다운 모발을 만들어드립니다.
						</p>
					</div>
				</div>
			</div>
		</section>

		<!-- 푸터 -->
		<footer class="border-t border-gray-200 py-12">
			<div class="container mx-auto px-4 text-center">
				<div class="mb-6">
					<h3 class="mb-2 text-2xl font-bold text-black">유메아</h3>
					<p
						class="text-gray-600"
						style="font-family: 'Dancing Script', cursive; font-size: 1.5rem; color: #D4AF37;"
					>
						꿈을 꾸는 곳
					</p>
				</div>
				<div class="mb-6 flex justify-center space-x-8">
					<a href="/" class="text-gray-600 transition-colors hover:text-black">홈</a>
					<a href="/menu" class="text-gray-600 transition-colors hover:text-black">메뉴</a>
					<a href="/about" class="text-gray-600 transition-colors hover:text-black">소개</a>
				</div>
				<p class="text-sm text-gray-500">© 2025 Yumea. All rights reserved.</p>
			</div>
		</footer>
	</div>
</div>

<style></style>
