<script>
	let clicked = false;
</script>

<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		{#if clicked == true}
		clicked
		{:else}
		click here
		{/if}
	</button>
	<!--  -->
</div>
