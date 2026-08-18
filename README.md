# comandos importantes git/github 

git init
- iniciar novo projeto com git

git add <nome-do-projeto> / .
- adiciona os arquivos que estao prontos para serem commitados

git commit -m "string"
- commit os arquivos para o historico

git log
- mostra os ultimos commits realizados

git status
- mostra o status da ramificacao 

git diff
- mostra o que foi alterado

git merge
- merge de ramificacoes, mescla ramificacoes

git branch
- mostra a branch ( arquivo principal) atual.

git branch -b
- cria uma nova branch a partir da branch atual que se esta inserido

git checkout <nome-da-branch>
- muda para a branch que deseja.

git remote add <nome> <url>
- sobe para um repositorio remoto ( nuvem )
- ex: github

git push <nome> <nome-da-branch>
- manda nossas alteracoes locais para o repositorio remoto,
- para cada branch

git pull <nome> <nome-da-branch>
- pega as alteracoes do repositorio remoto e para para a nossa maquina ( local )

git fetch
- atualiza o novo historico local de acordo com o historico salvo no repositorio