<p align="center">
  <a href="https://aluiziodeveloper.com.br/">
    <img alt="Conex Networks" src="https://aluiziodeveloper.com.br/assets/img/icon.png" width="200" />
  </a>
</p>
<h2 align="center">
Cursos, mini-cursos, dicas, tutoriais e muito mais.
</h2>

## Curso: API Restful Javascript com Node.js, Typescript, TypeORM etc

Seja muito bem-vindo e bem-vinda ao curso: **API Restful Javascript com Node.js, Typescript, TypeORM etc**, aqui você desenvolverá um exemplo de uma API de vendas, com os módulos de produtos, usuários, clientes e pedidos de compras, além vários outros recursos, incluindo o uso do TypeORM, upload de arquivos, autenticação com JWT, sistema de cache com o Redis, e muito mais.

Você precisará do Docker instalado em seu ambiente de desenvolvimento para rodar Postgres e Redis.

Este repositório contém o código inicial do projeto que será desenvolvido durante o curso. A ideia é ganhar tempo já trazendo todas as configurações iniciais prontas e focar naquilo que é mais importante, que é a implementação da API de fato.

### Instalando o projeto no seu PC

Instale o projeto em seu ambiente de desenvolvimento seguindo as etapas a seguir.

> NOTA: caso o seu PC esteja com Windows, recomendo trabalhar com um WSL Ubuntu. Acesse o link https://www.aluiziodeveloper.com.br/ambiente-de-desenvolvimento-no-windows-10-11-com-wsl/ para mais informações.

1. No Shell, clonar o repositório do projeto em seu PC.

```shell
git clone https://github.com/conexnetworks/apivendas2024-course-start-code.git api-vendas-2024
```

2. No Shell, acessar a pasta do projeto e instalar as dependências com o `Npm`.

```shell
cd api-vendas-2024

npm ci
```

3. No Shell, executar o comando `code .` para abrir o Visual Studio Code com o projeto carregado.

4. Criar o arquivo de variaveis de ambiente `.env` na pasta raiz do projeto, incluindo o conteúdo a seguir:

```shell
# Application
PORT=3333
API_URL=http://localhost:3333
```

### Executando o projeto em seu PC

O projeto inicial contém apenas o arquivo `server.ts` com o um `console.log`. Executar o servidor e observar a mensagem `Olá Dev!` na console do shell:

```shell
npm run dev
```

**Partiu curso!**


## Redes Sociais

[Site Conex Networks](https://conexnetworks.com.br)

[Blog Aluizio Developer](https://aluiziodeveloper.com.br)

[Perfil Udemy](https://www.udemy.com/user/jorge-aluizio-alves-de-souza/)

[Cursos Gratuitos](https://letsgoahead.com.br/)

[YouTube](https://www.youtube.com/jorgealuizio)

[Instagram](https://www.instagram.com/conexnetworks.dev/)

[Servidor no Discord](https://discord.gg/3J87BMz5fD)

[LinkedIn](https://www.linkedin.com/in/jorgealuizio/)
