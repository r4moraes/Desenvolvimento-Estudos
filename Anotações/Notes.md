# Anotações importantes
Composição objeto git

- Blobs: Como metadados, bloco hash de comparação
- Trees: Armazena blobs e commits, bem como faz o apontamento para as blobs em questão.
- Commits: Aponta para a tree, parent, autor, mesagem e timestamp de quando ocorreu.

#### Fluxo principal:

Untracked, unmodified/modified, staged.

Principais comandos do git:

#### Inicializar repositório: git init

#### Adicionar para área de staged: git add (file or *)

#### Realizar alterações: git commit -m "mensagem"

#### Verificar status atual: git status

#### Vincular repositórios remoto ao local: git remote add origin url

#### Visualizar repositórios cadastrados: git remote -v

#### Atualizar repositório remoto: git push origin master

#### Atualizar repositório local: git pull origin master

#### Clonar repositório remoto: git clone url









