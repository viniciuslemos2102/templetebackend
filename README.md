# eslint configurado para node.js

###  Esse é templete basico configurado para o back end de uma stack.

#####  segue abaixo uma lista de componetes e biblioteca de instalação para esse arquivo funcionar

#####  procure em extenções:

  * eslint

  * baixe dentro do seu vscode

  * configure as regras

  * como starta a o banco

  ##### primeiro passo

  #####inicia a docker com o seguinte comando

  <docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5431 -d postgres:11-alpine> #####por exemplo se a primeira vez, agora se já tiver criando alguma imagem é só utiliza o seguinte comando

  <docker start [nome do banco]>

  <yarn sequelize db:migration>
  <yarn dev>

  passa as informações do arquivo src/config/database.js para o postbird.
