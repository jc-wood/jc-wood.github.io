<script>
    import Card from "$lib/components/Card.svelte";

    const title = 'Music';
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>
<p class="lead">I grew up during the height of Grunge and lived through the Nu-metal explosion of the 90s while being raised on Rock of all varieties. My interests are diverse, though I tend to skew towards the harder, more technically adept tracks. Here's a few items that I adore of you want to check them out.</p>
<hr/>
<div class="row row-cols-sm-1 row-cols-md-3 g-3">
    <div class="col">
        <Card cap={`<iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/9w4TMU7avTY?si=VHL6IHjTx17A6r9f" title="YouTube video player" frameborder="0" allow="encrypted-media; picture-in-picture; web-share" allowfullscreen></iframe>`}>
            <h3 class="h5 card-title">HAMMS IN A GLASS</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Winona Fighter</h4>
        </Card>
    </div>
    <div class="col">
        <Card cap={`<iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/wz56aruweJY?si=xjBhJcvz_w6CL4ef" title="YouTube video player" frameborder="0" allow="encrypted-media; picture-in-picture; web-share" allowfullscreen></iframe>`}>
            <h3 class="h5 card-title">The Motherload</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Mastodon</h4>
        </Card>
    </div>
    <div class="col">
        <Card cap={`<iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/HANCzu70us4?si=6qZWrkyPP0HJAoX8" title="YouTube video player" frameborder="0" allow="encrypted-media; picture-in-picture; web-share" allowfullscreen></iframe>`}>
            <h3 class="h5 card-title">In Due Time</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Killswitch Engage</h4>
        </Card>
    </div>
    <div class="col">
        <Card cap={`<iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/OoQEUVEdwjg?si=sVql1KwVi9d7CWsj" title="YouTube video player" frameborder="0" allow="encrypted-media; picture-in-picture; web-share" allowfullscreen></iframe>`}>
            <h3 class="h5 card-title">Catch Fire</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Periphery</h4>
        </Card>
    </div>
    <div class="col">
        <Card cap={`<iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/qc98u-eGzlc?si=8LnkxCcUTa8CBWKR" title="YouTube video player" frameborder="0" allow="encrypted-media; picture-in-picture; web-share" allowfullscreen></iframe>`}>
            <h3 class="h5 card-title">Bleed</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Meshuggah</h4>
        </Card>
    </div>
    <div class="col">
        <Card cap={`<iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/SecJsEelf3c?si=AcFFw8OhO5S-Og_B" title="YouTube video player" frameborder="0" allow="encrypted-media; picture-in-picture; web-share" allowfullscreen></iframe>`}>
            <h3 class="h5 card-title">Blood on the Sand</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Thrice</h4>
        </Card>
    </div>
    <div class="col">
        <Card cap={`<iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/Z5NoQg8LdDk?si=9rzSZGAjW10oPJl5" title="YouTube video player" frameborder="0" allow="encrypted-media; picture-in-picture; web-share" allowfullscreen></iframe>`}>
            <h3 class="h5 card-title">Playing God</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Polyphia</h4>
        </Card>
    </div>
    <div class="col">
        <Card cap={`<iframe loading="lazy" src="https://www.youtube-nocookie.com/embed/mYgXS2Dft-g?si=CwDZMIWOs0dd43F7" title="YouTube video player" frameborder="0" allow="encrypted-media; picture-in-picture; web-share" allowfullscreen></iframe>`}>
            <h3 class="h5 card-title">The Lines</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Beartooth</h4>
        </Card>
    </div>
</div>


