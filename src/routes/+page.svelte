<title>GoldSMP - Kezdőlap</title>

<header>
  <nav class="navbar">
    <ul>
      <li><a href="/">Kezdőlap</a></li>
    </ul>
  </nav>
</header>

<footer>
  <p>&copy; 2025 GoldSMP - Made by feketefh & 9suw9suw9</p>
</footer>

<style>
  :global(body) {
    background-color: black;
    color: white;
    margin: 0;
    padding: 0;
  }

  header {
    position: fixed;
    top: 0;
    width: 100%;
    background-color: rgba(0, 0, 0, 0.5); /* Transparent background */
    padding: 10px 20px;
    z-index: 1000;
  }

  .navbar ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center; /* Center the content horizontally */
  }

  .navbar li {
    margin-right: 20px;
  }

  .navbar a {
    text-decoration: none;
    color: white;
    font-weight: bold;
  }

  .navbar a:hover {
    text-decoration: underline;
  }

  footer {
    text-align: center;
    padding: 20px 0;
    background-color: rgba(0, 0, 0, 0.8); /* valami */
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
    font-size: 0.8rem;
  }
</style>