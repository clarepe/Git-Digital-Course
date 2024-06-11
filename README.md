# Curso Digital: Git.

## Comandos git

~~~bash
git init # Inicializa um repositório git.
git add <nome do arquivo> # Adiciona um arquivo ao stage.
git add . # Adiciona todos os arquivos modificados ao stage.
git commit -m "mensagem do commit" # Cria um commit com a mensagem.
git log # Mostra o histórico de commits.
git branch <nome da branch> # Cria uma nova branch.
git checkout <nome da branch> # Troca para uma branch.
git merge <nome da branch> # Mescla as alterações de uma branch com a atual.
git remote add origin <url do repositório> # Adiciona um repositório rem
git restore # Remove a ultima alteração
git restore --staged <o nome do arquivo> # O arquivo sai da area de staged e volta do add e retorna para area de edição 
git reset --hard # Remove todas as alterações
git pull: #Busca as últimas alterações do repositório remoto e as mescla com o seu repositório local.
git fetch: # Baixa as últimas alterações do repositório remoto, mas não as mescla com o seu repositório local.
git rebase: # Reapplica commits em cima de uma branch base, reescrevendo o histórico do repositório.
git tag: # Cria, lista, exclui e verifica tags em commits específicos.
** Configuração:
git config: # Configura variáveis ​​globais e locais para personalizar o comportamento do Git.
** Utilitários:
git help: # Mostra ajuda para comandos Git específicos ou para o Git em geral.
git diff: # Mostra as diferenças entre arquivos modificados ou entre commits.
** Diferenças entre git diff e git diff --staged:
git diff: # Mostra as diferenças entre o seu diretório de trabalho e o índice (staging area) ou entre o índice e o último commit.
git diff --staged: # Foca apenas nas diferenças entre os arquivos preparados para commit no índice e a versão mais recente no índice.
** Cenários de uso para git diff --staged:
** Revisar alterações antes de commitar: #É útil para revisar as alterações que você já adicionou à área de preparo e garantir que tudo esteja correto antes de finalizar o commit.
** Depurar problemas de merge: #Se você estiver tendo problemas ao mesclar branches, o git diff --staged pode te ajudar a identificar quais arquivos estão causando o conflito.
** Verificar o status de arquivos específicos: # Você pode usar o comando junto com o nome de um arquivo para ver as alterações específicas que foram preparadas para commit naquele arquivo.

git show: # Exibe informações detalhadas sobre um commit específico.
git clean: # Remove arquivos não rastreados do diretório de trabalho.
git ls-remote: # Lista as branches e tags remotas em um repositório remoto.
git archive: # Cria um arquivo compactado de um commit ou branch específica.
** Ferramentas Avançadas:

git bisect: # Encontra o commit que introduziu um bug específico.
git revert: # Reverte um commit específico do histórico do repositório.
git cherry-pick: # Aplica as alterações de um commit específico em outra branch.
git submodule: # Gerencia submódulos, que são repositórios Git aninhados dentro de outro repositório.
~~~