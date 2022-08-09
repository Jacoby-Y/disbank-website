<nav class="d-none d-md-flex">
  <a href="/">
    <img id="nav-img" class="img-fluid" src="hero.png" alt="Hero" />
  </a>
  <a href="/">Home</a>
  <a href="/invite">Invite</a>
  <a href="/support">Support</a>
  <a href="/dashboard">Dashboard</a>

  <a id="login" href="/login">Login</a>
</nav>

<nav class="navbar navbar-dark bg-dark fixed-top d-md-none">
  <div class="container-fluid">
    <a href="/">
      <img id="nav-img" class="img-fluid" src="hero.png" alt="Hero" />
    </a>
    <button
      class="navbar-toggler"
      type="button"
      data-bs-toggle="offcanvas"
      data-bs-target="#offcanvasDarkNavbar"
      aria-controls="offcanvasDarkNavbar"
    >
      <span class="navbar-toggler-icon" />
    </button>
    <div
      class="offcanvas offcanvas-end text-bg-dark"
      tabindex="-1"
      id="offcanvasDarkNavbar"
      aria-labelledby="offcanvasDarkNavbarLabel"
    >
      <div class="offcanvas-header">
        <button
          type="button"
          class="btn-close btn-close-white"
          data-bs-dismiss="offcanvas"
          aria-label="Close"
        />
      </div>
      <div class="offcanvas-body">
        <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
          <li class="nav-item"><a class="nav-link" href="/">Home</a></li>
          <li class="nav-item">
            <a class="nav-link" href="/invite">Invite</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/support">Support</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/dashboard">Dashboard</a>
          </li>
          <li class="nav-item"><a class="nav-link" href="/login">Login</a></li>
        </ul>
      </div>
    </div>
  </div>
</nav>

<style>
    nav {
        width: 100%;
        display: flex;
        justify-content: center;
        padding: 1rem;
        height: max-content;
        position: relative;
        background-color: #1a1c22 !important;
    }
    #nav-img {
        position: absolute;
        height: 90%;
        left: 2rem;
        top: 0.3rem;
    }
    a, a.nav-link {
        color: #ffefa6;
        padding: 1rem;
        transition-duration: 0.3s;
        font-size: 1.2rem;
    }
    a:hover, a.nav-link:hover {
        color: #ffd55f;
    }
    a#login {
        position: absolute;
        right: 2rem;
        top: 1rem;
    }

    nav .offcanvas-header {
        position: absolute;
        right: 0.5rem;
        top: 0.5rem;
    }
</style>
