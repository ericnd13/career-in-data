# 1. git init
## O que faz?
- transforma uma pasta comum em um repositório.
## Quando usar?
- quanto se começa um projeto do zero, primeiro comando a ser usado.
## Exemplo
- na pasta MeuProjeto/, usar git init, cria a pasta .git que guarda o histórico do projeto.

# 2. git status
## O que faz?
- mostra o estado atual do repositório.
## Quando usar?
- a todo momento. com ele é capaz de visualizar o que mudou, o que ainda não foi salvo, e o que está pronto para commit.
## Exemplo
- ao usar git status, mostra modified: comandos.md. significa que eu alterei o arquivo, mas ainda não salvou no git.

# 3. git add
## O que faz?
- coloca arquivos na área de preparação ( staging area )
## Quando usar?
- ao querer incluir uma alteração no próximo commit
## Exemplo
- adiciona um arquivo: git add  comandos.md ( nome arquivo ).
- adiciona tudo: git add .