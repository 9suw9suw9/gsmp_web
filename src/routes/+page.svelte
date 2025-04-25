<title>GoldSMP - Kezdőlap</title>

<header>
  <nav class="navbar">
    <ul>
      <li><a href="/">Kezdőlap</a></li>
    </ul>
  </nav>
</header>

<!-- GoldSMP Title -->
<h1 class="title">GoldSMP</h1>

<main class="centered-container">

  <!-- Server Description Section -->
  <div class="server-description">
    <p class="intro">😀 Szeretnél egy Minecraft szervert, ami nem egy újabb “survival de van /kit start” élmény? Hát... mi is. Ezért csináltuk meg a GoldSMP-t.</p>

    <p>Itt nem csak blokkokat ásol, hanem barátságokat is. Meg néha gödröt a spawn közepére – de az adminok már megszokták.</p>

    <h2>Mi vár rád nálunk❓</h2>
    <ul>
      <li>• Egyedi élmények (vagy legalábbis mi annak hívjuk)</li>
      <li>• Egy staff csapat, akik több kávét isznak mint te XP-t farmolsz</li>
      <li>• Eventek, amik néha működnek is!</li>
      <li>• És egy közösség, ahol még senki se kapott bann-t a rossz poénjai miatt. Még.</li>
    </ul>

    <h2></h2>

    <p>👉 Csinálj magadnak egy házat. Vagy egy sárkunyhót. Vagy csak gyere fel, és mondd azt a chatbe, hogy “ez a szerver jobb mint a múltkori”. Mert tényleg az.</p>

    <h3>Csatlakozz most:</h3>
    <p><a class="button" href="https://dc.goldsmp.xyz" target="_blank">Discord</a> | <strong>IP:</strong> play.goldsmp.xyz</p>
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

  .server-description {
    background-color: rgba(50, 50, 50, 0.8);
    backdrop-filter: blur(10px);
    padding: 30px;
    border-radius: 10px;
    text-align: center;
    color: white;
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.3);
    width: 100%;
    max-width: 800px;
    margin: 40px auto;
  }

  .server-description p {
    font-size: 1.2rem;
    line-height: 1.6;
  }

  .server-description h2 {
    margin-top: 20px;
    font-size: 2rem;
  }

  .server-description ul {
    list-style-type: disc;
    padding-left: 20px;
  }

  .server-description h3 {
    margin-top: 30px;
    font-size: 1.5rem;
  }

  .button {
    display: inline-block;
    padding: 10px 20px;
    background-color: gold;
    color: black;
    text-decoration: none;
    font-weight: bold;
    border-radius: 5px;
    margin-top: 10px;
  }

  .button:hover {
    background-color: rgba(255, 215, 0, 0.8);
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
    min-height: calc(80vh - 200px);
    padding: 20px;
    box-sizing: border-box;
    margin-top: 20px;
  }

</style>
