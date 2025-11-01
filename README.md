# site-ong
 site-ong
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <img src="imagem/logo da ong.png" alt="logo" width="150">
  <title>ONG T.A. - Página Inicial</title>
</head>
<body>
  <header>
    <h1>ONG Tecnologia Avançada</h1>
    <nav>
      <a href="index.html">Início</a> |
      <a href="projetos.html">Projetos</a> |
      <a href="cadastro.html">Cadastro</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Quem Somos</h2>
      <p>A ONG Tecnologia Avançada atua desde 2015 levando educação, tecnologia e apoio a famílias carentes.</p>
      
    </section>

    <section>
      <h2>Missão, Visão e Valores</h2>
      <ul>
        <li><strong>Missão:</strong> Transformar vidas através da solidariedade.</li>
        <li><strong>Visão:</strong> Um futuro com mais igualdade.</li>
        <li><strong>Valores:</strong> solidariedáde, família e conhecimento</li>
      </ul>
    </section>

    <section>
      <h2>Contato</h2>
      <p>Email: contato@ongt.a.org</p>
      <p>Telefone: (99) 99999-9999</p>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 ONG T.A. - Todos tem direito a ter acesso a tecnologia</p>
  </footer>
</body>
</html>







<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ONG T.A - Cadastro</title>
</head>
<body>
  <header>
  
    <h1>Cadastro de Voluntários e Doadores</h1>
    <nav>
      <a href="index.html">Início</a> |
      <a href="projetos.html">Projetos</a> |
      <a href="cadastro.html">Cadastro</a>
    </nav>
  </header>

  <main>
    <section>
      <img src="imagem/voluntario da ong.png" alt="voluntario" width="150">
      <h2>Preencha o Formulário</h2>
      
      <form>
        <fieldset>
          <legend>Informações Pessoais</legend>

          <label>Nome Completo:
            <input type="text" name="nome" required>
          </label><br><br>

          <label>E-mail:
            <input type="email" name="email" required>
          </label><br><br>

          <label>CPF:
            <input type="text" name="cpf" placeholder="000.000.000-00" pattern="\d{3}\.\d{3}\.\d{3}-\d{2}" required>
          </label><br><br>

          <label>Telefone:
            <input type="tel" name="telefone" placeholder="(00) 00000-0000" pattern="\(\d{2}\)\s?\d{4,5}-\d{4}" required>
          </label><br><br>

          <label>Data de Nascimento:
            <input type="date" name="nascimento" required>
          </label><br><br>
        </fieldset>

        <fieldset>
          <legend>Endereço</legend>

          <label>Endereço:
            <input type="text" name="endereco" required>
          </label><br><br>

          <label>CEP:
            <input type="text" name="cep" placeholder="00000-000" pattern="\d{5}-\d{3}" required>
          </label><br><br>

          <label>Cidade:
            <input type="text" name="cidade" required>
          </label><br><br>

          <label>Estado:
            <select name="estado" required>
              <option value="">Selecione...</option>
              <option>SP</option>
              <option>RJ</option>
              <option>MG</option>
              <option>BA</option>
              <option>RS</option>
            </select>
          </label><br><br>
        </fieldset>

        <button type="submit">Enviar Cadastro</button>

        
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 ONG T.A. - Cuidando de quem precisa</p>
  </footer>
</body>
</html>






<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ONG T.A. - Projetos</title>
</head>
<body>
  <header>
    <h1>Projetos Sociais</h1>
    <nav>
      <a href="index.html">Início</a> |
      <a href="projetos.html">Projetos</a> |
      <a href="cadastro.html">Cadastro</a>
    </nav>
  </header>

  <main>
    <section>
      <h2>Projeto Educação para Todos</h2>
      <img src="imagem/projeto social da ong.png" alt="projeto social da ong" width="500">
      <p>Oferecemos reforço tecnologico gratuito para crianças em vulnerabilidade social.</p>
    </section>

    <section>
      <h2>Como Ajudar</h2>
      <p>Você pode apoiar nossos projetos de duas formas:</p>
      <ul>
        <li><strong>Doando:</strong> qualquer valor ou aparelho ajuda a transformar vidas.</li>
        <li><strong>Sendo voluntário:</strong> doe seu tempo e conhecimento!</li>
      </ul>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 ONG T.A.- Unidos por um mundo melhor</p>
  </footer>
</body>
</html>
