# como configurar o git

## niveis de configuração

**_system_** - todos os usuarios do computador // --system
**_global_** - todos os repositórios do usuário // --global
**_local_** - configurações do repositório atual // --local

## configurações básicas

**_usuario_** - user.name
**_email_** - user.email
**_configurar editor de texto_** - git config --global core.editor "(editor) --wait"
**_configurar o retorno de linha?_** - git config --global core.autocrlt input

**_renomear arquivos do staging via CLI_** - mv _arquivo novoNome_ (mover é renomear em unix)
**_remover pasta q foi commitada por engano_** - git rm --cached -r _nomePasta_
**_templates gitignore_** - github.com/github/gitignore

**_ver diferenças_** - git diff --staged
**_ver historico de commit_** - git log
**_ver historico de commit resumido_** - git log --oneline
**_commit mais novo no final da listagem_** - git log --reverse
**_ver conteudo de commit_** - git show  
**_ver listagem como árvore_** - git ls-tree

**_restaurar arquivo da area de staging_** - git restore --staged (nome)

**_restaurar commit_** - git restore --source HEAD~1 (nome do arquivo)
