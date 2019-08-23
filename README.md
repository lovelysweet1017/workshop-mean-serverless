# Workshop - MEAN & Serverless

[![bit-community.png](https://i.postimg.cc/4yVhWzYt/bit-community.png)](https://postimg.cc/BPZ66PcQ)

Repositório responsável pelo workshops de MEAN & Serverless.

## O que eu vou aprender?! 📙

Durante o tutorial, você aprenderá a desenvolver uma aplicação que consiste em realizar um cadastro de um Funcionário para uma empresa XYZ. A qual, usaremos as operações CRUD (Create, Read, Update & Delete). A aplicação estará integrada com o Back-End(Node.js) e estará hospedada na plataforma Cloud da Microsoft - Azure.

Os dados do Funcionário consiste em:

**Classe: Funcionario**

+ idFuncionario: (number - guid gerado pelo MongoDb)
+ nomeFuncionario: string
+ cargo: string
+ numeroIdentificador: number

## Recursos Utilizados 🚀

* **[Visual Studio Code](https://code.visualstudio.com/?WT.mc_id=meanserverlessworkshop-github-gllemos)**
* **[Node.js](https://nodejs.org/en/)**
* **[Postman](https://www.getpostman.com/)**
* **[Conta - Azure](https://azure.microsoft.com/pt-br/?WT.mc_id=meanserverlessworkshop-github-gllemos)**
* **[Azure Web App Service](https://azure.microsoft.com/services/app-service/?WT.mc_id=meanserverlessworkshop-github-gllemos)**
* **[Extensão Visual Studio Code: Azure Functions](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions&WT.mc_id=meanserverlessworkshop-github-gllemos)**
* **[Azure Storage Account](https://azure.microsoft.com/pt-br/services/storage/?WT.mc_id=meanserverlessworkshop-github-gllemos)**

## Conta - Azure for Students ⭐️

Caso você seja um(a) estudante de alguma Instituição de Ensino de Faculdade ou Universidade, poderá criar sua conta no **[Azure for Students](https://azure.microsoft.com/pt-br/free/students/?WT.mc_id=meanserverlessworkshop-github-gllemos)**. Essa conta te dará o benefício em possuir crédito de USD 100,00 para usar os serviços de maneira gratuita, sem necessidade de possuir um cartão de crédito. Para ativar essa conta, bastam acessar o link ao lado: **[AQUI](https://azure.microsoft.com/pt-br/free/students/?WT.mc_id=meanserverlessworkshop-github-gllemos)**

## Pré-requisitos 📌

Para a realização dos workshops de React.js, se faz necessário ter noções de: **HTML, CSS & JavaScript**. Pensando nisso, estou disponibilizando abaixo dois cursos grátis de:

* **[Crie um site simples usando HTML, CSS e JavaScript](https://docs.microsoft.com/learn/modules/build-simple-website/?WT.mc_id=meanserverlessworkshop-github-gllemos)**

* **[Desenvolva aplicativos Web com o Visual Studio Code](https://docs.microsoft.com/learn/modules/develop-web-apps-with-vs-code/?WT.mc_id=meanserverlessworkshop-github-gllemos)**

## Executando a Aplicação Localmente ❗️

### Executando a aplicação no lado do Front-End

1) Instalar os pacotes com o comando: (dentro da pasta `front`)

``` 
> npm install
```

2) Depois executar o seguinte comando para executar a aplicação (dentro da pasta `front`):

```
> ng serve -o
```

Depois bastam abrir o browser em **localhost:4200** (porta padrão de uma aplicação Angular)

### Executando a aplicação no lado do Back-End

Antes de iniciar os passos abaixo é muito importante que você execute nesse momento o MongoDb localmente!

1) Instalar os pacotes com o comando: (dentro da pasta `api`)

``` 
> npm install
```

2) Depois executar o seguinte comando para executar a aplicação (dentro da pasta `api`):

```
> nodemon
```

Depois bastam abrir o postamn em **localhost:8000** e testar as requisições

E vòilá! :heart: :heart:

## Links & Recursos Importantes ⭐️

Durante o workshop, comentei sobre importantes documentações, links e recursos que podem auxiliar o seu conhecimento sobre Serverless & Azure Functions

- ✅ **[Azure para devs JavaScript & Node.js](https://docs.microsoft.com/pt-br/javascript/azure/?WT.mc_id=meanserverlessworkshop-github-gllemos&view=azure-node-latest)**
- ✅ **[Documentação Azure Functions](https://docs.microsoft.com/pt-br/azure/azure-functions/?WT.mc_id=meanserverlessworkshop-github-gllemos)**
- ✅ **[Criando a sua Primeira Função no Visual Studio Code](https://docs.microsoft.com/pt-br/azure/azure-functions/functions-create-first-function-vs-code?WT.mc_id=meanserverlessworkshop-github-gllemos)**
- ✅ **[Extensão Vs Code – Azure Functions](https://marketplace.visualstudio.com/items?itemName=ms-azuretools.vscode-azurefunctions&WT.mc_id=meanserverlessworkshop-github-gllemos)**
- ✅ **[E-Book Grátis - Azure Serverless Computing Cookbook](https://azure.microsoft.com/pt-br/resources/azure-serverless-computing-cookbook/?WT.mc_id=meanserverlessworkshop-github-gllemos)**
- ✅ **[Cursos Grátis - Azure Functions](https://docs.microsoft.com/pt-br/learn/paths/create-serverless-applications/?WT.mc_id=meanserverlessworkshop-github-gllemos)**

## Tenho Dúvidas... O que Faço?! ❓

Caso tenham dúvidas aos códigos dos projetos relacionados aos workshops, sintam-se a vontade em abrir uma **[ISSUE AQUI](https://github.com/glaucia86/workshop-mean-serverless/issues)**. Assim que possível, estarei respondendo as todas as dúvidas que tiverem!


**(documentação em desenvolvimento)**