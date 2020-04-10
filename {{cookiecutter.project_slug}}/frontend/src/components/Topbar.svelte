<script>
  export let segment
</script>

<style>
  nav {
    position: fixed;
    left: 0;
    right: 0;
    top: 0;
    bottom: auto;
    z-index: 101;
    width: 100%;
    background-color: #222e44;
    color: #fff;
  }
  ul {
    display: flex;
    min-height: 4.64286rem;
    width: 100%;
    margin: 0;
    padding: 0;
  }
  /* clearfix */
  ul::after {
    content: '';
    clear: both;
  }
  li {
    display: flex;
    align-items: center;
    justify-content: center;
  }
  a {
    font-size: 0.92857rem;
    text-decoration: none;
  }
  .logo {
    width: 250px;
    background-color: #2e3c56;
  }
  .user {
    margin-left: auto;
    padding-right: 1.25em;
  }
</style>

<nav>
  <ul>
    <li class='logo'>
      <a href='.'>home</a>
    </li>
    <li class='user'>
      <a rel=prefetch href='blog'>user</a>
    </li>
  </ul>
</nav>
