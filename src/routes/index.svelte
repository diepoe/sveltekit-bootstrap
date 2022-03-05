<script lang="ts">
	import { Button, Col, Row } from 'sveltestrap';
</script>

<svelte:head>
	<title>SvelteKit Bootstrap</title>
</svelte:head>

<div class="container mt-4">
	<Row cols={1} class="border-bottom">
		<Col>
			<h1>Bootstrap + SvelteKit = ♥️</h1>
		</Col>
	</Row>
	<Row cols={3} class="mt-5">
		<Col>
			<h2>💄 Bootstrap</h2>
			<p>
				This template uses Bootstrap (by twitter) in the newest version 5 as CSS-framework. On this
				page, it's implemented with <a href="https://github.com/bestguy/sveltestrap">sveltestrap</a
				>. Check Bootstrap out here:
			</p>
			<Button
				href="https://getbootstrap.com/docs/5.0/getting-started/introduction/"
				color="info"
				outline>Docs</Button
			>
		</Col>
		<Col>
			<h2>⚙️ Svelte</h2>
			<p>
				The superfast webframework Svelte for cybernetically enhanced web apps powers this template
				at the core. Here you can find more about it:
			</p>
			<Button href="https://svelte.dev/docs" color="info" outline>Docs</Button>
		</Col>
		<Col>
			<h2>📑 SvelteKit</h2>
			<p>
				The full power of this site comes from SvelteKit. It's a framework built on top of Svelte
				and brings features like routing to this template. Visit the SvelteKit site here:
			</p>
			<Button href="https://kit.svelte.dev/docs" color="info" outline>Docs</Button>
		</Col>
	</Row>
</div>
