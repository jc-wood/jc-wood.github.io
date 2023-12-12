<script>
    import Hero from "$lib/components/Hero.svelte";
    import MainNavigation from "$lib/components/Main-Navigation.svelte";
    import Container from "$lib/components/Container.svelte";
</script>

<svelte:head>
    <style lang="scss" global>
        @charset "utf-8";

        $purple-60: #8a3ffc;
        $teal-60: #007d79;
        $green-60: #198038;
        $cyan-60: #0072c3;
        $lightblue-60: #0079ac;
        $yellow-60: #8a6a1b;
        $red-60: #da1e28;
        $gray-10: #f4f4f4;
        $gray-90: #262626;
        $cool-gray-90: #21272a;
        $warm-gray-30: #cac5c4;
        $warm-gray-100: #171414;

        @use "/node_modules/bootstrap/scss/bootstrap" with (
            $color-mode-type: media-query,
            $blockquote-footer-color: inherit,
            $body-color-dark: $gray-10,
            $body-bg-dark: $warm-gray-100,
            $primary: $purple-60,
            $secondary: $teal-60,
            $success: $green-60,
            $info: $lightblue-60,
            $warning: $yellow-60,
            $danger: $red-60,
            $light: $gray-10,
            $dark: $gray-90,
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
