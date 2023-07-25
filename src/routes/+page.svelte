
<script lang="ts">
	import Carousel from "$lib/carousel/carousel.svelte";
import Hero from "./Hero.svelte";

    export let data;
    console.log(data);
</script>

<h1 class="column">Top trending movies</h1>

<Hero movie={data.featured}></Hero>

<Carousel movies={data.trending.results}></Carousel>

<Carousel movies={data.trending.results}></Carousel>
<Carousel movies={data.trending.results}></Carousel>