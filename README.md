# Lista de tarefas

Um pequeno aplicativo de lista de tarefas feito com HTML, CSS e JavaScript puro.  
O objetivo deste projeto é praticar Git e GitHub: iniciar um repositório, fazer commits, criar branches e enviar o projeto para o GitHub.

## Funcionalidades

- Adicionar uma tarefa
- Marcar uma tarefa como concluída
- Excluir uma tarefa
- Salvar tarefas no navegador usando `localStorage`

## Como executar

1. Baixe ou clone este projeto.
2. Abra a pasta no VS Code.
3. Abra o arquivo `index.html` no navegador.

Não é necessário instalar dependências.

## Estrutura de pastas

```text
pratica-git-do-zero/
├── README.md
├── .gitignore
├── index.html
├── assets/
│   └── favicon.svg
└── src/
    ├── css/
    │   └── styles.css
    └── js/
        └── app.js
```

## Prática sugerida com Git

Siga esta sequência para treinar:

1. `git init` — iniciar o repositório local.
2. `git status` — conferir os arquivos.
3. `git add .` — preparar os arquivos.
4. `git commit -m "chore: estrutura inicial do projeto"` — criar o primeiro commit.
5. Crie um repositório vazio no GitHub.
6. `git remote add origin URL_DO_SEU_REPOSITORIO` — cadastrar o repositório remoto.
7. `git branch -M main` — renomear a branch atual para `main`.
8. `git push -u origin main` — enviar o projeto e configurar o rastreamento.

Depois, pratique uma alteração:

```bash
git checkout -b feature/mensagem-boas-vindas
```

Edite algum texto do aplicativo e rode:

```bash
git status
git add .
git commit -m "feat: adiciona mensagem de boas-vindas"
git push -u origin feature/mensagem-boas-vindas
```

No GitHub, abra um Pull Request para juntar a branch à `main`.

## Ideias para evoluir

- Adicionar filtro: todas, pendentes e concluídas.
- Permitir editar uma tarefa.
- Mostrar quantas tarefas ainda estão pendentes.
- Adicionar confirmação antes de excluir.
