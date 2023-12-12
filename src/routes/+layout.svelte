<script>
    import Hero from "$lib/components/Hero.svelte";
    import MainNavigation from "$lib/components/Main-Navigation.svelte";
    import Container from "$lib/components/Container.svelte";
</script>

<svelte:head>
    <style lang="scss" global>
        @charset "utf-8";

        @use "/node_modules/bootstrap/scss/bootstrap" with (
            $color-mode-type: media-query,
        );

        body {
            padding-bottom: 3rem;
        }

        :is(h1,h2,h3,h4,h5,h6) {
            margin-top: 0.6em;
            margin-bottom: 0.4em;
        }

        .alert {
            & .blockquote-footer {
                color: color-mix(in lab, var(--bs-alert-color) 80%, black);
            }

            & a {
                color: var(--bs-alert-color);
                
                &:hover {
                    color: color-mix(in lab, var(--bs-alert-color), white);
                }
            }
        }

        .card iframe {
            width: 100%;
            aspect-ratio: 16/9;
        }
    </style>
</svelte:head>

<MainNavigation />

<Hero title={`Hi, I'm Josh.`} />

<Container>
    <slot />
</Container>
