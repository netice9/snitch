<script>

</script>

<style>
  nav {
    border-bottom: 1px solid rgba(255, 62, 0, 0.1);
    font-weight: 300;
    padding: 0 1em;
    position: fixed;
    top: 0;
    left: 0;
    width: 100vw;
    display: flex;
    align-items: center;
    justify-content: space-between;
    z-index: 1;
    box-sizing: border-box;
    background: #f8f8f8;
  }

  a.logo {
    text-decoration: none;
    padding: 0.7em 0.5em 0.5em 0.5em;
    display: flex;
    flex-direction: column;
    justify-content: right;
    align-items: flex-end;
  }

  a:hover {
    background-color: #e7e7e780;
  }

  a.active {
    background-color: #e7e7e7;
  }

  a:any-link {
    color: black;
    font-size: 1.5rem;
  }


</style>

<nav>
  <a class="logo" href="/">
    <div class="large">Snitch</div>
  </a>
</nav>
