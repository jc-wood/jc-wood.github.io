<script>
    import Card from "$lib/components/Card.svelte";

    const title = 'Music';
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1 class="display-3">{title}</h1>
<p>I grew up during the height of Grunge and lived through the Nu-metal explosion of the 90s while being raised on Rock of all varieties. My interests are diverse, though I tend to skew towards the harder, more technically adept tracks.</p>
<p>I went to my first concert when I was about 12 years old. My cousins took me to Music Midtown in Atlanta, Georgia. I remember when Silverchair took the stage and played an amazing set. The crowd became an timultuous sea of people; jumping and bobbing and tumbling to the song blaring over the speakers; I think it was "Slave", from their album "Freak Show" which had recently debuted.</p>
<p>Here's a few items that I adore of you want to check them out.</p>

<div class="row row-cols-sm-1 row-cols-md-3 g-3 mt-4">
    <div class="col">
        <Card>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">HAMMS IN A GLASS</h3>
                <h4 class="h6 card-subtitle mb-2 text-body-secondary">Winona Fighter</h4>
                <a class="card-link" href="https://www.youtube.com/watch?v=9w4TMU7avTY">Youtube</a><a class="card-link" href="https://open.spotify.com/track/3249EJWdvR7xuLbXoxvLcJ">Spotify</a>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">The Motherload</h3>
                <h4 class="h6 card-subtitle mb-2 text-body-secondary">Mastodon</h4>
                <a class="card-link" href="https://www.youtube.com/watch?v=wz56aruweJY">Youtube</a><a class="card-link" href="https://open.spotify.com/track/6EF0xhfKtQNqUPz2mnE5BD">Spotify</a>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">In Due Time</h3>
                <h4 class="h6 card-subtitle mb-2 text-body-secondary">Killswitch Engage</h4>
                <a class="card-link" href="https://youtu.be/HANCzu70us4">Youtube</a><a class="card-link" href="https://open.spotify.com/track/1HlOGL1p6wlpOZatJ2NwFk">Spotify</a>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">Catch Fire</h3>
                <h4 class="h6 card-subtitle mb-2 text-body-secondary">Periphery</h4>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">Bleed</h3>
                <h4 class="h6 card-subtitle mb-2 text-body-secondary">Meshuggah</h4>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">Blood on the Sand</h3>
                <h4 class="h6 card-subtitle mb-2 text-body-secondary">Thrice</h4>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">Playing God</h3>
                <h4 class="h6 card-subtitle mb-2 text-body-secondary">Polyphia</h4>
            </div>
        </Card>
    </div>
    <div class="col">
        <Card>
            <div slot="body" class="card-body">
                <h3 class="h5 card-title">The Lines</h3>
                <h4 class="h6 card-subtitle mb-2 text-body-secondary">Beartooth</h4>
            </div>
        </Card>
    </div>
</div>


