# Objetivos

- Aplicar os conceitos de controle de versão utilizando o Git.
- Simular o processo de planejamento e execução de um release de software.
- Praticar o uso de branches, commits, pull requests, tags e releases.

## Descrição da Atividade

Os grupos deverão simular o desenvolvimento de uma miniaplicação web, com funcionalidades previamente definidas, utilizando um repositório Git hospedado no GitHub.

## Aplicação

A aplicação WEB simulada é bem simples. Foi construída com HTML e JavaScript sem recursos de CSS ou preocupação com design. A funcionalidade completa tem 4 páginas HTML:

- Página de login (`index.html`)
- Página de mensagem de erro (`msg.html`)
- Página de administrador (`pg001.html`)
- Página de operador (`pg002.html`)

## Etapas

### 1. Criar uma conta no GitHub (caso não tenha)
### 2. Criar um repositório (nome a critério do grupo).
### 3. Criar um arquivo `README.md`, colocando o nome dos integrantes do grupo e o propósito do projeto, incluindo o plano de releases previsto.

## Plano de Releases

### 5.1 Primeiro Release
- Tela de login construída, ao clicar no botão envia mensagem “em construção”.
- **Páginas**:
  - `index.html` (Página de login)
  - `working.html` (Página de aviso)

### 5.2 Segundo Release
- Página de login chamando a página do administrador sem validar se os campos login e senha foram preenchidos.
- **Páginas**:
  - `index.html` (Página de login sem consistência)
  - `pg001.html` (Página inicial para usuário administrador)

### 5.3 Terceiro Release
- Funcionamento completo: se deixar o campo usuário em branco (só valida este campo), mostra página de erro. Ao digitar “admin”, exibe a tela do administrador; qualquer outro conteúdo no campo de usuário mostra a página do operador.
- **Páginas**:
  - `index.html` (Página de login com consistência)
  - `pg001.html` (Página inicial para usuário administrador)
  - `pg002.html` (Página inicial para usuário operador)
  - `msg.html` (Página de mensagem de erro)

## Branches

Utilizar o controle de versão com ramificações (branches), incluindo ao menos:

- `main` ou `master`
- `develop`
- Branches de funcionalidade (exemplo: `versao1`, `release1`, `loginsenha`, `madalena`, etc.)
- Branches de correção (exemplo: `ajustev1`, `correcoes`, etc.)

Realizar **pull requests** simulando revisão de código, com pelo menos um comentário por parte de outro membro do grupo.

Criar **tags** no repositório para marcar os releases.

Gerar um arquivo `changelog` para a versão `v1.0`.

## Entrega

- Coletar **prints** do processo e incluir em um documento (Word ou PDF).
- O documento deverá ser entregue pelo Moodle com o link do repositório logo no primeiro parágrafo.
