<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Calculadora de IMC</title>
</head>
<body>
  <h1>Calculadora de IMC</h1>
  <form action="/calculate" method="post">
    <label for="weight">Peso (kg):</label>
    <input type="text" id="weight" name="weight" required>
    <br>
    <label for="height">Altura (m):</label>
    <input type="text" id="height" name="height" required>
    <br>
    <button type="submit">Calcular</button>
  </form>
  {{#if imc}}
    <h2>Seu IMC é: {{imc}}</h2>
  {{/if}}
</body>
</html>
