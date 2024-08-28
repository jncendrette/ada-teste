Exemplos de opções úteis:

git log --oneline: Exibe cada commit em uma linha com um resumo conciso (hash e mensagem).

git log --graph: Mostra um gráfico ASCII que representa a árvore de commits, ajudando a visualizar o histórico de ramificações e merges.

git log --author="Nome": Filtra os commits feitos por um autor específico.

git log --since="2023-01-01": Exibe commits feitos após uma data específica.

git reset: Use para desfazer commits e alterar o estado da área de trabalho e do índice.

git rebase -i: Use para modificar ou remover commits em um histórico.

git restore: Use para restaurar arquivos para um estado anterior.

git fetch

git diff branch

git branch -a 

git diff origin/main --name-status
============
A (Added): Indica que o arquivo foi adicionado no commit mais recente em comparação ao commit anterior. Ou seja, o arquivo foi criado e incluído no repositório em uma determinada revisão.

D (Deleted): Indica que o arquivo foi excluído no commit mais recente. Em comparação ao commit anterior, o arquivo foi removido do repositório.

M (Modified): Indica que o arquivo foi modificado no commit mais recente. Em comparação ao commit anterior, o arquivo sofreu alterações no seu conteúdo.
