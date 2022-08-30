# <h1 align="center"> 📝 Docker Todo List ✔️ </h1>

## Descrição:

<p text-align="justify" >O Docker Todo List foi o primeiro projeto desenvolvido no módulo de Back-end na Trybe; sua proposta foi permitir por em prática a utilização de comandos do docker com diferentes níveis de complexidade. A partir disso seguindo uma sequência para criar as imagens para as aplicações e configurar essas imagens com o docker-compose</p>
<p text-align="justify" >A estrutura fornecida foi uma aplicação full-stack de aplicativo de tarefas; sendo nosso objetivo contenerizar a aplicação desenvolvendo  os arquivos de configuração para Front-end, Back-end e testes, onde testes deveria validar se Front-end e Back-end estavam se comunicando</p>

## Ferramentas utilizadas:

###

<div align="left">
<img src="https://ccie.tv/content/images/2019/08/docker-5.svg" height="60" width="60" alt="react logo"/>
<img height="60" width="60" src="https://www.mundodocker.com.br/wp-content/uploads/2015/12/docker_compose.png"/>
<p text-align="justify">
O Docker é uma plataforma aberta, que facilita o desenvolvimento, a implantação e a execução de aplicações a partir de sua conteinerização, permitindo que elas rodem em ambientes isolados. Enquanto isso o Docker-Compose configura as imagens desses containers e se responsabiliza pela conexão entre eles.
</p>
</div>

###

## Rodando o projeto na sua máquina:

Se você ainda não tiver o Docker instalado na sua máquina [siga os passos deste link](https://docs.docker.com/engine/install/ubuntu/#:~:text=/dev/null-,Install%20Docker%20Engine,-Update%20the%20apt) antes de continuar.

1. Escolha um diretório e clone o repositório utilizando **git clone**:
```
  git clone git@github.com:AirelRibeiro/docker-to-do-list-.git
```

2. Acesse o diretório do projeto e nele acesse o diretório **docker**:
```
  cd docker-to-do-list
  cd docker
```

3. Então **docker-compose up -d** para criar e iniciar os contêineres:
```
  docker-compose up -d
```

4. Por fim, acesse o projeto via navegador, usando a seguinte url:
```
  http://localhost:3000
```
