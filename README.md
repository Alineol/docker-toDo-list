# <img alt="docker" width = "100px" src="./images/docker.png" > docker-toDo-list <img alt="docker" width = "100px" src="./images/docker.png" >
Projeto para testar docker.

Acessando a pasta docker/docker-comands você verá em cada arquivo numerado o comando feito para realizar os seguintes desafios: 

**Comandos docker:**
1. Crie um novo container de modo interativo sem roda-lo nomeando-o como 01container e utilizando a imagem alpine usando a versão 3.12
2. Inicie o container 01container
3. Liste os containers filtrando pelo nome 01container
4. Execute o comando cat /etc/os-release no container 01container sem se acoplar a ele
5. Remova o container 01container que está em andamento.
6. Faça o download da imagem nginx com a versão 1.21.3-alpine sem criar ou rodar um container.
7. Rode um novo container com a imagem nginx com a versão 1.21.3-alpine em segundo plano nomeando-o como 02images e mapeando sua porta padrão de acesso para porta 3000 do sistema hospedeiro.
8. Pare o container 02images que está em andamento.
Dockerfile
9. Gere uma build a partir do Dockerfile do back-end do todo-app nomeando a imagem para todobackend.
10. Gere uma build a partir do Dockerfile do front-end do todo-app nomeando a imagem para todofrontend.
11.Gere uma build a partir do Dockerfile dos testes do todo-app nomeando a imagem para todotests.
Bônus
Docker-compose
12. Suba uma orquestração em segundo plano com o docker-compose de forma que backend, frontend e tests consigam se comunicar.

**obs: a pasta docker/todo-app foi fornecida pela trybe, eu inseri dados somente na pasta docker/docker-comands e no docker/dockerCompose.yml**
