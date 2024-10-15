# Repositório do Desafio de Projeto sobre Git e Github da DIO
Desafio de Projeto (DIO)

## Links Úteis

[Sintaxe Básica Markdown] (https://www.markdownguide.org/basic-syntax/) 
[Guia git](https://git-scm.com)
[Curso Introdução ao Git e GitHub DIO] (https://web.dio.me/course/versionamento-de-codigo-com-git-e-github/learning/f3cbaa66-efbd-4c25-842e-2069c188c066?back=/track/potencia-tech-ifood-desenvolvimento-de-jogos&tab=undefined&moduleId=undefined)
[Editor de Readme.md] (https://readme.so/pt)

## Comandos importantes 

### Git clone <URL>
Clona um repositório existente para um novo diretório (Pasta ou local).

### Git pull
Puxa as alterações do repositório remoto para o local, busca e  mescla.

### Git push 
Empurra as alterações repositório local para o repositório remoto.

### Git remote add origin <URL>
Conecta o repositório local com o repositório remoto.

### Git clone <URL> --branch <Nome da branch> --single branch
Irá clonar apenas a branch citada do repositório.

### Git fetch + Git diff + Git merge
Baixa todos os arquivos conflitados sem os mesclar.

### Fazendo alterações

#### Git add .
Adiciona todas as alterações feitas no repositório, permitindo a 'commitação' delas.

#### Git commit -m"<Nome do commit>"
Grava alterações no repositório.

### Desfazendo alterações

#### Git restore <Nome do arquivo>
Desfaz todas as alterações feitas no arquivo, restaurando as informações do commit anterior.

#### Git reset --{Hard, mixed ou soft} <Id do commit>
Reseta todas as alterações feitas no repositório ate o último commit.

### Criando branches 

#### Git branch 
mostras todas as branches criadas. 

#### Git branch -b<Nome da branch> 
Cria e seleciona uma branch.

#### git branch merge <Nome da branch>
Junta a branch seleciona com as outras disponiveis. 

### Conflitos
Git pull para puxar os arquivos refazer as alterações feitas e para fazer as alterações no repositório remoto git push.