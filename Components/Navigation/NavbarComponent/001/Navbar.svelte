<script>
  import "./main.css";
  export let routes = ["home", "about"];
</script>

<nav>
  <div class="left">
    <a href="/">
      <h1>Logo</h1>
    </a>
  </div>
  <div class="wrapper">
    <div class="center">
      <ul>
        {#each routes as route}
          <li><a href={route}>{route}</a></li>
        {/each}
      </ul>
    </div>
    <div class="right">
      <button>Get started <span /></button>
    </div>
  </div>
</nav>
