<script>
    /**@type {string|null}*/
    export let cap = null;
</script>

<div class="card">
    {#if cap}
    {@html cap}
    {/if}
    <div class="card-body">
        <slot/>
    </div>
</div>