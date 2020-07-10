# Projeto e desafio Bem Promotora


## Recursos utilizados no desenvolvimento:

- Node.Js - [DOWNLOAD AQUI](https://nodejs.org/en/)
- Express.Js ~ v.4.0;
- Conceito RestFul;
- MongoDb - [DOWNLOAD AQUI](https://www.mongodb.com/)
- Visual Studio Code - [DOWNLOAD AQUI](https://code.visualstudio.com/)
- Ejs (Para gerar o HTML)
- JSON data (para retornar os dados);


## Executar Localmente

Caso você deseja executar o projeto na sua máquina local, basta seguir os passos abaixo:

## Começando...

Para começar, você deve simplesmente clonar o repositório do projeto na sua máquina e instalar as dependências.

### Pre-Requisitos

Antes de instalar as dependências no projeto, você precisa já ter instalado na sua máquina:

* **Node.Js**: Caso não tenha, basta realizar o download [Aqui](https://nodejs.org/en/)
* **MongoDb**: Caso também não tenha, basta realizar o download [Aqui](https://www.mongodb.com/download-center#community)

p.s.: o MongoDb caso você decida conectar a sua base de dados de maneira local. Caso não, basta usar 
a base de dados do MongoDb Atlas, que já está configurado:


### Instalando as Dependências

Abre o cmd (caso esteja utilizando o Windows) e digite a path do seu projeto

```
cd "C:\Users\NomeDoComputador\Documents\..."
```

Depois, quando estiver na pasta do projeto, basta digitar no cmd a seguinte instrução:

```
npm install
```

Ao digitar a instrução acima, automaticamente ele irá baixar todas as dependências listadas no arquivo package.json:

* `node_modules` - que contêm os packages do npm que precisará para o projeto.

### Executando a Aplicação

Bom, agora na mesma tela do cmd, basta iniciar o server para o projeto ser executado localmente.

```
npm run dev
```


Agora, abre a página da aplicação em `http://localhost:3000/api`. E pronto a aplicação será executada de maneira local na sua máquina.        

p.s.: no projeto, disponibilizei 2 maneiras de realizar a conexão de dados com o MongoDb através do Mongoose:

* **De maneira local**: utilizando o MongoDb;
* **De maneira em cloud**: utilizando o Atlas mongo;

Fiquem à vontade em usar ou até mesmo testar ambas as conexões!! :)  

