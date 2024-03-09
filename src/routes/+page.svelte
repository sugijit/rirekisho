<script>
	import Counter from './Counter.svelte';
	import welcome from '$lib/images/svelte-welcome.webp';
	import welcome_fallback from '$lib/images/svelte-welcome.png';
	import "../app.css";
</script>

<svelte:head>
	<title>ホーム</title>
	<meta name="description" content="履歴書アプリ" />
</svelte:head>

<section class="flex mt-60 flex-col justify-center items-center">
	<h1>
		<span class="welcome">
			<picture>
				<source srcset={welcome} type="image/webp" />
				<img src={welcome_fallback} alt="Welcome" />
			</picture>
		</span>
	</h1>
	<h1 class="text-4xl"><span class="text-orange-600">SVELTE</span>で<span class="text-orange-600">履歴書</span>を作っていくぞ</h1>
	<div class="mt-10">
		<a href="/cv" class="p-4 bg-slate-300 rounded-lg text-gray-600 hover:text-white hover:bg-slate-400 !no-underline">履歴書を見るぞ</a>
	</div>
</section>

<style>
	h1 {
		width: 100%;
	}

	.welcome {
		display: block;
		position: relative;
		width: 100%;
		height: 0;
		padding: 0 0 calc(100% * 495 / 2048) 0;
	}

	.welcome img {
		position: absolute;
		width: 100%;
		height: 100%;
		top: 0;
		display: block;
	}
</style>
