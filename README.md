# GPRH
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gestão de Processos RH</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #800000; /* Cor Marrow */
            color: white;
        }
        header {
            background-color: #660000;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        .cta-button {
            background-color: #ffcc00;
            color: #660000;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            text-transform: uppercase;
            cursor: pointer;
        }
        .cta-button:hover {
            background-color: #ff9900;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #660000;
            padding: 10px;
        }
        nav a {
            margin: 0 15px;
            color: white;
            text-decoration: none;
        }
        nav a:hover {
            text-decoration: underline;
        }
        section {
            padding: 20px;
        }
        footer {
            background-color: #660000;
            padding: 20px;
            text-align: center;
        }
        .job-search, .candidate-search {
            background-color: #330000;
            padding: 20px;
            border-radius: 10px;
            margin-bottom: 30px;
        }
        .job-search input, .candidate-search input {
            width: 70%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
        }
        .job-search button, .candidate-search button {
            background-color: #ffcc00;
            color: #660000;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .job-search button:hover, .candidate-search button:hover {
            background-color: #ff9900;
        }
        form input, form textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
        }
        form button {
            background-color: #ffcc00;
            color: #660000;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #ff9900;
        }
        .testimonials blockquote {
            background-color: #330000;
            padding: 15px;
            border-left: 5px solid #ffcc00;
            margin: 20px 0;
        }
    </style>
</head>
<body>

<header>
    <h1>Gestão de Processos RH</h1>
    <h3>Conectando recém-formados a oportunidades de carreira</h3>
    <button class="cta-button">Cadastre-se agora</button>
    <button class="cta-button">Saiba mais</button>
</header>

<nav>
    <a href="#sobre">Sobre Nós</a>
    <a href="#funcionalidades">Funcionalidades</a>
    <a href="#empresas">Para Empresas</a>
    <a href="#testemunhos">Testemunhos</a>
    <a href="#blog">Blog</a>
    <a href="#contato">Contato</a>
</nav>

<section id="pesquisa">
    <h2>Busque sua vaga de emprego</h2>
    <div class="job-search">
        <label for="job-keyword">Palavras-chave:</label>
        <input type="text" id="job-keyword" placeholder="Ex.: Desenvolvedor, Marketing">
        <button type="submit">Buscar Vagas</button>
    </div>

    <h2>Encontre candidatos</h2>
    <div class="candidate-search">
        <label for="candidate-keyword">Palavras-chave:</label>
        <input type="text" id="candidate-keyword" placeholder="Ex.: Engenharia, Administração">
        <button type="submit">Buscar Candidatos</button>
    </div>
</section>

<section id="sobre">
    <h2>Sobre Nós</h2>
    <p><strong>Missão:</strong> Conectar recém-formados e formandos a oportunidades de estágio, trainee e empregos, facilitando a transição para o mercado de trabalho.</p>
    <p><strong>História:</strong> A ideia surgiu ao perceber a dificuldade que muitos recém-formados enfrentam para entrar no mercado de trabalho.</p>
    <p><strong>Valores:</strong> Valorizamos a inovação, acessibilidade e a criação de oportunidades para todos.</p>
</section>

<section id="funcionalidades">
    <h2>Funcionalidades</h2>
    <ul>
        <li><strong>Perfis Personalizados:</strong> Os usuários podem criar perfis detalhados com suas qualificações e aspirações.</li>
        <li><strong>Match Inteligente:</strong> Algoritmos combinam o perfil do candidato com vagas compatíveis.</li>
        <li><strong>Orientação Profissional:</strong> Sessões de coaching, dicas de currículo e preparação para entrevistas.</li>
        <li><strong>Eventos de Networking:</strong> Feiras de emprego e webinars com empresas parceiras.</li>
    </ul>
</section>

<section id="empresas">
    <h2>Para Empresas</h2>
    <p>As empresas podem se cadastrar, postar vagas e acessar um banco de talentos de recém-formados altamente qualificados.</p>
    <p><strong>Parcerias Universitárias:</strong> Universidades podem colaborar, recomendando seus alunos para vagas e facilitando o recrutamento.</p>
</section>

<section id="testemunhos">
    <h2>Testemunhos</h2>
    <div class="testimonials">
        <blockquote>"Consegui meu primeiro emprego graças ao Gestão de Processos RH!" - João Silva</blockquote>
        <blockquote>"A plataforma facilitou o encontro entre meu perfil e a vaga perfeita." - Maria Souza</blockquote>
    </div>
</section>

<section id="blog">
    <h2>Blog</h2>
    <p>Artigos sobre desenvolvimento de carreira, dicas de entrevistas, e muito mais.</p>
</section>

<section id="contato">
    <h2>Contato</h2>
    <form>
        <label for="name">Nome:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">E-mail:</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Mensagem:</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Enviar</button>
    </form>
    <p><strong>Email:</strong> contato@gestaorh.com | <strong>Telefone:</strong> +244 923 456 789</p>
</section>

<footer>
    <p>&copy; 2024 Gestão de Processos RH. Todos os direitos reservados.</p>
</footer>

</body>
</html>
