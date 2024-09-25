<div class="navbar">
  <div class="links">
    <a href="/">Home</a>
    <a href="/omoss">Om Oss</a>
  </div>
  <div class="actions">
    <a href="/nyheter">Nyheter</a>
    <a href="/socials">Socials</a>
  </div>
</div>

<style>
  .navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;
    position: absolute;
    width: 100vw;
    z-index: 999;
  }

  .links {
    display: flex;
    gap: 10px;
  }

  .links a {
    font-size: 20px;
    color: white;
  }

  .actions {
    width: 200px;
    display: flex;
    justify-content: flex-end;
    gap: 10px;
    margin-right: 10px;
  }

  .actions a {
    color: white;
  }
</style>
