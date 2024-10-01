# Higanbana
<html>

<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width">
  <title>replit</title>
  <h2> Formulário</h2>
  <link href="style.css" rel="stylesheet" type="text/css" />
</head>

<body>
  <form>
    <div>
      <label for="name"> Nome: </label>
      <input type="text" id="name" name="user_name"/> 
    </div>
    <div>
      <label for="idade"> Idade: </label>
      <input type="number" id="idade" name="user_age" min="1" max="100"/>
    </div>
    <div>
      <label for="cidade"> Cidade: </label>
      <input type="text" id="cidade" name="user_city"/>
    </div>
    <div>
      <label for="CPF"> CPF: </label>
      <input min="1" type="number" id="CPF" name="user_CPF"/>
    </div> 
    <button name="button">Enviar dados</button> 
  </form>
</body>

</html>
