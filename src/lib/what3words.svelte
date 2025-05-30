<script lang="ts">
	let { children } = $props();
</script>

<div class="">
	<p class="slashes">///</p>
	<p class="location">{@render children()}</p>
</div>

<style>
	@import url('https://fonts.googleapis.com/css2?family=Source+Sans+3:ital,wght@0,200..900;1,200..900&display=swap');
	* {
		--what3words-red: #e11f26;
	}
	div {
		padding: 6px 10px;
		box-shadow: inset 0px -3px 0px var(--what3words-red);
		display: flex;
		width: fit-content;
		background-color: white;
	}

	div > .slashes {
		color: var(--what3words-red);
	}

	div > .location {
		color: black;
	}

	p {
		font-family: 'Source Sans 3', sans-serif;
		font-optical-sizing: auto;
		font-weight: 600;
		font-style: normal;
		padding: 0;
		margin: 0;
	}
</style>
