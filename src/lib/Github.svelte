<script>
    export let href = "";
</script>
<a href="{href}">
    <img src="/github-mark.svg" alt="Github logo" srcset="">
</a>

<style>
    a{
        margin: auto 0em;
    }
    a img{
        padding: 5px;
        filter: var(--filter-green);
        transition: 240ms opacity;
        height: 1em;
        width: 1em;
        /* border: solid 2px var(--accent2); */
    }
    a img:hover{
        opacity: 0.7;
        
    }
</style>