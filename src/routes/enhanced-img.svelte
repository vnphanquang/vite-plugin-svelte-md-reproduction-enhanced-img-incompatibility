<script lang="ts">
	import type { EnhancedImgAttributes } from '@sveltejs/enhanced-img';

	let { src, ...attrs }: EnhancedImgAttributes = $props();
</script>

<enhanced:img {src} {...attrs} />
