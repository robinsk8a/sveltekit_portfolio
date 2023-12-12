<script>
	export let cardIcon = 'fa-solid fa-gift';
	export let cardName = 'Card Imaginary';
	export let cardDescription =
		'Here should be a card description, can be a short text or a simple frase, you deside';
</script>

<div class="card">
	<i class={cardIcon}></i>
	<h3>{cardName}</h3>
	<p>{cardDescription}</p>
</div>

<style>
	.card {
		display: flex;
		flex-direction: column;
		align-items: center;
		gap: 1rem;
		justify-content: start;
		padding: 1.3rem;
		background-color: rgba(255, 255, 255, 0.8);
		color: var(--dark02);
		border-radius: 0.4rem;
		box-shadow: 0 0.1rem 0.1rem 0.05rem #000;
	}
	i {
		font-size: 2.5rem;
	}
</style>
