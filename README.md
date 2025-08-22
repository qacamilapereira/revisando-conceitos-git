Revisando conceitos de Git e Github - Anotações Vídeo Youtube de Fernanda Kipper
Comandos no Git
git init
- iniciar novo projeto com git;

git add <nome-do-arquivo>
git add .
- adiciona os arquivos que estão prontos para serem commitados;

git commit -m "mensagem de commit"
- commita os arquivos no histórico (efetiva as alterações que foram realizadas);

git log
- mostra os último commits, log de alterações;

git status
- mostra como está o estado da nossa ramificação, se tem alterações para serem commitadas,
  se tem alterações que já foram preparadas para serem commitadas, mas ainda não foram;

git diff
- mostra o que foi alterado, na ramificação atual;

git merge
- faz merge de ramificações, ou seja, mescla as ramificações;

git branch
- mostra a branch atual;

git branch -b <nome-da-branch-a-ser-criada>
- cria uma nova branch a partir do histórico da branch atual que estamos;

git checkout <nome-da-branch>
- muda para essa branch (vai para esse branch indicada)

git checkout -b <nome-da-branch>
- criar uma nova branch a partir da branch atual que estamos

git remote add <nome-do-remote> <URL>
- adiciona um novo repositório remoto

git push <nome> <nome-da-branch>
- manda as nossas alterações locais para o repositório remoto, para cada branch;

git pull <nome> <nome-da-branch>
- pega as alterações do repositorio remoto e salva na pasta do projeto,
  ele atualiza a branch de acordo com as alterações feitas e enviadas ao repositório remoto.

git fetch
- atualiza o novo histórico local de acordo com  o histórico salvo no repositório remoto.
  Para atualizar todas as novas branches que foram criadas.
- faz uma sincronização do local com o remoto.
