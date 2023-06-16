# aula1-git-github
Este repositório é para fins de estudo do módulo git e github.
-Para criar pasta:
mkdir nome-da-pasta 

-Para acessar a pasta:
cd nome-da-pasta

-Para sair de uma pasta:
cd ..

-Para iniciar repositório:
git init	

-Para listar arquivos e pastas
ls

-Para criar um dentro da pasta
echo "#nome-da-pasta" >> arquivo.extensão

-Para adicionar conteudo(arquivo/pasta):
git add nome-do-arquivo-ou-pasta

-Para adicionar todos os arquivos/pastas:
git add .

-Para desfazer um add específico:
git reset nome-do-arquivo

-Para desfazer um add geral:
git reset

-Para visualizar o status:
git status

-Para abrir o "vs code":
code .

-Para retornar ao último commit, mantendo as alterações feitas nos arquivos:
git reset --soft HEAD~1

-Para retonar ao último commit, removendo as alterações feitas nos arquivos:
git reset --hard HEAD~1
