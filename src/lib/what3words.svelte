<script lang="ts">
	let { location } = $props();
</script>

<a href={`https://what3words.com/${location}`} target="_blank">
	<p class="slashes">///</p>
	<p class="location">{location}</p>
</a>

<style>
	@import url('https://fonts.bunny.net/css2?family=Source+Sans+3:ital,wght@0,200..900;1,200..900&display=swap');
	* {
		--what3words-red: #e11f26;
	}
	a {
		padding: 6px 10px;
		box-shadow: inset 0px -3px 0px var(--what3words-red);
		display: flex;
		width: fit-content;
		background-color: white;
		text-decoration: none;
	}

	a > .slashes {
		color: var(--what3words-red);
	}

	a > .location {
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
