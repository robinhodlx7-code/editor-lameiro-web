# editor-lameiro-web
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <title>Editor de Lameiro ETS2</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/fabric.js/6.7.1/fabric.min.js"></script>
  <style>
    body { background: #222; color: #eee; font-family: sans-serif; text-align:center; }
    canvas { border: 1px solid #555; margin-top: 10px; }
    #toolbar { margin-top: 10px; }
    button { padding: 8px 12px; margin: 0 5px; }
  </style>
</head>
<body>
  <h2>Editor de Lameiro ETS2</h2>
  <div id="toolbar">
    <input type="file" id="imgLoader" accept="image/*" />
    <button id="addText">Adicionar Texto</button>
    <button id="exportPNG">Exportar PNG</button>
  </div>
  <canvas id="canvas" width="600" height="400"></canvas>
  <script src="app.js"></script>
</body>
</html>
