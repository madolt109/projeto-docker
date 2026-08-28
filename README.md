```html
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Projeto Docker - Nginx</title>
</head>

<body>

    <h1>🐳 Projeto Docker - Nginx</h1>

    <p>
        Este projeto foi desenvolvido durante a aula para aprender os conceitos
        básicos do <strong>Docker</strong>, utilizando o <strong>Nginx</strong>
        para executar um servidor web dentro de um container.
    </p>

    <h2>📌 Sobre o projeto</h2>

    <p>
        O objetivo é criar e executar um container Docker com o Nginx,
        permitindo acessar uma página web através do navegador.
    </p>

    <h2>🛠️ Tecnologias utilizadas</h2>

    <ul>
        <li>🐳 Docker</li>
        <li>🌐 Nginx</li>
        <li>📄 HTML</li>
    </ul>

    <h2>🚀 Como executar</h2>

    <p>Clone o repositório:</p>

    <pre><code>git clone https://github.com/madolt109/projeto-docker.git</code></pre>

    <p>Entre na pasta do projeto:</p>

    <pre><code>cd projeto-docker</code></pre>

    <p>Crie a imagem Docker:</p>

    <pre><code>docker build -t meu-site .</code></pre>

    <p>Execute o container:</p>

    <pre><code>docker run -d -p 8080:80 meu-site</code></pre>

    <p>
        Depois, abra no navegador:
    </p>

    <p>
        <strong>http://localhost:8080</strong>
    </p>

    <h2>📚 O que foi aprendido</h2>

    <ul>
        <li>Criação de uma imagem Docker;</li>
        <li>Utilização de um Dockerfile;</li>
        <li>Criação e execução de containers;</li>
        <li>Mapeamento de portas com 8080:80;</li>
        <li>Utilização do Nginx dentro do Docker;</li>
        <li>Comandos básicos do Docker.</li>
    </ul>

    <h2>👨‍💻 Autor</h2>

    <p>
        <strong>Madolt109</strong>
    </p>

    <p>
        Projeto desenvolvido para fins de aprendizado durante as aulas de Docker.
    </p>

</body>
</html>
```
