# Comandos Git e GitHub Student

Este arquivo README tem o objetivo de fornecer uma visão geral dos principais comandos Git e também compartilhar informações sobre o programa "GitHub Student". Este conteúdo é destinado a estudantes de engenharia de software interessados em aprender sobre controle de versão e colaboração em projetos de desenvolvimento.

## Comandos Git Básicos

Os comandos Git básicos são essenciais para começar a usar o Git como ferramenta de controle de versão. Aqui estão alguns comandos comuns com exemplos:

- `git clone`: Clonar um repositório remoto para o seu ambiente local.
  Exemplo: `git clone https://github.com/seu-usuario/seu-repositorio.git`

- `git branch`: Criar e gerenciar branches para trabalhar em diferentes fluxos de desenvolvimento.
  Exemplo: `git branch nome-da-branch`

- `git checkout`: Alternar entre diferentes branches ou versões do código.
  Exemplo: `git checkout nome-da-branch`

- `git add`: Adicionar arquivos ou alterações específicas ao próximo commit.
  Exemplo: `git add arquivo1.txt`

- `git pull`: Atualizar o repositório local com as alterações mais recentes do repositório remoto.
  Exemplo: `git pull origin nome-da-branch`

- `git push`: Enviar suas alterações locais para o repositório remoto.
  Exemplo: `git push origin nome-da-branch`

- `git fetch`: Buscar as alterações mais recentes do repositório remoto sem mesclá-las ao código local.
  Exemplo: `git fetch origin`

## Comandos Git Avançados

Além dos comandos básicos, existem comandos Git mais avançados que podem ser úteis durante o desenvolvimento de software. Aqui estão alguns exemplos:

- `git commit --amend`: Modificar o commit mais recente com novas alterações ou uma nova mensagem de commit.
  Exemplo: `git commit --amend`

- `git cherrypick`: Aplicar um commit específico de uma branch para outra.
  Exemplo: `git cherrypick <hash-do-commit>`

- `git remote`: Gerenciar repositórios remotos e suas configurações.
  Exemplo: `git remote add origin <URL-do-repositório-remoto>`

- `git stash`: Armazenar temporariamente alterações não commitadas para trabalhar em outra tarefa.
  Exemplo: `git stash save "Nome do stash"`

  **Comandos relacionados ao git stash:**
  - `git stash list`: Exibir a lista de stashes disponíveis.
  - `git stash pop`: Aplicar e remover o stash mais recente da pilha.
Exemplo: git stash pop

  - `git stash apply`: Aplicar o stash mais recente sem removê-lo da pilha.
Exemplo: `git stash apply`

  - `git stash apply stash@{n}`: Aplicar um stash específico da pilha usando o índice n.
Exemplo: git stash apply stash@{2}

  - `git stash drop stash@{n}`: Remover um stash específico da pilha usando o índice n.
Exemplo: `git stash drop stash@{1}`

  - `git stash branch nome-da-branch`: Criar uma nova branch e aplicar o stash mais recente nela.
Exemplo: `git stash branch nova-branch`

  - `git stash show stash@{n}`: Exibir as alterações contidas em um stash específico da pilha.
Exemplo: `git stash show stash@{0}`

  **Diferença entre git stash e git cherrypick:**
  - O comando `git stash` é usado para armazenar temporariamente alterações não commitadas, permitindo que você as recupere mais tarde.
  - O comando `git cherrypick` é usado para aplicar um commit específico de uma branch para outra.
