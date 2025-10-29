# Super-Hero-adventure-Vivek-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Super Hero Run Adventure - Vivek Thakur</title>
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body { overflow: hidden; background: linear-gradient(#87CEEB, #fff); }
  canvas { background: #70c5ce; display: block; margin: 0 auto; }
  #title {
    position: absolute;
    top: 15px; left: 50%; transform: translateX(-50%);
    font-size: 24px; font-weight: bold;
    color: #fff; text-shadow: 2px 2px 4px #000;
    font-family: Arial, sans-serif;
  }
</style>
</head>
<body>
<div id="title">🦸‍♂️ Super Hero Run Adventure — Vivek Thakur</div>
<canvas id="gameCanvas" width="800" height="400"></canvas>

<script>
const canvas = document.getElementById("gameCanvas");
const ctx = canvas.getContext("2
