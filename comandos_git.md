
# Curso de Git Hora de Codar Comandos
=============================================================================
## Comandos básico do git
=============================================================================


git init  => Adiciona o projeto ao git.

git status => Exibe o status do repo que estamos trabalhando.

git add <nome do arquivo> => adiciona arquivo para ser comitado

git add . => adiciona vários arquivos na area de Stage.

git commit => Faz commmit do arquivo

git commit -a -m => Para comitar todos arquivos no stage.

git push => Empurra os arquivos para o server git

git pull => Busca atualização no repo

git clone + caminho do repo => Clona repo para sua máquina

git rm => remove arquivo do repo

git mv => pode renomear ou mover um arquivo no git

git checkout => volta o arquivo para o estado original.

.gitignore => Este arquivo serve para ignorar o que não será monitorado no git.

git reset --hard + origin/main => Reseta as configurações para as mesmas definiçoes do server.

=============================================================================
## Trabalhando com Branch
=============================================================================


git branch => Comnado para verificar quantos branch temos e onde estamos trabalhando.

git branch + nome_branch => cria um novo branch

git branch -d ou --delete => deleta um branch criado

git checkout + <nome_branch> => comando para mudar de Branch

git checkout -b + <nome_branch> => cria um novo branch e muda para ele.

git merge <nome_branch> => faz união dos branch

git stash => Comando utilizado para fazer rollback para estado inicial do projeto, porém é possivel recuperar caso seja necessároio o que foi feito. 

git stash list => lista todas as stash feita até o momento

git stash apply < Numero da Stash> => recupera a stash enviada para a lixeira.

 git stash show -p < Numero da Stash> => Mostra quais alterações foram feitas.

 git stash clear => Limpa todas as stash

 git stash drop < Numero da Stash> => Exclui a stash selecionada apenas.

 git tag -a <Nome da Tag> -m <Mensagem enviada > => Cria um marco durante o desenvolvimento.

 git show < nome da tag> => Mostra toda atualização feita quando foi salva a tag

 git checkout < nome da tag > => Usado para trocar de tag

=============================================================================
## Compartilhamento e atualização de Repo
=============================================================================


git 

=============================================================================
## Analise e inspeção de Repo
=============================================================================


git show => Examinar objetos em um repositório Git e historico de commits.

git diff => Mostra a diferença entre arquivos do git.

git shortlog => Mostra um historico de commits do que foi feito no projeto.


=============================================================================
## Admistração de repositório
=============================================================================


git clean => limpa todos arquivos que estão untracked

git gc => Limpa arquivos que não são necessário para nosso projeto através do garbage collector.

git fsck => Verifica a integridade de arquivos e a sua conectividade do repo.

git reflog => Mapea todos seus passos no repo.

git archive --format zip --output main_files.zip main => comando para tranformar o repo em um arquivo .zip


=============================================================================
## Melhorando os commits do projeto
=============================================================================

