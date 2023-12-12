<script>
     import Card from "$lib/components/Card.svelte";

    let title = 'Games';
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1 class="display-3">{title}</h1>
<p>I remember sitting in front of the family TV sometime back in 1990 or '91 playing various games on the Atari 2600 that my uncle dropped off. I remember being enamored with and utterly confused by a copy of <abbr title="E.T., The Extraterrestrial">E.T.</abbr>, <a href="https://www.npr.org/2017/05/31/530235165/total-failure-the-worlds-worst-video-game" title="A link to NPR.org">a game so awful millions of copies were buried in the desert</a>. Sometime shortly after, we acquired an <abbr title="Nintendo Entertainment System">NES</abbr> on which I would play Duck Hunt for <em>hours</em>. Many years later, Mario 64 would blow my mind when I got to play the demo at my local Blockbuster.</p>
<p>As you can imagine, video games have been a large part of my life. My high school years were probably the peak of gaming. Halo LAN parties and Smash Bros. tournaments were a weekly event for my friends and I.</p>

<p>For the past 8 years I've had a pretty regular game of <abbr title="Dungeons and Dragons, Fifth Edition">D&D 5e</abbr> going with a group of friends that I met in Knoxville, TN (or through those friends). I'm interested in trying out the Pathfinder <abbr title="Second Edition">2e</abbr> system in the future.</p>
<p class="mb-1">I'm a huge fan of both <a href="https://critrole.com/" title="A link to Critical Role's webpage">Critical Role</a> and <a href="https://www.youtube.com/@dimension20show" title="A link to Dimension 20's Youtube page.">Dimension 20</a>.</p>

<p class="mb-1"></p>


<div class="row row-cols-1 row-cols-md-2 row-cols-lg-4 g-3 mt-4">
    <div class="col">
        <Card>
            <img slot="cap" srcset="/img/d2_lightfall_360x360.webp 360w, /img/d2_lightfall_720x720.webp 720w" sizes="(max-width:600px) 360px, 720px" src="/img/d2_lightfall_720x720.webp" alt="Destiny 2: Lightfall Promotional Art"/>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">Destiny 2</h3>
                <p class="card-text">These days I spend an inordinate amount of time playing Destiny 2 with my friends and clanmates.</p>
                <p class="card-text">Shoot me an email, message me on Discord, or DM me on Mastodon and we'll game together.</p>
                <a class="card-link" href="https://www.bungie.net/7/en/Destiny">Go</a>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <img slot="cap" srcset="/img/baldurs-gate-3_keyart_360x360.webp 360w, /img/baldurs-gate-3_keyart_720x720.webp 720w" sizes="(max-width:600px) 360px, 720px" src="/img/baldurs-gate-3_keyart_720x720.webp" alt="Baldur's Gate 3 Promotional Art"/>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">Baldur's Gate 3</h3>
                <p class="card-text">This game is one of the best I've ever played. Phenomenal story telling. Great gameplay. The developers thought of everything.</p>
                <a class="card-link" href="https://baldursgate3.game">Go</a>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <img slot="cap" srcset="/img/discord-logo_360x360.webp 360w, /img/discord-logo_720x720.webp 720w" sizes="(max-width:600px) 360px, 720px" src="/img/discord-logo_720x720.webp" alt="Discord Logo"/>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">Discord</h3>
                <p class="card-text">You can also find me on <a href="https://discord.com/users/ifeelanxious" title="Link to Discord user profile.">Discord</a>.</p>
            </div>
        </Card>
    </div>
</div>