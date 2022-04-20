<header>
    <h1>Adrian T.</h1>
    <nav>
        <a href="##">Films</a>
        <a href="##">Photography</a>
        <a href="##">Animation</a>
        <a href="##">Programming</a>
        <a href="##">Contact</a>
    </nav>
</header>
<main>
    <video autoplay muted loop>
        <source src="videos/Butter-Milk-Media-Reel.mp4" type="video/mp4">
    </video>
</main>

<style>
    :root {
        --primary-color: gold;
    }
    header {
        padding: 1rem 2rem;
        color: white;
        background-color: rgba(0, 0, 0, .15);
        backdrop-filter: blur(5px);

        display: flex;
        justify-content: space-between;
        align-items: center;
        position: absolute;
        z-index: 1;
        width: 100%;
    }
    h1 {
        font-size: 1.5rem;
        margin: 0.5rem;
    }
    nav {
        margin: 0;
        padding: 0;
    }
    nav a {
        text-decoration: none;
        color: white;
        padding: 1rem;
    }
    nav a:hover {
        color: var(--primary-color)
    }
    video {
        position: fixed;
        margin: 0 auto;

        min-height: 100%;
        width: auto;
    }
</style>
