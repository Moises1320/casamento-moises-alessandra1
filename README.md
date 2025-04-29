<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Confirmação de Presença - Moises & Alessandra</title>
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #f4f4f2;
      color: #2e3d2f;
    }

    header {
      background-color: #556b2f;
      color: white;
      padding: 2rem;
      text-align: center;
    }

    h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    section {
      padding: 2rem;
      max-width: 600px;
      margin: auto;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0,0,0,0.1);
    }

    form {
      display: flex;
      flex-direction: column;
    }

    label {
      margin-top: 1rem;
      font-weight: bold;
    }

    input, select, textarea {
      padding: 0.7rem;
      margin-top: 0.3rem;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1rem;
    }

    button {
      margin-top: 2rem;
      padding: 1rem;
      background-color: #6b8e23;
      color: white;
      border: none;
      border-radius: 5px;
      font-size: 1.2rem;
      cursor: pointer;
    }

    button:hover {
      background-color: #556b2f;
    }

    footer {
      text-align: center;
      padding: 2rem;
      color: #6b8e23;
    }
  </style>
</head>
<body>
  <header>
    <h1>Moises & Alessandra</h1>
    <p>08 de junho de 2025</p>
  </header>

  <section>
    <h2>Confirme sua presença</h2>
    <form action="https://formspree.io/f/xzzrdgvp" method="POST">
      <label for="nome">Nome Completo</label>
      <input type="text" name="nome" id="nome" required />

      <label for="presenca">Você vai comparecer?</label>
      <select name="presenca" id="presenca" required>
        <option value="">Selecione</option>
        <option value="Sim">Sim, estarei presente</option>
        <option value="Não">Não poderei comparecer</option>
      </select>

      <label for="mensagem">Mensagem (opcional)</label>
      <textarea name="mensagem" id="mensagem" rows="4"></textarea>

      <button type="submit">Enviar Confirmação</button>
    </form>
  </section>

  <footer>
    Aguardamos você com carinho!
  </footer>
</body>
</html>
