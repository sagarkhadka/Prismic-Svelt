<script lang="ts">
	import { SliceZone } from '@prismicio/svelte';
	import type { PageProps } from './$types';
	import '@fontsource-variable/dm-sans';
	import { components } from '$lib/slices';

	const { data }: PageProps = $props();
</script>

<SliceZone slices={data.page.data.slices} {components} />
