<script>
    import Card from "$lib/components/Card.svelte";

    const title = 'Podcasts';
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1 class="display-3">{title}</h1>
<p>I'm old enough to remember when podcasts first came into the scene. iPods were the tech accessory that everyone wanted. If you had one you were instantly cool. My buddy, Christian (though we always called him, “Wookie”), had one with 40 Gbs of storage and just about every song on it that you could imagine.</p>
<p>At the time, though, I wasn't too big on listening to podcasts but I was interested in making them. A few years back I figured out that they help me to pass the time at work and are great to listen to on long trips.</p>
<p>I'd now consider myself to be a pretty big fan of the medium.</p>
<div class="row row-cols-sm-1 row-cols-md-3 g-3 mt-4">
    <div class="col">
        <Card>
            <h3 class="h5 card-title">How Did This Get Made?</h3>
            <p class="card-text">HDTGM is a podcast that examines both B-movies and big blockbusters with unbelievable plot hooks, strange scripts, and odd dialogue. They discuss the movies as well as any weird behind-the-scenes tales that may have plagued the production, cast, or crew. Not only is it informative but it's also hilarious. <em>GEOSTORM!</em></p>
            <a class="card-link" href="https://www.earwolf.com/show/how-did-this-get-made/">Go</a>
        </Card>
    </div>
    <div class="col">
        <Card>
            <h3 class="h5 card-title">Worlds Beyond Number</h3>
            <p class="card-text">If you are already a fan of Dropout’s “Dimension 20”, then you'll already be familiar with the cast of “Worlds Beyond Number”. If not, then is a great entry point for those who are interested in group storytelling or tabletop roleplay.</p>
            <a class="card-link" href="https://worldsbeyondnumber.com/">Go</a>
        </Card>
    </div>
    <div class="col">
        <Card>
            <h3 class="h5 card-title">The Truth</h3>
            <p class="card-text">Short-form storytelling at its best. If you're a fan of “The Outer Limits”, “The Twilight Zone”, or “Black Mirror“ then you'll undoubtedly appreciate this show.</p>
            <a class="card-link" href="https://www.thetruthpodcast.com/">Go</a>
        </Card>
    </div>
</div>