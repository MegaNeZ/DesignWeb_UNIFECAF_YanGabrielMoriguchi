# DesignWeb_UNIFECAF_YanGabrielMoriguchi

HTML:
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biblioteca Digital UniFECAF</title>
    <link rel="stylesheet" href="css/styles.css">
</head>
<body>

    <header>
        <h1>Biblioteca UniFECAF</h1>
        <nav>
            <a href="#inicio">Início</a>
            <a href="#livros">Livros</a>
            <a href="#servicos">Serviços</a>
        </nav>
    </header>

    <section id="inicio" class="banner">
        <h2>Bem-vindo à Biblioteca Digital</h2>
        <p>Encontre livros e materiais acadêmicos para o seu curso.</p>
    </section>

    <section id="livros" class="container">
        <h2>Livros em Destaque</h2>
        <div class="cards">
            <div class="card">
                <h3>Sistemas de Informação</h3>
                <p>Fundamentos de TI e Banco de Dados.</p>
            </div>
            <div class="card">
                <h3>Engenharia de Software</h3>
                <p>Boas práticas de desenvolvimento web.</p>
            </div>
            <div class="card">
                <h3>Gestão de Projetos</h3>
                <p>Organização e metodologias.</p>
            </div>
        </div>
    </section>

    <section id="servicos" class="container bg">
        <h2>Serviços</h2>
        <p>Empréstimo de e-books, reservas online e suporte acadêmico 24h.</p>
    </section>

    <footer>
        <p>&copy; 2026 UniFECAF - Desenvolvido para Design Web</p>
        <p>Feito Por: Yan Gabriel Moriguchi Caetano Barbosa (Aluno da UNIFECAF)</p>
    </footer>

</body>
</html>

CSS:
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}

body {
    background-color: #f4f4f4;
    color: #333;
    line-height: 1.5;
}

header {
    background: #0A2540;
    color: white;
    padding: 1rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

nav a {
    color: white;
    text-decoration: none;
    margin-left: 15px;
    font-weight: bold;
}

nav a:hover {
    color: #FF9900;
}

.banner {
    background: #0056B3;
    color: white;
    text-align: center;
    padding: 3rem 1rem;
}

.container {
    padding: 2rem 1rem;
    max-width: 1000px;
    margin: 0 auto;
}

.cards {
    display: flex;
    gap: 20px;
    flex-wrap: wrap;
    margin-top: 1rem;
}

.card {
    background: white;
    padding: 1.5rem;
    border-radius: 7px;
    flex: 1;
    min-width: 250px;
    box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    transition: transform 0.3s ease;
    /* cursor: pointer; */
}

.card:hover {
    transform: scale(1.07);
    /* background-color: black;
    color: #FFF; */
}

.bg {
    background: #e9ecef;
}

footer {
    background: #0A2540;
    color: white;
    text-align: center;
    padding: 1rem;
    margin-top: 17rem;
}
