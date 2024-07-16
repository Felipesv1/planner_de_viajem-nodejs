<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=0:83a4d4,100:005bea&height=120&section=header"/>

# Planner de Viajens

Um aplicativo de planejamento de viagens desenvolvido com Node.js, Express e Prisma.

## Índice

- [Sobre o Projeto](#sobre-o-projeto)
- [Funcionalidades](#funcionalidades)
- [Tecnologias Utilizadas](#tecnologias-utilizadas)
- [Instalação](#instalação)
- [Como Usar](#como-usar)
- [Contribuição](#contribuição)
- [Licença](#licença)
- [Contato](#contato)

## Sobre o Projeto

Este projeto é um aplicativo web para planejar viagens, onde os usuários podem criar, editar e excluir planos de viagem. O objetivo é fornecer uma ferramenta simples e intuitiva para organizar viagens e compartilhar itinerários.

## Funcionalidades

- Cadastro de usuários
- Login/Logout
- Criação de planos de viagem
- Edição de planos de viagem
- Exclusão de planos de viagem
- Visualização dos planos de viagem

## Tecnologias Utilizadas

- Node.js
- Express
- Prisma
- PostgreSQL
- TypeScript

## Instalação

1. Clone o repositório:
    ```bash
    git clone https://github.com/Felipesv1/planner_de_viajens-nodejs.git
    ```

2. Navegue até o diretório do projeto:
    ```bash
    cd planner_de_viajens-nodejs
    ```

3. Instale as dependências:
    ```bash
    npm install
    ```

4. Crie um arquivo `.env` e configure as variáveis de ambiente necessárias:
    ```env
    DATABASE_URL=postgresql://user:password@localhost:5432/mydatabase
    ```

5. Execute as migrações do Prisma:
    ```bash
    npx prisma migrate dev
    ```

6. Inicie o servidor:
    ```bash
    npm start
    ```

7. Abra o navegador e acesse `http://localhost:3000`.

## Como Usar

1. Registre-se no aplicativo.
2. Faça login com suas credenciais.
3. Crie um novo plano de viagem.
4. Adicione detalhes à sua viagem, como destinos, datas e atividades.
5. Edite ou exclua planos conforme necessário.
6. Visualize todos os seus planos de viagem em um só lugar.

## Contribuição

Contribuições são bem-vindas! Se você tiver sugestões de melhorias ou encontrar algum bug, por favor, abra uma issue ou envie um pull request.

## Licença

Este projeto está licenciado sob a Licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

## Contato

Felipe - [Seu LinkedIn](https://www.linkedin.com/in/seu-perfil) - seu-email

