# Turtorial-container-docker
Turtorial simples para ajudar a rodar a sua primeira aplicação de JS em um contêiner, embora não se aprofunde muito, aborda temas como comandos container, docker, dockerfile.

<img src="http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge"/>
</p>

## Aplicação em JS 

 * Cronometro com Javascript.
 
## Conhecimentos Básicos

* [Comandos Docker- Comandos básicos ](https://stack.desenvolvedor.expert/appendix/docker/comandos.html)
* [Dockerfile - Principais comandos](https://blog.rocketseat.com.br/dockerfile-principais-comandos-para-criar-a-receita-da-imagem/)
* [Introdução ao Visual Studio Code](https://www.devmedia.com.br/introducao-ao-visual-studio-code/34418)
* [O Que é HTML? Guia Básico Para Iniciantes](https://www.hostinger.com.br/tutoriais/o-que-e-html-conceitos-basicos)
* [Os 6 principais comandos git](https://www.digitalhouse.com/br/blog/principais-comandos-git/#acesso-ao-projeto)

## ✔️ Técnicas e tecnologias utilizadas

- ``Docker``
- ``Visual Studio Code``
- ``arquivo de configuração dockerfile``
- ``Git``

## Clonando o repositório

```markdown
git clone https://github.com/taysa-barbosa/Turtorial-Docker-container.git
```
## Fazendo o Build da image

```markdown
Docker build -t nome-da-imagem .
```
##  Criando e configurando o container 

```markdown
docker run -p 4200:80 -d nome-da-imagem
```
## Testando o localhost da aplicação

```markdown
localhost:http://0.0.0.0:4200/test/
```
## Fazendo login no github e criando uma tag 

```markdown
docker login
```
```markdown
docker tag nginx:latest nomedousuario/nomedocontainer
```
```markdown
docker pull nomedousuario/nomedocontainer
```
