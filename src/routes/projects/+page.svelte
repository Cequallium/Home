<script>
  import Github from "$lib/Github.svelte";
  import More from "$lib/More.svelte";
import Title from "$lib/Title.svelte";

</script>

<Title pageName="Projects"/>

<div>
    <div class="card">
        <div class="image">
        </div>
        <div class="description">
            <div class="content">
                <h1>
                    Catppuccin/KDE
                </h1>
                <h2>
                    Contributer
                </h2>
                <p/>
                A soothing pastel theme for KDE
            </div>
            <div class="links">
               <Github href="https://github.com/catppuccin/kde"/>
            </div>
        </div>
    </div>
    <div class="card">
        <div class="image">
        </div>
        <div class="description">
            <div class="content">
                <h1>
                    Catsay
                </h1>
                <h2>
                    Creator
                </h2>
                <p/>
                Cowsay but for Cats!
            </div>
            <div class="links">
               <Github href="https://github.com/cequallium/Catsay"/>
               <More href="Catsay"/>
            </div>
        </div>
    </div>
    <div class="card discontinued">
        <div class="image">
        </div>
        <div class="description">
            <div class="content">
                <h1>
                    Canvas [Discontinued]
                </h1>
                <h2>
                    Creator
                </h2>
                <p/>
                A r/Place clone
            </div>
            <div class="links">
               <Github href="https://github.com/cequallium/Canvas"/>
            </div>
        </div>
    </div>
</div>

<style>
    .card{
        height: 11em;
    }
    .card .image{
        background: linear-gradient(-45deg, var(--accent), var(--green));
    }
    .links{
        height: 2em;
        display: flex;
        flex-direction: row;
        gap: 10px;
    }
    .description{
        display: grid;
        grid-template-rows: 4fr 2em;
    }
    .discontinued{
        transition: 240ms filter;
    }
    .discontinued *{
        opacity: 0.7;
    }
</style>