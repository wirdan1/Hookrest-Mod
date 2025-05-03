<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Hookrest Mod Apk</title>
  <link rel="icon" href="Hookrest.png" type="image/png" />
  <style>
    :root {
      --primary: #4e54c8;
      --secondary: #8f94fb;
      --background: #f0f2f5;
      --card-bg: #fff;
      --text: #333;
      --radius: 12px;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: var(--background);
      color: var(--text);
    }

    header {
      background: linear-gradient(to right, var(--primary), var(--secondary));
      padding: 2rem;
      text-align: center;
      color: white;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
      letter-spacing: 1px;
    }

    .search-box {
      max-width: 600px;
      margin: 2rem auto;
      display: flex;
      box-shadow: 0 5px 15px rgba(0,0,0,0.1);
      border-radius: var(--radius);
      overflow: hidden;
    }

    .search-box input {
      flex: 1;
      padding: 1rem;
      font-size: 1rem;
      border: none;
      outline: none;
    }

    .search-box button {
      background: var(--primary);
      color: white;
      border: none;
      padding: 1rem 1.5rem;
      font-size: 1rem;
      cursor: pointer;
      transition: background 0.3s ease;
    }

    .search-box button:hover {
      background: var(--secondary);
    }

    .results {
      max-width: 1200px;
      margin: 0 auto;
      padding: 2rem;
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(280px, 1fr));
      gap: 2rem;
    }

    .card {
      background: var(--card-bg);
      border-radius: var(--radius);
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      overflow: hidden;
      display: flex;
      flex-direction: column;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.15);
    }

    .card img {
      width: 100%;
      height: 180px;
      object-fit: cover;
    }

    .card-content {
      padding: 1rem;
      flex-grow: 1;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    .card-content h2 {
      font-size: 1.1rem;
      margin: 0 0 0.5rem;
    }

    .card-content p {
      margin: 0.3rem 0;
      font-size: 0.9rem;
    }

    .card-content a {
      margin-top: 0.5rem;
      background: var(--secondary);
      padding: 0.5rem 1rem;
      color: white;
      text-align: center;
      text-decoration: none;
      border-radius: 6px;
      transition: background 0.3s ease;
    }

    .card-content a:hover {
      background: var(--primary);
    }

    .loading, .no-result {
      text-align: center;
      font-size: 1.2rem;
      margin-top: 3rem;
      color: #666;
    }
  </style>
</head>
<body>

  <header>
    <h1>Hookrest Mod Apk</h1>
  </header>

  <div class="search-box">
    <input type="text" id="searchInput" placeholder="Contoh: Subway Surfers" />
    <button onclick="searchGame()">Cari</button>
  </div>

  <div id="results" class="results"></div>
  <div id="statusMessage" class="loading"></div>

  <script>
    async function searchGame() {
      const query = document.getElementById("searchInput").value.trim();
      const results = document.getElementById("results");
      const statusMessage = document.getElementById("statusMessage");

      if (!query) {
        statusMessage.textContent = "Silakan masukkan nama game...";
        results.innerHTML = "";
        return;
      }

      statusMessage.textContent = "Memuat hasil...";
      results.innerHTML = "";

      try {
        const response = await fetch(`https://hookrest-api.vercel.app/apk/happymod?search=${encodeURIComponent(query)}`);
        const json = await response.json();

        if (!json.status || json.data.length === 0) {
          statusMessage.textContent = "Tidak ditemukan.";
          return;
        }

        statusMessage.textContent = "";
        json.data.forEach(app => {
          const card = document.createElement("div");
          card.className = "card";
          card.innerHTML = `
            <img src="${app.image}" alt="${app.title}">
            <div class="card-content">
              <h2>${app.title}</h2>
              <p><strong>Versi:</strong> ${app.version}</p>
              <p><strong>Fitur MOD:</strong> ${app.modFeatures || "Tidak tersedia"}</p>
              <p><strong>Rating:</strong> ${app.rating.value} (${app.rating.percentage}%)</p>
              <a href="${app.link}" target="_blank">Download</a>
            </div>
          `;
          results.appendChild(card);
        });

      } catch (error) {
        statusMessage.textContent = "Gagal mengambil data.";
        console.error(error);
      }
    }
  </script>
</body>
</html>
