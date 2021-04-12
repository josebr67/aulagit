# GIT e GITHUB

Guia prático para iniciantes.

## Instalação

https://git-scm.com/download

#SCENES

Inicio: no terminal digitar git init

-[] Você deseja criar pontos na história da produção do seu projeto.
    git add 
    git commit -m "descrição do commit"

-[] Você deseja verificar mudanças feitas no seu projeto
    git log - mostra as mudanças nos arquivos
    git status - mostra o estado dos arquivos


[] Você começa nova funcionalidade no seu projeto, sem estragar o que já foi feito.
    git branch (nome da nova branch) exemplo feature/cart
    git checkout feature/cart para mudar para a nova branch
    git checkout navega entre as branchs

[] Você adiciona as novas funcionalidades ao seu projeto em produção

    git merge feature/cart (junta a brancha branch principal)

[] Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

    git branch -D feature/cart

[] Você quer colocar seu projeto na nuvem

    criar repositório no GITHUB
    copiar o link do repositório e executar o comando : git remote add origin https://github.com/josexxx/aulagit.git
    Na primeira vez que estiver subindo os dados para nuvem: git push -u origin master, após apenas git push.


Resumo:
- git init // inicia a linha do tempo
- git add // adiciona ou atualiza mudanças para irem para a linha do tempo
- git commit // adiciona um ponto na linha do tempo
- git log // visualiza os ppontos na linha do tempo
- git status // informa o estado das alterações do nosso projeto
- git show // apresenta determinado ponto no tempo.

