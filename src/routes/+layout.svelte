<script lang="ts">
	import Header from './Header.svelte';
	import '../app.css';

	let { children } = $props();
</script>

<svelte:head>
	<title>Yumea | 유메아</title>
	<meta name="description" content="꿈을  꾸는 곳 , 유메아에서  하루의 피로를 내려 놓으세요 " />
</svelte:head>

<div class="app">
	<!-- <Header /> -->

	<main>
		{@render children()}
	</main>

	<!-- <footer></footer> -->
</div>

<style>
</style>
