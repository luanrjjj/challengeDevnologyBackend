# challengeDevnologyBackend

Ao abrir o arquivo do projeto para instalação das dependências contidas no package.json execute yarn no terminal.

Depois da instalação das dependências, também na pasta do diretório execute yarn start para iniciliazar o projeto. 

É necessário ter um container do mongodb na porta 27017 com o nome mongo, como pode ser visto no arquivo ormconfig.jso, já que nesse projeto foi utilizado o typeorm

![image](https://user-images.githubusercontent.com/71605566/139562300-d77363c7-2b25-45ed-ae74-43171b478ed6.png)

A imagem do mongodb pode ser criada com o seguinte comando : docker pull mongo

E a criação do container pode ser feito da seguinte forma : docker run --name mongodb -p 27017:27017 -e MONGO_INITDB_ROOT_USERNAME=balta -e MONGO_INITDB_ROOT_PASSWORD=e296cd9f mongo

Depois de configurado o container, execute yarn dev:server no terminal.

Neste projeto foi utilizado o Typeorm e o MongoDB compass para visualização dos schemas.

Salvei no banco de dados os dados do usuário e o carrinho de compra do checkout. Os dados foram salvos da seguinte maneira no banco de dados.

![image](https://user-images.githubusercontent.com/71605566/139562363-55480cb6-41bc-4a43-88f8-c0dc93c138ca.png)

