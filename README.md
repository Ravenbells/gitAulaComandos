# Comandos do bash

- pwd: ver onde eu estou no computador;
- touch: criar um arquivo vazio;
- cd: me mover para outro lugar/diretório;
- echo: comando para escrever algo no terminal ou em um arquivo;

# Comandos Git

- git config --global --list: ver em lista as configurações globais;
- git config --global user.name "nome": definir nome global;
- git config --global user.email "email@email.com": definir email global;

- git init: inicia pela primeira vez o git em um projeto/pasta;
- git branch -m nomeBranch: inicia pela primeira vez um branch no projeto;
- git branch -v: permite visualizar os branchs de um projeto (Somente Locais);
- git branch -a -v: permite visualizar os branchs remotos (Github);
- git status: permite ver o que está acontecendo com os arquivos no git;

- git add: adiciona os arquivos que foram modificados para serem rastreados pelo git;
- git add . : Adiciona todos os arquivos da pasta que estamos (veja pelo pwd);
- git add Arquivo1 Arquivo2 Arquivo3: Adiciona um arquivo no Git de acordo com o nome;

- git commit -m "mensagem commit": criar o salvamento da minha versão localmente com uma mensagem de atualização;

- git remote add origin https://github.com/MeuNomeGithub/Meurepositorio.git: 
adiciona o repositório online do Github com o nome de "origin" no meu Git;
- git remote -v: visualiza os repositórios remotos registrados no Git.

- git -h: exibe a ajuda geral do git. Posso utilizar outro comando para ter informações específicas daquele comando. Ex: git remote -h.

- git push -u origin master: Empurra o código local do Git para o repositório online (Github), o -u garante que o branch, por exemplo "master" seja criado no repositório
se não houver o mesmo.