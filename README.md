<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cozinhas Industriais - Equipamentos de Qualidade</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header>
    <div class="logo">
      <h1>Cozinhas Industriais</h1>
    </div>
    <nav>
      <ul>
        <li><a href="#produtos">Produtos</a></li>
        <li><a href="#sobre">Sobre Nós</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="hero">
      <h2>Equipamentos Industriais de Alta Qualidade</h2>
      <p>Transforme sua cozinha com os melhores produtos do mercado.</p>
      <a href="#produtos" class="btn">Confira nossos produtos</a>
    </section>

    <section id="produtos">
      <h2>Nossos Produtos</h2>
      <div class="produto">
        <img src="fogao-industrial.jpg" alt="Fogão Industrial">
        <h3>Fogão Industrial</h3>
        <p>Alta potência e durabilidade.</p>
        <span>R$ 2.500,00</span>
      </div>
      <div class="produto">
        <img src="coifa-industrial.jpg" alt="Coifa Industrial">
        <h3>Coifa Industrial</h3>
        <p>Eficiência máxima na exaustão.</p>
        <span>R$ 1.800,00</span>
      </div>
      <!-- Adicione mais produtos -->
    </section>

    <section id="sobre">
      <h2>Sobre Nós</h2>
      <p>Somos líderes no mercado de equipamentos para cozinhas industriais, oferecendo soluções práticas e eficientes para o seu negócio.</p>
    </section>

    <section id="contato">
      <h2>Contato</h2>
      <form>
        <label for="nome">Nome:</label>
        <input type="text" id="nome" name="nome" required>

        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" required>

        <label for="mensagem">Mensagem:</label>
        <textarea id="mensagem" name="mensagem" rows="4" required></textarea>

        <button type="submit">Enviar</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Cozinhas Industriais. Todos os direitos reservados.</p>
  </footer>
</body>
</html> 

body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  color: #333;
}

header {
  background: #0078D4;
  color: #fff;
  padding: 20px 0;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
}

nav ul li {
  display: inline;
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
}

#hero {
  text-align: center;
  padding: 50px 20px;
  background: #f4f4f4;
}

#hero .btn {
  display: inline-block;
  padding: 10px 20px;
  background: #0078D4;
  color: #fff;
  text-decoration: none;
  margin-top: 20px;
  border-radius: 5px;
}

#produtos {
  padding: 50px 20px;
  background: #fff;
  text-align: center;
}

.produto {
  display: inline-block;
  margin: 15px;
  text-align: center;
}

.produto img {
  width: 200px;
  height: auto;
  border-radius: 5px;
}

footer {
  background: #333;
  color: #fff;
  text-align: center;
  padding: 10px 0;
}
