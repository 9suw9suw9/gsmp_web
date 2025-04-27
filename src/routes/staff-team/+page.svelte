<title>GoldSMP</title>

<header>
    <nav class="navbar">
      <ul>
        <li><a href="/">Kezdőlap</a></li>
        <li><a href="/staff-team">Staff csapat</a></li>
      </ul>
    </nav>
  </header>

  <main class="centered-container">
    <h1 class="title">A GoldSMP staff csapata</h1>
    <p>Itt vannak azok, akik néha dolgoznak is valamit 😎</p>
  
    <div class="staff-grid">
        <div class="staff-card">
          <img src="/skins/9suw9suw9.png" alt="9suw9suw9" class="staff-skin">
          <p class="staff-name">9suw9suw9</p>
          <p class="staff-role" style="color: #FF0000;">Tulajdonos</p> <!-- Added role with color -->
        </div>
        <div class="staff-card">
          <img src="/skins/ruminiz5.png" alt="Ruminiz5" class="staff-skin">
          <p class="staff-name">Ruminiz5</p>
          <p class="staff-role" style="color: #FF0000;">Tulajdonos</p> <!-- Added role with color -->
        </div>
        <div class="staff-card">
          <img src="/skins/feketefh.png" alt="feketefh" class="staff-skin">
          <p class="staff-name">feketefh</p>
          <p class="staff-role" style="color: #71368A;">Manager</p> <!-- Added role with color -->
        </div>
      </div>
  </main>    
  <footer>
    <p>&copy; 2025 GoldSMP - Made by <a href="https://feketefh.eu" target="_blank" rel="noopener noreferrer" style="color: gold; text-decoration: none;">feketefh</a> & <a href="https://9suw9suw9.hu" target="_blank" rel="noopener noreferrer" style="color: gold; text-decoration: none;">9suw9suw9</a></p>
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

    .centered-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  padding-top: 120px; /* more top padding */
  padding-bottom: 40px;
  min-height: auto; /* no full screen centering */
  box-sizing: border-box;
}


  .title {
  font-size: 3rem;
  color: gold;
  margin-bottom: 20px;
  text-align: center;
  text-shadow: 0 0 10px rgba(255, 215, 0, 0.7);
}

.staff-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 30px;
  margin-top: 40px;
}

.staff-card {
  background-color: rgba(50, 50, 50, 0.8);
  border-radius: 20px;
  padding: 20px;
  width: 200px;
  text-align: center;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.5);
  transition: transform 0.3s ease;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center; /* Center content inside the card */
}

.staff-card:hover {
  transform: scale(1.05);
}

.staff-skin {
  width: 100%;
  max-width: 276px;
  height: auto;
  border-radius: 10px;
  margin-bottom: 15px;
}

.staff-name {
  font-size: 1.2rem;
  font-weight: bold;
  color: gold;
}

.staff-role {
  font-size: 1rem;
  font-weight: bold;
  margin-top: 10px;  /* Space between name and role */
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
  </style>
   