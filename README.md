Guia para Iniciantes em Git e GitHub

Este guia básico tem como objetivo oferecer uma introdução aos comandos essenciais do Git e GitHub para iniciantes.

Iniciando com Git
Inicializando um repositório:

Vá para o diretório local onde deseja salvar o repositório.
Utilize git clone "path of clone(repository path)" para clonar um repositório existente ou git init para iniciar um novo projeto e começar a rastrear alterações.
Gerenciando Alterações:

Após realizar alterações no projeto, utilize git status e git diff para visualizar as modificações.
Adicione as alterações utilizando git add "file" para prepará-las para o commit.
Commit das Alterações:

Faça um snapshot das alterações usando git commit -m "mensagem descritiva" para iniciar um novo rastreamento das modificações.
Histórico e Visualização:

Utilize git log para visualizar o histórico de commits e suas informações.
Desfazendo Alterações:

Para desfazer uma alteração, utilize git restore "filename" ou git reset HEAD "filename" para restaurar para uma versão anterior.
Gerenciando Branches:

Crie um novo branch com git branch nome-novo-branch e mude para ele usando git checkout nome-novo-branch.
Para mesclar branches, retorne ao branch principal (git checkout master) e faça a mesclagem usando git merge nome-novo-branch.
Atualizando e Compartilhando o Código:

Antes de enviar suas alterações para o repositório remoto, utilize git fetch e git diff para visualizar as mudanças.
Finalmente, use git pull para mesclar as alterações e git push origin master para enviar suas alterações para o repositório remoto.
Comandos Git Comuns
git add nomedoarquivo.extensão: Adiciona o arquivo especificado.
git status: Exibe o status dos arquivos.
git diff: Mostra as mudanças nos arquivos.
git commit -m "mensagem": Realiza um commit com uma mensagem descritiva.
git log: Visualiza o histórico de commits.
git restore nomedoarquivo.extensão: Restaura um arquivo para uma versão anterior.
git reset HEAD nomedoarquivo.extensão: Volta o arquivo para o estado anterior.
git rm nomedoarquivo.extensão: Remove o arquivo do rastreamento.
git branch: Lista os branches e mostra o branch atual.
git checkout nome-do-branch: Altera para o branch especificado.
git stash: Arquiva temporariamente as alterações.
git remote -v: Mostra os repositórios remotos configurados.
Para mais informações, consulte a documentação oficial do Git.

Este guia oferece uma introdução básica aos principais comandos do Git e GitHub para iniciantes. À medida que você ganha mais experiência, explore recursos avançados e práticas recomendadas para melhorar sua habilidade com controle de versão e colaboração em projetos de software.
