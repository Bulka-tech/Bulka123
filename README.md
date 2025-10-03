<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Rocket League Ranking System</title>
  <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-900 text-white min-h-screen flex flex-col items-center p-6">
  <header class="text-center mb-6">
    <h1 class="text-4xl font-bold text-orange-400">🚀 Rocket League Ranking System</h1>
    <p class="text-gray-400 mt-2">Add your player name and rank!</p>
  </header>

  <main class="w-full max-w-md bg-gray-800 rounded-2xl p-6 shadow-lg">
    <form id="rankForm" class="flex flex-col gap-4">
      <input 
        id="playerName" 
        type="text" 
        placeholder="Enter your player name" 
        class="p-3 rounded-lg text-gray-900 focus:outline-none"
        required
      >
      <select id="playerRank" class="p-3 rounded-lg text-gray-900" required>
        <option value="">Select Rank</option>
        <option>Bronze</option>
        <option>Silver</option>
        <option>Gold</option>
        <option>Platinum</option>
        <option>Diamond</option>
        <option>Champion</option>
        <option>Grand Champion</option>
        <option>Supersonic Legend</option>
      </select>
      <button 
        type="submit" 
        class="bg-orange-500 hover:bg-orange-600 text-white font-bold py-2 px-4 rounded-lg"
      >
        Add Player
      </button>
    </form>

    <h2 class="text-2xl font-semibold mt-8 mb-4 text-center">🏆 Player Rankings</h2>
    <ul id="playerList" class="space-y-3">
      <!-- Players will appear here -->
    </ul>
  </main>

  <footer class="mt-10 text-gray-500 text-sm">
    Made by Kevin 🚗💨
  </footer>

  <script>
    const rankForm = document.getElementById("rankForm");
    const playerList = document.getElementById("playerList");

    rankForm.addEventListener("submit", (e) => {
      e.preventDefault();

      const name = document.getElementById("playerName").value.trim();
      const rank = document.getElementById("playerRank").value;

      if (!name || !rank) return;

      const li = document.createElement("li");
      li.className = "bg-gray-700 p-3 rounded-lg flex justify-between items-center";
      li.innerHTML = `
        <span class="font-semibold text-orange-300">${name}</span>
        <span class="text-gray-300">${rank}</span>
      `;

      playerList.appendChild(li);
      rankForm.reset();
    });
  </script>
</body>
</html>

