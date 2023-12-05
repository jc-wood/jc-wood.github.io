<script>
    import Card from "$lib/components/Card.svelte";

    const title = 'Philosophy';
</script>

<svelte:head>
    <title>{title}</title>
</svelte:head>

<h1>{title}</h1>
<p class="lead">Throughout my life I've thought of myself as something of a “free thinker”; always challenging my beliefs and attempting to refine my knowledge into something firm and certain. I now believe that such a goal has always been a <em>fool's errand</em> and that those who go through life with rigid certainty are overconfident in their knowledge and ignorant of their ignorance.</p>
<div class="alert alert-secondary">
<!--     <blockquote class="blockquote mb-0">
        <p>I know that I know nothing.</p>
        <footer class="blockquote-footer">Socrates in <cite>The Apology</cite>, one of the dialogues in the Trial and Death of Socrates.</footer>
    </blockquote> -->
    <figure class="mb-0">
        <blockquote class="blockquote">
            <p>I know that I know nothing.</p>
        </blockquote>
        <figcaption class="blockquote-footer mb-0">
            Socrates in <cite title='The Trial and Death of Socrates: "The Apology"'>The Apology</cite>, one of the dialogues in the Trial and Death of Socrates.
        </figcaption>
    </figure>
</div>
<p class="lead">Are you wiser than Socrates? When Socrates was <a href="https://www.thoughtco.com/what-was-the-charge-against-socrates-121060" title="A link to a ThoughtCo article about the trial">on trial</a>, he recounted the tale of his visit with the Oracle of Delphi. The oracle informed Socrates that he was the wisest person on earth (sic). In contemplating why the oracle would say such a thing, he determined that it was because unlike other people, he knew that he did not know <em>anything</em>. <a href="https://reasonandmeaning.com/2019/11/03/socrates-i-know-that-i-know-nothing/" title="A link to Reason and Meaning">Here's a great breakdown of Socrates' argument.</a></p>
<hr/>
<h2 class="my-4">Brain Nuggets</h2>
<div class="row row-cols-sm-1 row-cols-md-2 row-cols-lg-4 g-3">
    <div class="col">
        <Card>
            <h3 class="h5 card-title">The Myth of Sisyphus</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Albert Camus</h4>
            <p class="card-text">An essay in which the French-Algerian playwrite and author explores the notion of the Absurd, <em>with a capital "A".</em></p>
            <p class="card-text">According to Camus, we are meaning-seeking beings that exist in a universe devoid of any objective meaning to our existence. If this premise is true, why should one go on living?</p>
            <a class="card-link" href="https://archive.org/details/AlbertCamusTheMythOfSisyphus" title="Link to Archive.org">Go</a>
        </Card>
    </div>
    <div class="col">
        <Card>
            <h3 class="h5 card-title">The Trial and Death of Socrates</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Plato</h4>
            <p class="card-text">A collection of dialogues which detail the persecution of Socrates, once held in high esteem for his wisdom, by the citizens of Athens.</p>
            <p class="card-text">There are a lot of parallels to today's political climate with regards to journalism and activism.</p>
            <a class="card-link" href="https://archive.org/details/in.ernet.dli.2015.503536" title="Link to Archive.org">Go</a>
        </Card>
    </div>
    <div class="col">
        <Card>
            <h3 class="h5 card-title">The Nicomachean Ethics</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Aristotle</h4>
            <p class="card-text">A discussion of what constitutes ones character. How does one become courageous without being foolhardy? This is the origin of the term, "the golden mean".</p>
            <a class="card-link" href="https://archive.org/details/in.ernet.dli.2015.183333" title="Link to Archive.org">Go</a>
        </Card>
    </div>
    <div class="col">
        <Card>
            <h3 class="h5 card-title">Philosophize This</h3>
            <h4 class="h6 card-subtitle mb-2 text-body-secondary">Stephen West</h4>
            <p class="card-text">A beginner-friendly podcast about all things philosophy.</p>
            <a class="card-link" href="https://pca.st/philosophize" title="Link to Pocket Casts' hub">Go</a>
        </Card>
    </div>
</div>