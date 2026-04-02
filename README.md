# Test2-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HypixelSMP</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    background: linear-gradient(135deg, #1a0000, #330000, #660000);
    color: white;
    text-align: center;
}

/* Header */
header {
    padding: 40px 20px 20px;
}

h1 {
    font-size: 2.5rem;
    color: #ff3333;
}

.subtitle {
    margin-top: 10px;
}

/* Layout */
.container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    padding: 20px;
}

/* Card */
.card {
    background: rgba(0,0,0,0.7);
    padding: 20px;
    border-radius: 15px;
    width: 300px;
    max-width: 90%;
    box-shadow: 0 0 20px rgba(255,0,0,0.6);
}

/* Button */
button {
    background: #ff3333;
    border: none;
    padding: 12px 18px;
    border-radius: 10px;
    cursor: pointer;
    margin-top: 10px;
    font-weight: bold;
    color: white;
}

button:hover {
    background: #cc0000;
}

/* Status */
.status {
    font-size: 18px;
    margin-top: 10px;
}

/* Footer */
footer {
    margin-top: 20px;
    padding: 20px;
    color: #aaa;
}
</style>
</head>

<body>

<header>
    <h1>HypixelSMP</h1>
    <p class="subtitle">🔥 LifeSteal Minecraft Server 🔥</p>
</header>

<div class="container">

    <!-- Server Status -->
    <div class="card">
        <h2>Server Status</h2>
        <p class="status">🟢 Online</p>
        <p>Players: 500+</p>
    </div>

    <!-- Server Info -->
    <div class="card">
        <h2>Server Info</h2>
        <p><b>Mode:</b> LifeSteal</p>
        <p><b>Version:</b> 1.20+</p>
        <p><b>24/7:</b> Yes</p>
    </div>

    <!-- IP -->
    <div class="card">
        <h2>Server IP</h2>
        <p id="ip">Hypixelsmp.aternos.me</p>
        <button onclick="copyIP()">Copy IP</button>
    </div>

    <!-- Staff -->
    <div class="card">
        <h2>Server Staff</h2>
        <p><b>Owner:</b> senpmaispider</p>
        <p><b>2nd Owner:</b> deadly_araf_og</p>
        <p><b>SR Admin:</b> prohmas</p>
    </div>

    <!-- Discord -->
    <div class="card">
        <h2>Discord</h2>
        <a href="https://discord.gg/R6G7yYpzr" target="_blank">
            <button>Join Server</button>
        </a>
    </div>

</div>

<footer>
    © 2026 HypixelSMP | LifeSteal
</footer>

<script>
function copyIP() {
    const ip = document.getElementById("ip").innerText;
    navigator.clipboard.writeText(ip);
    alert("Copied: " + ip);
}
</script>

</body>
</html>
Test2 
