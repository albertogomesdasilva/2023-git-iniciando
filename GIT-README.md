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

<<<<<<< HEAD
git branch <nome-da-nova-branch>: Substitua <nome-da-nova-branch> pelo nome que deseja dar à nova branch.
=======
git branch <nome-da-nova-branch>


git branch: Lista todas as branches existentes no repositório.

git checkout <branch>: Alterna para a branch especificada.

git merge <branch>: Combina a branch especificada com a branch atual.

git remote add <nome> <URL>: Adiciona um novo repositório remoto com o nome especificado.

git remote -v: Lista os repositórios remotos vinculados ao repositório local.

git log: Mostra um registro de todos os commits realizados no repositório.

git diff: Exibe as diferenças entre o estado atual do repositório e o commit anterior.

echo Olá, mundo! > exemplo.txt

notepad exemplo.txt

# 
git checkout <commit> <arquivo>: Este comando permite que você recupere a versão de um arquivo específico de um commit anterior, sem alterar o estado do seu branch atual. Substitua <commit> pelo identificador do commit desejado e <arquivo> pelo nome do arquivo que você deseja restaurar. Por exemplo:

Copy code
git checkout abc123 file.txt
Isso substituirá o conteúdo do arquivo "file.txt" pelo estado no commit com o identificador "abc123". Tenha em mente que as alterações não serão refletidas em commits futuros.

git reset <commit>: Este comando permite redefinir o estado do seu branch para um commit anterior, removendo os commits subsequentes. Substitua <commit> pelo identificador do commit desejado. Existem duas opções principais:

git reset --hard <commit>: Redefine completamente o branch para o commit especificado, descartando todas as alterações posteriores. Tenha cuidado ao usar este comando, pois ele descarta permanentemente as alterações não salvas.

git reset --soft <commit>: Redefine o branch para o commit especificado, mas mantém as alterações não confirmadas no seu diretório de trabalho e no índice do Git. Isso permite que você ajuste o commit antes de confirmar novamente.

git remote -v
Isso exibirá a lista de repositórios remotos, juntamente com suas URLs.

Identifique o repositório remoto que deseja desconectar. Geralmente, ele tem um nome como "origin".

Execute o comando git remote remove seguido do nome do repositório remoto. Por exemplo, se o repositório remoto for chamado "origin", execute o seguinte comando:

arduino
Copy code
git remote remove origin
Isso remove a referência ao repositório remoto do seu repositório local.

Após executar esse comando, seu repositório local não estará mais vinculado ao repositório remoto específico. Observe que isso não afeta as informações ou histórico do seu repositório local, apenas remove a conexão com o repositório remoto.






Por exemplo:

css
Copy code
git reset --hard abc123
Isso redefine o branch atual para o commit com o identificador "abc123" e descarta todas as alterações e commits posteriores.


* É importante destacar que, ao redefinir o branch para um commit anterior, você está reescrevendo o histórico do Git. Portanto, tenha cuidado ao usar esses comandos, especialmente quando estiver trabalhando em um repositório compartilhado com outras pessoas.
