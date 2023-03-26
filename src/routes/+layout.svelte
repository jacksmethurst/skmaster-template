<script>
	import "master.css";
	import "./styles.css";
</script>

<svelte:head>
	<title>MasterSvelte | A Sveltekit and MasterCSS template</title>
	<meta
		name="description"
		content="A base template including the <mark>latest version</mark> of both SvelteKit
			& MasterCSS."
	/>
	<meta
		property="og:title"
		content="MasterSvelte | A Sveltekit and MasterCSS template"
	/>
	<meta
		property="og:description"
		content="A base template including the <mark>latest version</mark> of both SvelteKit
			& MasterCSS."
	/>
	<meta property="og:image" content="/ogimage.png" />
	<meta property="og:site_name" content="New Genre" />
	<meta property="og:type" content="website" />
	<meta name="author" content="New Genre" />
	<meta name="robots" content="all" />

	<!-- favicon -->

	<link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png" />
	<link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png" />
	<link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png" />
	<link rel="manifest" href="/site.webmanifest" />

	<!-- Twitter -->
	<meta property="twitter:card" content="summary_large_image" />
	<meta
		property="twitter:title"
		content="MasterSvelte | A Sveltekit and MasterCSS template"
	/>
	<meta
		property="twitter:description"
		content="A base template including the <mark>latest version</mark> of both SvelteKit
			& MasterCSS."
	/>
	<meta property="twitter:image" content="/ogimage.png" />

	<script src="https://cdn.master.co/css@beta"></script>
</svelte:head>

<slot />
