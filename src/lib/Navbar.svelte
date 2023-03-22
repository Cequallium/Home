<nav class="titlebar">
    <a href="/" class="logo">
        <img src="/logo.svg" alt="logo" srcset="">
    </a>
    <div class="links">
        <a href="/about" class="about">
            <div>
                About
            </div>    
        </a>
        <a href="/projects" class="projects">
            <div>
                Projects
            </div>
        </a>
        <a href="/blog" class="blog">
            <div>
                Blog
            </div>
        </a>
    </div>
</nav>

<style>
    .titlebar{  
        color: white;
        display: grid;
        background-color: var(--base5);
        grid-template-columns: 3em calc(100vw - 3em);
        height: 3em;
    }
    .logo{
        display: flex;
        justify-content: center;
        transition: all 120ms;
    }
    .logo img{
        width: 1.2em;
        filter: invert(45%) sepia(15%) saturate(3923%) hue-rotate(231deg) brightness(101%) contrast(91%);
        transition: all 120ms;
    }
    .logo:hover  > img{
        opacity: 0.9;
        filter: invert(94%) sepia(64%) saturate(1715%) hue-rotate(180deg) brightness(104%) contrast(97%);
    }
    .logo:hover{
        background-color: var(--purple);
    }
    .links{
        display: flex;
    }
    .links a{
        width: 33.3%;
        height: 100%;
        font-size: medium;
        display: flex;
    }
    .links a div{
        margin: auto;
    }
    .links a{
        font-weight: 600;
        border-bottom-width: 0px;
        border-bottom-style: solid;
        transition: 60ms border-bottom;
    }
    .links a:hover{
        border-bottom-width: 2px;
    }
    .about{
        color: var(--purple);
    }
    .about:hover{
        background-color: hsla(265, 80%, 62%, 0.22);
    }
    .projects{
        color: var(--green2);
    }
    .projects:hover{
        background-color: hsla(152, 88%, 45%, 0.22);
    }
    .blog{
        color: var(--orange2);
    }
    .blog:hover{
        background-color: hsla(37, 98%, 57%, 0.22);
    }
</style>