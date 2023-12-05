<script>
    let isCollapsed = true;

    function toggleMenu() {
        isCollapsed = !isCollapsed;
    }
</script>

<nav class="navbar navbar-expand-lg">
    <div class="container">
      <a class="navbar-brand" href="/">Josh Wood</a>
      <button on:click={toggleMenu} class="navbar-toggler" type="button" aria-controls="main-menu" aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class:collapse={isCollapsed} class="navbar-collapse" id="main-menu">
        <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
          <li class="nav-item">
            <a class="nav-link" href="/music">Music</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/coffee">Coffee</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/philosophy">Philosophy</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/games">Games</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="/podcasts">Podcasts</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>