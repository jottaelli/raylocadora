# raylocadora
teste


<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>FERNANDO RAY LOCADORA</title>
  <style>
    body {
  font-family: Arial, sans-serif;
  background-color: #f2f2f2;
  margin: 0;
  padding: 0;
}

header {
  background-color: #333;
  color: #fff;
  padding: 20px;
}

header h1 {
  margin: 0;
}

main {
  margin: 20px;
}

section {
  margin-bottom: 30px;
}

h2 {
  margin-top: 0;
}

form {
  display: flex;
  flex-direction: column;
}

label {
  margin-bottom: 10px;
}

input, button {
  padding: 5px;
  margin-bottom: 20px;
  border-radius: 5px;
  border: 1px solid #ccc;
}

button {
  background-color: #333;
  color: #fff;
  cursor: pointer;
}

table {
  border-collapse: collapse;
  width: 100%;
}

th, td {
  text-align: left;
  padding: 8px;
}

th {
  background-color: #333;
  color: #fff;
}

tr:nth-child(even) {
  background-color: #f2f2f2;
}

footer {
  background-color: #333;
  color: #fff;
  padding: 10px;
  text-align: center;
}

  </style>
</head>
<body>
  <header>
    <h1>FERNANDO RAY LOCADORA</h1>
  </header>

  <main>
    <section>
      <h2>Cadastro de Clientes</h2>
      <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required>

        <label for="telefone">Telefone:</label>
        <input type="tel" id="telefone" name="telefone" required>

        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" required>

        <label for="endereco">Endereço:</label>
        <input type="text" id="endereco" name="endereco" required>

        <label for="comprovante">Comprovante de Residência:</label>
        <input type="file" id="comprovante" name="comprovante" accept=".pdf,.doc,.docx">

        <label for="ficha-criminal">Ficha Criminal:</label>
        <input type="file" id="ficha-criminal" name="ficha crminal" accept=".pdf,.doc,.docx">

        <label for="RG e CNH">RG e CNH:</label>
        <input type="file" id="RG e CNH" name="rg e cnh" accept=".pdf,.doc,.docx">

        <button type="submit">Cadastrar</button>
      </form>
    </section>

    <section id="clientes">
      <h2>Área do Cliente</h2>
      <input type="text" id="pesquisa" placeholder="Pesquisar por nome...">
      <table>
        <thead>
          <tr>
            <th>Nome</th>
            <th>Telefone</th>
            <th>E-mail</th>
            <th>Endereço</th>
            <th>Comprovante de Residência</th>
            <th>Ficha Criminal</th>
            <th>Multas</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>João Silva</td>
            <td>(11) 98765-4321</td>
            <td>joao.silva@gmail.com</td>
            <td>Rua A, 123</td>
            <td><a href="#">Comprovante.pdf</a></td>
            <td>Nenhuma</td>
            <td>
              <ul>
                <li>01/03/2023 - R$50,00 - Excesso de velocidade</li>
                <li>05/03/2023 - R$100,00 - Estacionamento proibido</li>
              </ul>
            </td>
          </tr>
          <tr>
            <td>Maria Santos</td>
            <td>(11) 91234-5678</td>
            <td>maria.santos@gmail.com</td>
            <td>Rua B, 456</td>
            <td><a href="#">Comprovante.pdf</a></td>
            <td>Nenhuma</td>
            <td>
              <ul>
                <li>02/03/2023 - R$75,00 - Ultrapassagem em local proibido</li>
                <li>06/03/2023 - R$150,00 - Falta de capacete</li>
</ul>
</td>
</tr>
</tbody>
</table>
</section>
</main>

</body>
</html>
