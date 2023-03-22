<script>
  import Back from "$lib/Back.svelte";

</script>
<body>
    <Back/>
    <div class="content">
        <h1>Catsay</h1>
        <h2>Catsay is a tiny simple cli that prints out cute cats</h2>
        <pre>
            <code>
    catsay "hello world" 3

     /| ､      
    (°､ ｡ 7     hello world
    |､  ~ヽ   
    じしf_,)/
            </code>
        </pre>
    </div>
</body>

<style>
    h1{
        margin-top: 0em;
    }
    .content{
        margin-top: 5vh;
        background-color: var(--base);
        padding: 1em;
    }
    pre{
        border: solid var(--accent) 2px;
        background-color: var(--base5);
        margin: 0em 0.2em;
        color: var(--base4);
        font-size: medium;
        font-weight: 500;
        text-align: left;
        background-image: linear-gradient(0deg, var(--base) 50%, var(--base2) 50%, var(--base2) 100%);
        background-position: 0px 5rem;
        background-size: 1rem 2rem;
    }

</style>