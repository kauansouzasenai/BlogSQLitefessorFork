# Blog SESI Nova Odessa

Este é um projeto de blog desenvolvido com Node.js, utilizando o framework 
ExpressJS e banco de dados SQLite3. Ele permite o cadastro, login e listagem 
de usuários, com páginas renderizadas via EJS.

--------------------------------------------------------------------------------

## Tecnologias Utilizadas

- [Node.js](https://nodejs.org/)
- [ExpressJS](https://expressjs.com/)
- [SQLite3](https://www.sqlite.org/)
- [EJS](https://ejs.co/)
- [Body-Parser](https://github.com/expressjs/body-parser)
- [Express-Session](https://github.com/expressjs/session)

--------------------------------------------------------------------------------

## Instalação

1. Clone o repositório:

bash
git clone https://github.com/DenadaiSenai/BlogSQLite_tutorial_reiniciado
cd BlogSQLite_tutorial_reiniciado

2. Instale as dependências:

npm install

3. Execute o servidor:

nodemon app.js

--------------------------------------------------------------------------------

# Estrutura do projeto

- app.js                # Código principal da aplicação
- user.db               # Banco de dados SQLite
- /views                # Templates EJS para renderização das páginas
- /pages            # Páginas principais (index, login, cadastro, etc)
- /partials         # Componentes parciais (ex: tabela de usuários)
- /static               # Arquivos estáticos (CSS, imagens, JS)

--------------------------------------------------------------------------------

# Funcionalidades 

 Login com sessão
 Cadastro de usuários
 Listagem de usuários
 Validação de duplicidade no cadastro (usuário já existente)
 Sistema de sessões com autenticação
 Renderização de páginas com EJS
 Página de erro 404 customizada

--------------------------------------------------------------------------------

# Funcionalidades a serem implementadas

1. Criação e gerenciamento de posts/artigos
 Criar um novo post (formulário + rota POST)
 Salvar post no banco de dados (tabela posts)
 Listar posts na página principal
 Visualizar post completo em uma página dedicada
 Editar e deletar posts (CRUD completo)

2. Modelo de dados para posts
 Criar a tabela posts no banco de dados com campos como:
    id, titulo, conteudo, autor, data_criacao, etc.

3. Comentários em posts
 Adicionar comentários por usuários autenticados
 Relacionar comentários com posts no banco

4. Sistema de categorias ou tags
 Associar posts a categorias ou tags para organização

5. Painel administrativo
 Página para administradores gerenciarem usuários e posts
 Sistema de permissões (ex: autor vs. admin)

6. Editor de texto rico (opcional)
 WYSIWYG (Abreviação de "What You See Is What You Get" 
 (O que você vê é o que você obtém) e refere-se a editores 
 que exibem o conteúdo da forma como será impresso ou apresentado, 
 permitindo uma edição visual e intuitiva.) para criar posts com formatação

7. Melhorias de segurança
 Hash de senhas (ex: bcrypt)
 Criptografia de dados do dashboard
 Proteção contra XSS e CSRF

--------------------------------------------------------------------------------

# Ambiente de execução e teste

Linux Ubuntu 24.04 LTS
- Requisições Mínimas:
- 4gb RAM
- Conexão com Internet
- 356gb de armazenamento

--------------------------------------------------------------------------------

## Autores:
Otávio
David
Kauan
Victor

Estudantes do Curso Desenvolvimento de Sistemas
SENAI 'Celso Charuri' - Sumaré  
