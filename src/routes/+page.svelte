<title>GoldSMP - Kezdőlap</title>

<header>
  <nav class="navbar">
    <ul>
      <li><a href="/">Kezdőlap</a></li>
    </ul>
  </nav>
</header>

<!-- asdf -->
<h1 class="title">GoldSMP</h1>

<main class="centered-container">
  <div class="content-box">
    <h1>placeholder h1</h1>
    <p>placeholder p</p>
  </div>
</main>

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
    background-color: rgba(0, 0, 0, 0.5);
    padding: 10px 20px;
    z-index: 1000;
  }

  .navbar ul {
    list-style: none;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
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

  .title {
    margin-top: 100px; 
    text-align: center;
    font-size: 4rem;
    font-weight: 900;
    color: gold;
    text-shadow: 0 0 10px rgba(255, 215, 0, 0.8);
  }

  footer {
    text-align: center;
    padding: 20px 0;
    background-color: rgba(0, 0, 0, 0.8);
    color: white;
    position: fixed;
    bottom: 0;
    width: 100%;
    font-size: 0.8rem;
  }

  .centered-container {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: calc(100vh - 400px); /* Leaves room for header + footer */
  padding: 20px;
  box-sizing: border-box;
  margin-top: 40px; /* optional: space between title and content */
}


  .content-box {
    background-color: rgba(50, 50, 50, 0.8);
    backdrop-filter: blur(10px);
    padding: 20px;
    border-radius: 10px;
    text-align: center;
    color: white;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
  }
</style>
