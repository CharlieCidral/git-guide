# Guia para Iniciantes em Git e GitHub

Este guia básico tem como objetivo oferecer uma introdução aos comandos essenciais do Git e GitHub para iniciantes.

## Iniciando com Git

#### 1. Inicializando um repositório:

- Vá para o diretório local onde deseja salvar o repositório.
- Utilize git clone "path of clone(repository path)" para clonar um repositório existente ou git init para iniciar um novo projeto e começar a rastrear alterações.

#### 2. Gerenciando Alterações:

- Após realizar alterações no projeto, utilize git status e git diff para visualizar as modificações.
- Adicione as alterações utilizando git add "file" para prepará-las para o commit.

#### 3. Commit das Alterações:

- Faça um snapshot das alterações usando git commit -m "mensagem descritiva" para iniciar um novo rastreamento das modificações.

#### 4.Histórico e Visualização:

- Utilize git log para visualizar o histórico de commits e suas informações.

#### 5. Desfazendo Alterações:

- Para desfazer uma alteração, utilize git restore "filename" ou git reset HEAD "filename" para restaurar para uma versão anterior.

#### 6. Gerenciando Branches:

- Crie um novo branch com git branch nome-novo-branch e mude para ele usando git checkout nome-novo-branch.
- Para mesclar branches, retorne ao branch principal (git checkout master) e faça a mesclagem usando git merge nome-novo-branch.

#### 7. Atualizando e Compartilhando o Código:

- Antes de enviar suas alterações para o repositório remoto, utilize git fetch e git diff para visualizar as mudanças.
- Finalmente, use git pull para mesclar as alterações e git push origin master para enviar suas alterações para o repositório remoto.

### Comandos Git Comuns
- Adiciona o arquivo especificado:
``` bash
git add nomedoarquivo.extensão
```
- Exibe o status dos arquivos:
``` bash
git status
```
- Mostra as mudanças nos arquivos:
``` bash
git diff
```
- Realiza um commit com uma mensagem descritiva:
``` bash
git commit -m "mensagem"
```
- Visualiza o histórico de commits:
``` bash
git log
```
- Restaura um arquivo para uma versão anterior:
``` bash
git restore nomedoarquivo.extensão
```
- Volta o arquivo para o estado anterior:
``` bash
git reset HEAD nomedoarquivo.extensão
```
- Remove o arquivo do rastreamento:
``` bash
git rm nomedoarquivo.extensão
```
- Lista os branches e mostra o branch atual:
``` bash
git branch
```
- Altera para o branch especificado:
``` bash
git checkout nome-do-branch
```
- Arquiva temporariamente as alterações:
``` bash
git stash
```
- Mostra os repositórios remotos configurados:
``` bash
git remote -v
```

Para mais informações, consulte as documentações do [Github](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet.pdf), [Git](https://git-scm.com/docs/git/pt_BR) e [Outros](https://gist.github.com/leocomelli/2545add34e4fec21ec16)(comandos mais avançados).

### Você também pode estudar outras alternativas como:

### GitLab:
- #### Características Principais:

  - GitLab oferece uma plataforma completa para o ciclo de vida de DevOps, incluindo hospedagem de repositórios Git, rastreamento de problemas, integração contínua, entrega contínua (CI/CD), monitoramento e muito mais.
  - Pode ser auto-hospedado ou usado como um serviço na nuvem.
  - Oferece recursos avançados de colaboração, como wikis, issue boards, merge request approvals, e muito mais.
  - Licença de código aberto disponível na versão Community Edition, com recursos mais avançados na versão Enterprise Edition.
- #### Diferenciais:

  - GitLab é conhecido por sua abordagem integrada de DevOps, fornecendo uma solução abrangente para equipes de desenvolvimento.
  - A versão Community Edition é gratuita e oferece muitos recursos poderosos para pequenas equipes e projetos de código aberto.

### Bitbucket:
- #### Características Principais:

  - Desenvolvido pela Atlassian, o Bitbucket oferece hospedagem gratuita e privada de repositórios Git e Mercurial.
  - Integração nativa com outras ferramentas da Atlassian, como Jira, Confluence e Trello.
  - Oferece suporte para pipelines de integração e entrega contínua (CI/CD) diretamente na plataforma.
- #### Diferenciais:

  - O Bitbucket é uma escolha popular para equipes que já utilizam outras ferramentas da Atlassian, facilitando a integração e o fluxo de trabalho.
  - Oferece opções flexíveis de controle de acesso e permissões, incluindo repositórios públicos e privados.

### Azure DevOps Services:
- #### Características Principais:

  - Oferece uma suíte de ferramentas para colaboração de desenvolvimento de software, incluindo controle de versão Git, rastreamento de problemas, integração contínua e entrega contínua (CI/CD).
  - Integra-se perfeitamente com outras ferramentas e serviços da Microsoft, como Visual Studio e Azure Cloud.
  - Permite a automação de todo o processo de desenvolvimento, desde a construção até a implantação.
- #### Diferenciais:

  - Azure DevOps Services oferece uma integração profunda com o ecossistema da Microsoft, permitindo que equipes que já utilizam outras ferramentas da Microsoft aproveitem ao máximo a integração e o suporte.

- #### Escolha da Plataforma:
  - GitLab é ideal para equipes que buscam uma solução completa de DevOps em um único lugar, incluindo repositórios Git, CI/CD, rastreamento de problemas e muito mais.

  - Bitbucket é uma escolha sólida para equipes que já estão integradas ao ecossistema da Atlassian e procuram uma solução unificada para colaboração e desenvolvimento de software.

  - Azure DevOps Services é uma opção poderosa para equipes que estão profundamente integradas ao ambiente Microsoft e desejam uma solução completa de DevOps com integração estreita com serviços Azure.
  

Este guia oferece uma introdução básica aos principais comandos do Git e GitHub para iniciantes. À medida que você ganha mais experiência, explore recursos avançados e práticas recomendadas para melhorar sua habilidade com controle de versão e colaboração em projetos de software.

Recomendação de Estudo: [LinkedIn](https://www.linkedin.com/learning-login/share?forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fgit-e-github-formacao-basica%3Ftrk%3Dshare_ent_url%26shareId%3D%252F0beD%252F68Thm8bjWKKDD6qA%253D%253D) - Git e Github, [LinkedIn](https://www.linkedin.com/learning-login/share?forceAccount=false&redirect=https%3A%2F%2Fwww.linkedin.com%2Flearning%2Fgit-for-teams%3Ftrk%3Dshare_ent_url%26shareId%3DKb8kJwKJT1O8J8H%252BUV2Kxg%253D%253D) - Git for Teams e [DIO](https://dio.me/curso-linux/AF7AWZ2AEG8V) onde você pode aprender sobre Linux e também os fundamentos de Git e Github.
