<script>
	import TestImage from './test.png?enhanced';
	import EnhancedImage from './enhanced-img.svelte';
</script>

# Reproduction

<enhanced:img src={TestImage} alt="some alt text" />

<enhanced:img src="./test.png" alt="some alt text" />

<EnhancedImage src={TestImage} alt="some alt text"  />
