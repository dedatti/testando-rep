# meu projeto

git init
- iniciar novo projeto com git

git add <nome do arquivo>/.
- add os arquivos estao prontos parar serem commitados

git commit -m "mensagem commit"
- commit os arquivos no historico

git log
- mostra os ultimos commit, log de alteracoes

git status
- como esta o estado das nossas ramificacoes

git diff
- que mostra como foi alterado
- o que tem de alteracao na ramificacao

git merge
- merge de ramificacoes, mescla ramificacoes

git branch
- mostra a branch atual

git checkout -b <nome-da-branch>
- cria uma nova branch a partir do historico da branch atual que estamos

git checkout <nome-branch>
- muda pra essa 

git remote add <nome> <url>
- add um novo repositorio remoto

git push <nome> <nome-da-branch>
- manda nossas alteracoes locais para o repositorio remoto, pra cada branch

git pull <nome> <nome-da-branch>
- pega as alteracoes do repositorio remoto e joga pra nossa maquina

git fetch
- atualiza o novo historico local de acordo com o historico salvo la no repositorio remoto
- sincronizacao do local com o remoto