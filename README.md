# Pasado-simple<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pasado Simple en Inglés</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background: #f4f4f4;
    }
    header {
      background: #2c3e50;
      color: white;
      padding: 20px;
      text-align: center;
    }
    section {
      padding: 20px;
      margin: 15px;
      background: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #2c3e50;
    }
    button {
      background: #3498db;
      color: white;
      border: none;
      padding: 10px 15px;
      margin-top: 10px;
      cursor: pointer;
      border-radius: 5px;
    }
    input {
      padding: 8px;
      margin: 5px 0;
      width: 100%;
    }
  </style>
</head>
<body><header>
  <h1>Pasado Simple en Inglés</h1>
  <p>Aprende los verbos regulares e irregulares</p>
</header><section>
  <h2>¿Qué es el pasado simple?</h2>
  <p>El pasado simple se utiliza para hablar de acciones que ocurrieron en el pasado y ya terminaron.</p>
  <p>Ejemplo: I played soccer (Yo jugué fútbol)</p>
</section><section>
  <h2>Verbos Regulares</h2>
  <p>Los verbos regulares forman el pasado agregando <b>-ed</b>.</p>
  <ul>
    <li>Play → Played</li>
    <li>Work → Worked</li>
    <li>Clean → Cleaned</li>
  </ul>
</section><section>
  <h2>Verbos Irregulares</h2>
  <p>No siguen una regla fija, cambian completamente.</p>
  <ul>
    <li>Go → Went</li>
    <li>Eat → Ate</li>
    <li>See → Saw</li>
  </ul>
</section><section>
  <h2>Ejercicio</h2>
  <p>Escribe la forma en pasado del verbo:</p><label>1. Play:</label> <input id="q1">

<label>2. Go:</label> <input id="q2">

<label>3. Eat:</label> <input id="q3">

<label>4. Work:</label> <input id="q4">

<button onclick="verificar()">Verificar respuestas</button>

  <p id="resultado"></p>
</section><script>
function verificar() {
  let correctas = 0;

  if(document.getElementById('q1').value.toLowerCase() === 'played') correctas++;
  if(document.getElementById('q2').value.toLowerCase() === 'went') correctas++;
  if(document.getElementById('q3').value.toLowerCase() === 'ate') correctas++;
  if(document.getElementById('q4').value.toLowerCase() === 'worked') correctas++;

  document.getElementById('resultado').innerText = 'Respuestas correctas: ' + correctas + '/4';
}
</script></body>
</html>
