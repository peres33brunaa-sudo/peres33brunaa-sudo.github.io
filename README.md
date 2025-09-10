<canvas id="gameCanvas" width="800" height="600"></canvas>
<script src="script.js"></script>
<link rel="stylesheet" href="style.css">
body {
    background: linear-gradient(135deg, #3b0a45, #6a0dad, #b44ef0);
}
canvas {
    border: 3px solid #fff;
}
let player = { x: 400, y: 300, form: 'esqueleto' };
// Movimento com setas
document.addEventListener('keydown', e => { if(e.key === 'ArrowUp') player.y -= 4; });
