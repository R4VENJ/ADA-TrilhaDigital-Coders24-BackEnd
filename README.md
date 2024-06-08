# Curso Digital: Git/Versionamento

## Gravando mudanças no repositório
## Salvando modificações no Git


*Mudança pelo VSCode
*Mudança pelo site

Avançar de Unmodified to Modified 
Editar Arquivo e Salvar
Retroceder de Modified to Unmodified
> git restore .\README.md
	Visualizar diferenças
		> git diff

Avançar de Modified to Staged
> git add .\README.md
Retroceder de Staged to Modified
> git restore –staged .\README.md
	Visualizar diferenças
		> git diff –staged

Avançar de Staged to Unmodified
> git commit -m "add new title"

Avançar para Committed
> commit -m "add new text" 
Log de Commits
	> git log
Publicar no GitHub
Verificar Remotes
> git remote
Subir
	> git push origin main
Baixar
	> git pull origin main
