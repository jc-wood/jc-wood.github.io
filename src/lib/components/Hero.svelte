<script>
    import Container from "$lib/components/Container.svelte";
    /** @type {string} */
    export let title;
    /** @type {string|null} */
    export let tagline = null;
    /** @type {string} */
    export let thumbnail = "/img/my-face.webp";
</script>

<section class="hero">
    <Container>
        <h1 class="heading display-1">
            <img class="hero-img" src={thumbnail} alt="Me."/>
            {title}
        </h1>

        {#if tagline}

        <p>{tagline}</p>

        {/if}
    </Container>
</section>

<style lang="scss">    
    .hero {
        width: 100dvw;
        height: max(300px, 30vh);
        background-image: linear-gradient(60deg, #0072c3 15%, #198038 85%);

        @media (prefers-color-scheme: light){
            background-image: linear-gradient(60deg, hsl(205, 100%, 60%) 15%, hsl(138, 67%, 60%) 85%);
        }

        display: flex;
        flex-flow: column nowrap;
        justify-content: center;
        align-items: flex-start;

        & .heading {
            text-shadow: 0px 3px 6px #000;

            @media (prefers-color-scheme: light){
                color: var(--bs-light);
            }

            display: flex;
            flex-flow: row nowrap;
            justify-content: flex-start;
            align-items: center;
            gap: 2rem;

            & .hero-img {
                width: 128px;
                aspect-ratio: 1/1;
                object-fit: cover;
            }
        }
    }
</style>