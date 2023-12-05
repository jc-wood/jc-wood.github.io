<script>
    import Card from "$lib/components/Card.svelte";

    const title = 'Coffee';
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>
<p class="lead">My father was a big coffee drinker when I was a kid. As soon as I was old enough, my parents would make me a cup of coffee just like my dad's; a splash milk and packet of Sweet'n Low. <em>My father is diabetic</em>. As I grew older, I lost my taste for coffee though I never lost my enjoyment for the smell of it.</p>
<p class="lead">Years later my girlfriend (now wife), a big iced coffee drinker, got me hooked on the stuff. It turns out that quality beans and extra cream was what I was missing all along! Given that I'm never one to be satisfied the basics of anything, I began a lifelong obsession with finding yummy coffee and great ways to brew it.</p>
<p class="lead">Think I'm kidding about my coffee fanaticism? I named two of my dogs after coffee; Kona and Kahlua.</p>
<hr/>
<div class="alert alert-warning">
    <p class="mb-0">
        The "Golden Ratio" of (drip) coffee brewing is about 2 heaping tablespoons of freshly ground coffee per 6 fl.oz. of water according to the <a class="link-offset-2" href="https://www.ncausa.org/About-Coffee/How-to-Brew-Coffee#:~:text=Coffee%2Dto%2DWater%20Ratio,every%20six%20ounces%20of%20water." title="Link to National Coffee Association website">National Coffee Association</a>.
    </p>
</div>
<h2 class="my-3">Grinds &amp; Gear</h2>
<div class="row row-cols-sm-1 row-cols-md-2 row-cols-lg-4 g-3">
    <div class="col">
        <Card cap={`<img src="/img/grassroots-logo.webp" alt="Grassroots Coffee Co." />`}>
            <h3 class="h5 card-title">Grassroots Coffee</h3>
            <p class="card-text">This local roaster has never let me down. The Sumatra Gayo is a single-origin coffee that is <em>to die for</em>.</p>
            <a class="card-link" href="https://grassrootscoffee.com/collections/coffee" title="Link to Grassroots Coffee's online store.">Go</a>
        </Card>
    </div>
    <div class="col">
        <Card cap={`<img src="/img/moccamaster-logo.webp" alt="Technivorm Moccamaster" />`}>
            <h3 class="h5 card-title">Technivorm Moccamaster</h3>
            <p class="card-text">I don't own one of these yet but it would be an absolute dream to do so. Universally regarded as the best drip coffee maker that you can buy.</p>
            <a class="card-link" href="https://us.moccamaster.com/" title="Link to Technivorm's online store.">Go</a>
        </Card>
    </div>
</div>
