<main>
    <div><h1>Callum Laing</h1></div>
    <div class="links"><a href="#">About</a>
    <a href="#">Projects</a>
    <a href="#">Contact</a></div>
</main>

<style>
    main {
        display: flex;
        justify-content: space-between;
        align-items: center;
        color: white;
        margin-bottom: 100px;
    }

    a {
        text-decoration: none;
        color: white;
        margin-left: 20px;
        font-size: 1.2em;
    }

    a:hover {
        border-bottom: 2px solid yellow;
    }


	.links {
		font-family: "Oregano", cursive;
		letter-spacing: 2px;
	}

@media (max-width: 769px) {
    main {
        display: flex;
        justify-content: space-around;
    } h1 {
        display: none;
    } a {
        font-size: 1em;
    }
}
</style>