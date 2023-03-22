<script>
  import Title from "$lib/Title.svelte";

</script>

<Title pageName="Home"/>

<body>
    <div class="card">
        <div class="image"></div>
        <div class="description">
            <h1>hey.</h1>
            <p>
            I'm Cequal, a Coder & Designer
            <p>
            Welcome to my site
            <p>
            
        </div>
    </div>
</body>


<style>
    @import "../../static/card.css";
    .card .image{
        background: linear-gradient(-45deg, var(--purple2), var(--purple));
    }
    .card{
        --accent: var(--purple);
    }
</style>
