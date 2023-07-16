<script lang="ts">
	import { error } from '@sveltejs/kit';

	throw error(404, { message: 'test' });
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>
