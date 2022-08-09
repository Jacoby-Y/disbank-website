
<nav>
    <a href="/">
        <img id="nav-img" class="img-fluid" src="hero.png" alt="Hero">
    </a>
    <a href="/">Home</a>
    <a href="/">Invite</a>
    <a href="/">Support</a>
    <a href="/">Dashboard</a>

    <a id="login" href="/login">Login</a>
</nav>

<style>
    nav {
        width: 100%;
        display: flex;
        justify-content: center;
        padding: 1rem;
        height: max-content;
        position: relative;
        background-color: #1a1c22;
    }
    #nav-img {
        position: absolute;
        height: 90%;
        left: 2rem;
        top: 0.3rem;
    }
    a {
        color: #FFEFA6;
        padding: 1rem;
        transition-duration: 0.3s;
        font-size: 1.2rem;
    }
    a:hover {
        color: #FFD55F;
    }
    a#login {
        position: absolute;
        right: 2rem;
        top: 1rem;
    }
</style>