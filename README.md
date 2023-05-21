# Comandos Git e GitHub Student

Este arquivo README tem o objetivo de fornecer uma visão geral dos principais comandos Git e também compartilhar informações sobre o programa "GitHub Student". Este conteúdo é destinado a estudantes de engenharia de software interessados em aprender sobre controle de versão e colaboração em projetos de desenvolvimento.

## Comandos Git Básicos

Os comandos Git básicos são essenciais para começar a usar o Git como ferramenta de controle de versão. Aqui estão alguns comandos comuns com exemplos:

- `git clone`: Clonar um repositório remoto para o seu ambiente local.
  Exemplo: `git clone https://github.com/seu-usuario/seu-repositorio.git`

- `git branch`: Criar e gerenciar branches para trabalhar em diferentes fluxos de desenvolvimento.
  Exemplo: `git branch implementacao-login`

- `git checkout`: Alternar entre diferentes branches ou versões do código.
  Exemplo: `git checkout implementacao-login`

- `git add`: Adicionar arquivos ou alterações específicas ao próximo commit.
  Exemplo: `git add index.html`

- `git pull`: Atualizar o repositório local com as alterações mais recentes do repositório remoto.
  Exemplo: `git pull origin implementacao-login`

- `git push`: Enviar suas alterações locais para o repositório remoto.
  Exemplo: `git push origin implementacao-login`

- `git fetch`: Buscar as alterações mais recentes do repositório remoto sem mesclá-las ao código local.
  Exemplo: `git fetch origin`

## Comandos Git Avançados

Além dos comandos básicos, existem comandos Git mais avançados que podem ser úteis durante o desenvolvimento de software. Aqui estão alguns exemplos:

- `git commit --amend`: Modificar o commit mais recente com novas alterações ou uma nova mensagem de commit.
  Exemplo: `git commit --amend -m "Mensagem corrigida!"`
 
- `git config`: Configurar variáveis de configuração do Git.
   Exemplo: `git config --global user.name "Seu Nome"` 
 
  **Adicionar configurações pra apenas um commit**
  - `git -c`: É possível setar configurações as configurações e realizar o commit em uma só linha (pra não ter que setar globalmente e correr o risco de alguém pegar a máquina e commitar no seu nome).
  - Exemplo: `git -c "user.name=Gabriel Silva" -c "user.email=silva@gmail.com" commit -m "Mensagem do commit"`

- `git remote`: Gerenciar repositórios remotos e suas configurações.
  Exemplo: `git remote add origin <URL-do-repositório-remoto>`, `git remote remove origin`, `git remote`
  
- `git reflog`: Exibir o histórico completo de referências, incluindo commits que não estão mais visíveis.
   Exemplo: `git reflog`

- `git log`: Exibir o histórico de commits com detalhes, incluindo autor, data e mensagem.
   Exemplo: `git log`
  
- `git revert`: Desfazer um commit específico, criando um novo commit que reverte as alterações.
   Exemplo: `git revert <hash-do-commit>`

- `git stash`: Armazenar temporariamente alterações não commitadas para trabalhar em outra tarefa.
  Exemplo: `git stash`, `git stash save "Nome do stash"`

  **Comandos relacionados ao git stash:**
  - `git stash list`: Exibir a lista de stashes disponíveis.
  - `git stash pop`: Aplicar e remover o stash mais recente da pilha.

  - `git stash apply`: Aplicar o stash mais recente sem removê-lo da pilha.

  - `git stash apply stash@{n}`: Aplicar um stash específico da pilha usando o índice n.
Exemplo: `git stash apply stash@{2}`

  - `git stash drop stash@{n}`: Remover um stash específico da pilha usando o índice n.
Exemplo: `git stash drop stash@{1}`

  - `git stash show stash@{n}`: Exibir as alterações contidas em um stash específico da pilha.
Exemplo: `git stash show stash@{0}`

- `git cherry-pick`: Aplicar um commit específico de uma branch para outra.
  Exemplo: `git cherry-pick <hash-do-commit>`, `git cherr-ypick -n 2475e9a`

  **Diferença entre git stash e git cherrypick:**
  - O comando `git stash` é usado para armazenar temporariamente alterações não commitadas, permitindo que você as recupere mais tarde.
  - O comando `git cherrypick` é usado para aplicar um commit específico de uma branch para outra.

- `git merge`: Combinar alterações de uma branch para outra.
   Exemplo: `git merge nome-da-branch`

- `git diff`: Exibir as diferenças entre commits, branches ou arquivos específicos.
   Exemplo: `git diff branch1 branch2`

- `git grep`: Pesquisar por uma determinada string nos arquivos do repositório.
   Exemplo: `git grep "palavra-chave"`
   
## Programa GitHub Student

O programa "GitHub Student" é uma iniciativa destinada a estudantes, que oferece benefícios especiais para auxiliar no desenvolvimento de projetos e colaboração no GitHub. Alguns dos benefícios incluem:
   
- Conta GitHub gratuita com recursos aprimorados.
- Acesso a ferramentas e recursos exclusivos para estudantes.
- Créditos em serviços de hospedagem e outros recursos úteis para projetos.
- Participação em programas de aprendizado e eventos da comunidade.

Para se inscrever no programa GitHub Student, acesse [education.github.com/students](https://education.github.com/students) e siga as instruções fornecidas.
