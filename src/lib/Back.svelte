<button class="back" on:click={() => {window.history.back()}}>
    ←
</button>

<style>
    .back{
        margin-top: 5vh;
        height: 2rem;
        width: 2rem;
        color: var(--accent);
        background-color: var(--base);
        transition: all 240ms;
    }
    .back:hover{
        background-color: var(--accent);
        color: var(--base);
    }
</style>