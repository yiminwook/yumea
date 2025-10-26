<script lang="ts">
	// import Counter from './Counter.svelte';
	// import welcome from '$lib/images/svelte-welcome.webp';
	// import welcomeFallback from '$lib/images/svelte-welcome.png';
</script>

<svelte:head>
	<title>Yumea | 유메아</title>
	<meta name="description" content="꿈을  꾸는 곳 , 유메아에서  하루의 피로를 내려 놓으세요 " />
</svelte:head>

<!-- 종이질감 배경 -->
<main class="relative min-h-screen bg-white">
	<!-- 종이질감 텍스처 -->
	<div
		class="absolute inset-0 opacity-20"
		style="background-image: url('data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIxMDAiIGhlaWdodD0iMTAwIiB2aWV3Qm94PSIwIDAgMTAwIDEwMCI+PGRlZnM+PHBhdHRlcm4gaWQ9InBhcGVyIiBwYXR0ZXJuVW5pdHM9InVzZXJTcGFjZU9uVXNlIiB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCI+PHJlY3Qgd2lkdGg9IjEwMCIgaGVpZ2h0PSIxMDAiIGZpbGw9IiNmZmZmZmYiLz48cGF0aCBkPSJNMCAwaDEwMHYxSDB6TTAgMmgxMDB2MUgwek0wIDRoMTAwdjFIMHpNMCA2aDEwMHYxSDB6TTAgOGgxMDB2MUgwek0wIDEwaDEwMHYxSDB6TTAgMTJoMTAwdjFIMHpNMCAxNGgxMDB2MUgwek0wIDE2aDEwMHYxSDB6TTAgMThoMTAwdjFIMHpNMCAyMGgxMDB2MUgwek0wIDIyaDEwMHYxSDB6TTAgMjRoMTAwdjFIMHpNMCAyNmgxMDB2MUgwek0wIDI4aDEwMHYxSDB6TTAgMzBoMTAwdjFIMHpNMCAzMmgxMDB2MUgwek0wIDM0aDEwMHYxSDB6TTAgMzZoMTAwdjFIMHpNMCAzOGgxMDB2MUgwek0wIDQwaDEwMHYxSDB6TTAgNDJoMTAwdjFIMHpNMCA0NGgxMDB2MUgwek0wIDQ2aDEwMHYxSDB6TTAgNDhoMTAwdjFIMHpNMCA1MGgxMDB2MUgwek0wIDUyaDEwMHYxSDB6TTAgNTRoMTAwdjFIMHpNMCA1NmgxMDB2MUgwek0wIDU4aDEwMHYxSDB6TTAgNjBoMTAwdjFIMHpNMCA2MmgxMDB2MUgwek0wIDY0aDEwMHYxSDB6TTAgNjZoMTAwdjFIMHpNMCA2OGgxMDB2MUgwek0wIDcwaDEwMHYxSDB6TTAgNzJoMTAwdjFIMHpNMCA3NGgxMDB2MUgwek0wIDc2aDEwMHYxSDB6TTAgNzhoMTAwdjFIMHpNMCA4MGgxMDB2MUgwek0wIDgyaDEwMHYxSDB6TTAgODRoMTAwdjFIMHpNMCA4NmgxMDB2MUgwek0wIDg4aDEwMHYxSDB6TTAgOTBoMTAwdjFIMHpNMCA5MmgxMDB2MUgwek0wIDk0aDEwMHYxSDB6TTAgOTZoMTAwdjFIMHpNMCA5OGgxMDB2MUgwek0wIDEwMGgxMDB2MUgweiIgZmlsbD0iI2Y1ZjVmNSIgb3BhY2l0eT0iMC4xIi8+PC9wYXR0ZXJuPjwvZGVmcz48cmVjdCB3aWR0aD0iMTAwIiBoZWlnaHQ9IjEwMCIgZmlsbD0idXJsKCNwYXBlcikiLz48L3N2Zz4='); background-size: 100px 100px;"
	></div>

	<div class="relative z-10 container mx-auto px-4 py-8">
		<!-- 페이지 헤더 -->
		<header class="mb-12 text-center">
			<h1 class="mb-4 text-4xl font-bold text-black md:text-5xl">YUMEA MENU</h1>
			<p
				class="text-lg text-gray-600"
				style="font-family: 'Nanum Pen Script', cursive; font-size: 1.5rem; color: #374151;"
			>
				꿈을 꾸는 곳, 유메아에서 하루의 피로를 내려놓으세요
			</p>
		</header>

		<!-- 메뉴 그리드 - 데스크톱 2열, 모바일 1열 -->
		<section class="mx-auto grid max-w-7xl grid-cols-1 gap-12 sm:grid-cols-2">
			<!-- 청소년 코스 -->
			<article class="border-b-2 border-gray-200 pb-8">
				<header class="mb-6 flex items-center justify-between">
					<h2
						class="text-2xl text-black"
						style="font-family: 'Nanum Pen Script', cursive; font-size: 2.5rem; color: #374151;"
					>
						청소년 코스
					</h2>
					<div
						class="rounded-full border border-gray-300 px-3 py-1 text-sm font-medium whitespace-nowrap text-gray-700"
					>
						인기
					</div>
				</header>

				<div class="mb-6 space-y-3">
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="font-medium">소요시간 35분 ~ 40분</span>
					</div>
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"
							></path>
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="text-xl font-bold">90,000원</span>
					</div>
					<!-- <div
						class="inline-block border border-gray-300 px-3 py-1 text-sm font-medium text-gray-700"
					>
						단발이하 1만원 할인
					</div> -->
				</div>

				<div class="border-t border-gray-200 pt-6">
					<h4 class="mb-4 text-lg font-semibold text-black">프로그램 구성</h4>
					<ol class="space-y-2">
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>1</span
							>
							진단
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>2</span
							>
							쿨브러쉬
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>3</span
							>
							플라즈마
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>4</span
							>
							두침욕
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>5</span
							>
							버블 두피 스케일링
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>6</span
							>
							샴푸
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>7</span
							>
							두피팩
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>8</span
							>
							두피냄새 제거용 토너
						</li>
					</ol>
				</div>
			</article>

			<!-- 유메아 시그니처 -->
			<article class="border-b-2 border-gray-200 pb-8">
				<header class="mb-6 flex items-center justify-between">
					<h2
						class="text-2xl text-black"
						style="font-family: 'Nanum Pen Script', cursive; font-size: 2.5rem; color: #374151;"
					>
						유메아 시그니처
					</h2>
					<div
						class="rounded-full border border-gray-300 px-3 py-1 text-sm font-medium text-gray-700"
					>
						프리미엄
					</div>
				</header>

				<div class="mb-6 space-y-3">
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="font-medium">소요시간 60분</span>
					</div>
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"
							></path>
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="text-xl font-bold">150,000원</span>
					</div>
					<!-- <div class="flex flex-wrap gap-2">
						<div class="border border-gray-300 px-3 py-1 text-sm font-medium text-gray-700">
							10회 회원 5% 할인
						</div>
						<div class="border border-gray-300 px-3 py-1 text-sm font-medium text-gray-700">
							현금 11회 + 매회 탄산 스파
						</div>
					</div> -->
				</div>

				<div class="border-t border-gray-200 pt-6">
					<h4 class="mb-4 text-lg font-semibold text-black">프로그램 구성</h4>
					<ol class="space-y-2">
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>1</span
							>
							진단
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>2</span
							>
							쿨브러쉬 + 온열 EMS 림프 테라피
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>3</span
							>
							플라즈마
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>4</span
							>
							두침욕
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>5</span
							>
							두피 상태에 따른 스케일링
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>6</span
							>
							타카라 미스트
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>7</span
							>
							샴푸
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>8</span
							>
							두피팩
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>9</span
							>
							근막 마사지
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>10</span
							>
							두피 갈바닉
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>11</span
							>
							생체 전류 테라피
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>12</span
							>
							두피 드라이
						</li>
					</ol>
				</div>
			</article>

			<!-- 유메 맘(산후) -->
			<article class="border-b-2 border-gray-200 pb-8">
				<header class="mb-6 flex items-center justify-between">
					<h2
						class="text-2xl text-black"
						style="font-family: 'Nanum Pen Script', cursive; font-size: 2.5rem; color: #374151;"
					>
						유메 맘(산후)
					</h2>
					<div
						class="rounded-full border border-gray-300 px-3 py-1 text-sm font-medium whitespace-nowrap text-gray-700"
					>
						산후케어
					</div>
				</header>

				<div class="mb-6 space-y-3">
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="font-medium">소요시간 60분</span>
					</div>
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"
							></path>
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="text-xl font-bold">150,000원</span>
					</div>
					<!-- <div class="flex flex-wrap gap-2">
						<div
							class="rounded-lg border border-gray-300 px-3 py-1 text-sm font-medium text-gray-700"
						>
							10회 회원 5% 할인
						</div>
						<div
							class="rounded-lg border border-gray-300 px-3 py-1 text-sm font-medium text-gray-700"
						>
							현금 11회 + 에센스
						</div>
					</div> -->
				</div>

				<div class="border-t border-gray-200 pt-6">
					<h4 class="mb-4 text-lg font-semibold text-black">프로그램 구성</h4>
					<ol class="space-y-2">
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>1</span
							>
							진단
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>2</span
							>
							두피 괄사 + 온열 EMS 림프 테라피
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>3</span
							>
							플라즈마
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>4</span
							>
							두침욕
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>5</span
							>
							두피 상태에 따른 스케일링
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>6</span
							>
							적외선 온열
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>7</span
							>
							샴푸
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>8</span
							>
							두피팩
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>9</span
							>
							헤어 미스트
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>10</span
							>
							두피 갈바닉
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>11</span
							>
							생체 전류 마사지 (탈모방지 에센스)
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>12</span
							>
							두피 드라이
						</li>
					</ol>
				</div>
			</article>

			<!-- 문제성 -->
			<article class="border-b-2 border-gray-200 pb-8">
				<header class="mb-6 flex items-center justify-between">
					<h2
						class="text-2xl text-black"
						style="font-family: 'Nanum Pen Script', cursive; font-size: 2.5rem; color: #374151;"
					>
						문제성
					</h2>
					<div
						class="rounded-full border border-gray-300 px-3 py-1 text-sm font-medium whitespace-nowrap text-gray-700"
					>
						맞춤케어
					</div>
				</header>

				<div class="mb-6 space-y-3">
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="font-medium">소요시간 40분</span>
					</div>
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"
							></path>
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="text-xl font-bold">100,000원</span>
					</div>
					<!-- <div
						class="inline-block rounded-lg border border-gray-300 px-3 py-1 text-sm font-medium text-gray-700"
					>
						10회 5% 할인
					</div> -->
				</div>

				<div class="border-t border-gray-200 pt-6">
					<h4 class="mb-4 text-lg font-semibold text-black">프로그램 구성</h4>
					<ol class="space-y-2">
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>1</span
							>
							진단
						</li>
						<li class="flex items-center text-gray-700">
							<span
								class="mr-3 flex h-6 w-6 items-center justify-center rounded-full border-2 border-black text-sm text-black"
								>2</span
							>
							두피상태에 알맞는 프로그램으로 진행
						</li>
					</ol>
				</div>
			</article>

			<!-- 유메아 시그니처 + 모발 클리닉 -->
			<article class="border-b-2 border-gray-200 pb-8 sm:col-span-2">
				<header class="mb-6 flex items-center justify-between">
					<h2
						class="text-2xl break-keep text-black"
						style="font-family: 'Nanum Pen Script', cursive; font-size: 2.5rem; color: #374151;"
					>
						유메아 시그니처 + 모발 클리닉
					</h2>
					<div
						class="rounded-full border border-gray-300 px-3 py-1 text-sm font-medium whitespace-nowrap text-gray-700"
					>
						프리미엄
					</div>
				</header>

				<div class="mb-6 space-y-3">
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-12a1 1 0 10-2 0v4a1 1 0 00.293.707l2.828 2.829a1 1 0 101.415-1.415L11 9.586V6z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="font-medium">소요시간 100분</span>
					</div>
					<div class="flex items-center text-gray-700">
						<svg class="mr-2 h-5 w-5" fill="currentColor" viewBox="0 0 20 20">
							<path
								d="M8.433 7.418c.155-.103.346-.196.567-.267v1.698a2.305 2.305 0 01-.567-.267C8.07 8.34 8 8.114 8 8c0-.114.07-.34.433-.582zM11 12.849v-1.698c.22.071.412.164.567.267.364.243.433.468.433.582 0 .114-.07.34-.433.582a2.305 2.305 0 01-.567.267z"
							></path>
							<path
								fill-rule="evenodd"
								d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-13a1 1 0 10-2 0v.092a4.535 4.535 0 00-1.676.662C6.602 6.234 6 7.009 6 8c0 .99.602 1.765 1.324 2.246.48.32 1.054.545 1.676.662v1.941c-.391-.127-.68-.317-.843-.504a1 1 0 10-1.51 1.31c.562.649 1.413 1.076 2.353 1.253V15a1 1 0 102 0v-.092a4.535 4.535 0 001.676-.662C13.398 13.766 14 12.991 14 12c0-.99-.602-1.765-1.324-2.246A4.535 4.535 0 0011 9.092V7.151c.391.127.68.317.843.504a1 1 0 101.511-1.31c-.563-.649-1.413-1.076-2.354-1.253V5z"
								clip-rule="evenodd"
							></path>
						</svg>
						<span class="text-xl font-bold">200,000원</span>
					</div>
					<!-- <div
						class="inline-block rounded-lg border border-gray-300 px-3 py-1 text-sm font-medium text-gray-700"
					>
						10회 회원 5% 할인
					</div> -->
				</div>

				<div class="rounded-lg border border-gray-200 bg-gray-50 p-6">
					<h4 class="mb-2 text-lg font-semibold text-black">프리미엄 패키지</h4>
					<p class="text-gray-700">
						유메아 시그니처 코스와 모발 클리닉을 결합한 최고급 패키지로, 두피와 모발의 완벽한 케어를
						제공합니다.
					</p>
				</div>
			</article>
		</section>
	</div>
</main>

<style></style>
