<script>
	import Logo from "$lib/atoms/Logo.svelte";
</script>

<section class="min-h:100vh w:full flex flex:col jc:center ai:center">
	<div class="container flex flex:col gap:16 ai:start">
		<Logo />

		<h1 class="f:80">SvelteKit + <br />MasterCSS</h1>

		<p class="f:18 max-w:400 lh:1.5">
			A base template including the <mark>latest version</mark> of both SvelteKit
			& MasterCSS.
		</p>

		<div class="flex mt:32">
			<a
				href="https://github.com/jacksmethurst/skmaster-template"
				target="_blank"
				class="block p:12|16 b:1|solid|black bg:black:hover color:white:hover"
				>Get started</a
			>
			<a
				href="https://stackblitz.com/edit/sveltekit-mastercss-template?file=src/routes/+page.svelte"
				target="_blank"
				class="block p:12|16 b:1|solid|black bl:none bg:black:hover color:white:hover flex ai:center gap:4"
			>
				<span class="material-symbols-outlined"> download </span> Download</a
			>
		</div>
	</div>
</section>

<style>
	mark {
		background: black;
		color: white;
	}

	:global(svg) {
		animation: spin 30s linear;
		animation-iteration-count: infinite;
	}

	@keyframes spin {
		0% {
			transform: rotate(0deg);
		}
		100% {
			transform: rotate(360deg);
		}
	}
</style>
