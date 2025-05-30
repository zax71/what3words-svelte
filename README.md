# What3words-svelte

[![npm](https://cdn.jsdelivr.net/npm/@intergrav/devins-badges@3/assets/cozy/available/npm_vector.svg)](https://www.npmjs.com/package/what3words-svelte)

A [Svelte](https://svelte.dev/) component to display a [what3words](https://what3words.com/) address, complying with [their best practices](https://developer.what3words.com/design/formatting-best-practice). Upon click it will open the location in a new browser tab

## Usage

```svelte
<script lang="ts">
	import { What3words } from 'what3words-svelte';
</script>

<What3words location="filled.count.soap" />
<What3words location="your.three.words" />
```

## Demo

![](.github/assets/demo.png)
