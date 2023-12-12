<script>
	import Hero from "$lib/components/home/Hero.svelte";
	import Presentation from "$lib/components/home/Presentation.svelte";
	import ServiceCard from "$lib/components/home/ServiceCard.svelte";

</script>
<body>
  <Hero />
  <div class="services-container">
    <ServiceCard cardIcon="fa-solid fa-object-group" cardName= "Design" />
    <ServiceCard cardIcon="fa-solid fa-laptop-code" cardName= "Web Dev" />
    <ServiceCard cardIcon="fa-solid fa-compass" cardName= "Consulting" />
  </div>
  <Presentation />

</body>

<style>
  .services-container {
    width: 100;
    display: flex;
    gap: 2rem;
    margin: 2rem;
  }
</style>