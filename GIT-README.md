Principais comandos do GIT:

* echo "# 2023-git-iniciando" >> README.md
* git init
* git add README.md
* git commit -m "first commit"
* git branch -M main
* git remote add origin https://github.com/albertogomesdasilva/2023-git-iniciando.git
* git push -u origin main

git --help

git init: Inicializa um novo repositório Git em um diretório.

git clone <URL>: Cria uma cópia local de um repositório remoto existente.

git add <arquivo>: Adiciona um arquivo ao índice do Git para ser monitorado.

git commit -m "mensagem do commit": Cria um novo commit com as alterações realizadas, juntamente com uma mensagem explicativa.

git status: Exibe o estado atual do repositório, mostrando quais arquivos foram modificados, adicionados ou removidos.

git pull: Atualiza o repositório local com as alterações mais recentes do repositório remoto.

git push: Envia os commits locais para o repositório remoto.

git branch <nome-da-nova-branch>

git branch: Lista todas as branches existentes no repositório.

git checkout <branch>: Alterna para a branch especificada.

git merge <branch>: Combina a branch especificada com a branch atual.

git remote add <nome> <URL>: Adiciona um novo repositório remoto com o nome especificado.

git remote -v: Lista os repositórios remotos vinculados ao repositório local.

git log: Mostra um registro de todos os commits realizados no repositório.

git diff: Exibe as diferenças entre o estado atual do repositório e o commit anterior.