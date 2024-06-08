# Curso Digital: Git/Versionamento

## Gravando mudanças no repositório
## Salvando modificações no Git
*Mudança pelo VSCode <br />
*Mudança pelo site

Avançar de Unmodified to Modified 
> Editar Arquivo e Salvar

Retroceder de Modified to Unmodified
> git restore .\README.md

Visualizar diferenças
> git diff

<br />

Avançar de Modified to Staged
> git add .\README.md

Retroceder de Staged to Modified
> git restore –staged .\README.md

Visualizar diferenças
> git diff –staged

<br />

Avançar de Staged to Unmodified
> git commit -m "add new title"

Avançar para Committed
> commit -m "add new text"

Log de Commits
> git log

<br />

Publicar no GitHub <br />
Verificar Remotes
> git remote

Subir
> git push origin main

Baixar
> git pull origin main

Fetch
> git fetch
> git diff origin/main
