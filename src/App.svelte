<script>
	export let income;
</script>

<main>
	<div class="grid justify-items-stretch">
		<h1 class="sm pt-6 rounded-full justify-self-auto text-center text-lg">
			Enter your Monthly Income
		</h1>

		<form class=" pl-10 border-solid border-black shadow justify-self-auto">
			<input
				class="justify-self-auto"
				type="text"
				bind:value={income}
			/>
		</form>
	</div>
</main>

<style>
</style>
