<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portal Escolar</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <nav>
            <h1>Portal Escolar</h1>
            <ul>
                <li><a href="#login">Login</a></li>
                <li><a href="#dashboard">Dashboard</a></li>
                <li><a href="#admin">Administração</a></li>
            </ul>
        </nav>
    </header>

    <!-- Login -->
    <section id="login">
        <h2>Login do Aluno</h2>
        <form action="/login" method="post">
            <label for="username">Usuário:</label>
            <input type="text" id="username" name="username" required>
            
            <label for="password">Senha:</label>
            <input type="password" id="password" name="password" required>
            
            <button type="submit">Entrar</button>
        </form>
    </section>

    <!-- Dashboard do Aluno -->
    <section id="dashboard">
        <h2>Dashboard</h2>
        <div>
            <h3>Bem-vindo, [Nome do Aluno]</h3>
            <p><strong>Carteira Estudantil:</strong> [Número]</p>
            <p><strong>Matrícula:</strong> [Status]</p>
            <p><strong>Notas:</strong> [Notas por Matéria]</p>
        </div>
        <div>
            <h3>Projetos e Materiais</h3>
            <ul>
                <li><a href="#">Projeto 1</a></li>
                <li><a href="#">Projeto 2</a></li>
            </ul>
        </div>
    </section>

    <!-- Administração -->
    <section id="admin">
        <h2>Administração</h2>
        <form action="/admin" method="post">
            <label for="student-name">Nome do Aluno:</label>
            <input type="text" id="student-name" name="student-name">
            
            <label for="student-grade">Nota:</label>
            <input type="number" id="student-grade" name="student-grade">
            
            <button type="submit">Salvar</button>
        </form>
    </section>

    <!-- Rodapé -->
    <footer>
        <p>© 2025 Portal Escolar. Todos os direitos reservados.</p>
    </footer>
</body>
</html>
