# 🐳 Projeto Docker - Nginx

Este projeto foi desenvolvido durante a aula para aprender os conceitos básicos do **Docker**, utilizando o **Nginx** para executar um servidor web dentro de um container.

## 📌 Sobre o projeto

O objetivo é criar e executar um container Docker com o Nginx, permitindo acessar uma página web através do navegador.

## 🛠️ Tecnologias utilizadas

* 🐳 Docker
* 🌐 Nginx
* 📄 HTML

## 🚀 Como executar

Primeiro, faça o clone do repositório:

```bash
git clone https://github.com/madolt109/projeto-docker.git
```

Entre na pasta do projeto:

```bash
cd projeto-docker
```

Crie a imagem Docker:

```bash
docker build -t meu-site .
```

Execute o container:

```bash
docker run -d -p 8080:80 meu-site
```

Depois, acesse no navegador:

```text
http://localhost:8080
```

## 📚 O que foi aprendido

Neste projeto foram praticados:

* Criação de uma imagem Docker;
* Utilização de um `Dockerfile`;
* Criação e execução de containers;
* Mapeamento de portas com `8080:80`;
* Utilização do Nginx dentro do Docker;
* Comandos básicos do Docker.

## 👨‍💻 Autor

**Madolt109**

Projeto desenvolvido para fins de aprendizado durante as aulas de Docker.
