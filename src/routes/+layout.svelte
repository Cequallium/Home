<script>
    import Navbar from "$lib/Navbar.svelte";
</script>

<svelte:head>
    <style>
        @import '/reset.css';
    </style>
</svelte:head>

<Navbar/>

<div class="Body">
    <slot/>
</div>



<style>
    @import "../../static/card.css";
    :global(body){
        background-color: var(--base2);
        --green: #0ed87b;
        --green2: #0fb37f;
        --purple: #9050ec;
        --purple2: #6236c9;
        --orange: #fdab26;
        --orange2: #f08a0a;
        --base: #f6edfd;
        --base2: #e5ddf9;
        --base3: #3b3b3b;
        --base4: #241935;
        --base5: #120c18;
        --filter-green: invert(51%) sepia(18%) saturate(2463%) hue-rotate(115deg) brightness(100%) contrast(88%);
    }
    @media (prefers-color-scheme: dark) {
        :global(body){
            --base4: #e5ddf9;
            --base: #241935;
            --base2: #120c18;
            --base5: black;
        }
        :global(.card h1){
            --purple2: var(--purple);
        }
    }
    .Body{
        height: calc(100vh - 3em);
        overflow-y: scroll;
        margin: 0vw 10vw;
    }
    :global(::selection){
        background-color: var(--accent);
    }
</style>