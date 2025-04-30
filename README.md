<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Cadastro de Cliente Reprovado</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f8f9fa;
      padding: 40px;
    }
    .form-container {
      background-color: #fff;
      padding: 20px 30px;
      border-radius: 8px;
      max-width: 500px;
      margin: auto;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      text-align: center;
      color: #333;
    }
    label {
      font-weight: bold;
    }
    input, textarea, button {
      width: 100%;
      padding: 10px;
      margin-top: 6px;
      margin-bottom: 20px;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    button {
      background-color: #007bff;
      color: white;
      font-weight: bold;
      cursor: pointer;
    }
    button:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

<div class="form-container">
  <h2>Cadastro de Cliente</h2>
  <form action="https://script.google.com/macros/s/AKfycbyXCbn6uNXM0KFA3FalUqgBfFsmLAXgVasziZAK0BU1MUVS4PYRZdc8mRRbDNnyKtLZ/exec" method="post">
    <label>Nome do cliente:</label>
    <input type="text" name="nome" required>

    <label>Telefone do cliente:</label>
    <input type="tel" name="telefone" required>

    <label>Observações:</label>
    <textarea name="observacoes"></textarea>

    <button type="submit">Enviar</button>
  </form>
</div>

</body>
</html>
