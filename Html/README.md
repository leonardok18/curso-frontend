# Curso Frontend

# GIT
## versionamento 
- Histórico
- Controle de versão.
- Quem alterou.
- O quê alterou.
- Quando alterou.
- Todos os arquivos.
- Evolução contínua.

Arquivo A | Versão 1 | Versão 2.
Arquivo B | Versão 1 | Versão 2.

## Instação do Git
- Windons : https://git-scm.com/downloads 
- Linux (apt get) sudo apt-get install git
- Mac (brew): brew install git

## Criar conta no GitHub

## Commits 
Informação de alteração. 
- após testado todo seu código (apenas após todas as confimações no código).
- git add *
- git commit -m "mensgem" 
- git push (enviar alterações para o repositório)
- git pull ( puxar / trazer alterações do GitHub para sua máquina)

## GitFlow 
Fluxo do Git 


### Branchs
- são ramificações / versões paralelas 

- main / master ( vai para produção, quando o projeto é publicado)
- develop 
- DOD Definition of Done : critérios de aceite
- versionamento 0.1.10

git checkout -b dev (cria uma branch)
git checkout master (mudar de branch)

### Merge 
- Mescla de branchs

- git merge main

### Pull Requests 
- mescla de branchs no repositório
- permite code revisew
- o respositório resolve os conflistos automaticamente 

### configura o GitFlow
- git flow init
- git flow feature start {nome-da-feature}


