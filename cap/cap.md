# CAP - Cloud Application Programming Model

| [Level 1](#level-1) <br> Nível 1 <br> Fundamentos e conceitos essenciais para iniciar a jornada | [Level 2](#level-2) <br> Nível 2 <br> Especialização e domínio intermediário das tecnologias | [Level 3](#level-3) <br> Nível 3 <br> Conceitos avançados, visão de arquitetura e inovações |
|----|----|----|
| [CAP](#cap)| [Profiles (dev, hybrid, prod)](#profiles-dev-hybrid-prod)| [Test: Jest/Mocha](#test-jestmocha) |
| [OData](#odata)| [.http (or Postman)](#http-or-postman)| [Messaging](#messaging) |
| [SAPUI5 (basic)](#sapui5-basic)| [Fiori Freestyle (SAPUI5)](#fiori-freestyle-sapui5) | [CAP TypeScript](#cap-typescript) |
| [Fiori Elements Annotations](#fiori-elements-annotations) | [Fiori Launchpad Plugin](#fiori-launchpad-plugin) | |
| [CDS (CDS Annotations)](#cds-cds-annotations)| [HANA](#hana) | |
| [XSUAA (Roles & Role Collections)](#xsuaa-roles--role-collections)| [External Services](#external-services) | |
| [Destinations (Connectivity - Cloud Connector)](#destinations-connectivity---cloud-connector)| [capire](#capire) | |

## Level 1
**CAP Fundamentals**

Start here your learning journey to become a Cloud Application Programming Model developer. What is CAP? What are the technologies and concepts at its base? These and more questions will be answered on this path.

**Fundamentos do CAP**

Comece aqui sua jornada de aprendizado para se tornar um desenvolvedor do Cloud Application Programming Model. O que é CAP? Quais são as tecnologias e conceitos em sua base? Essas e outras perguntas serão respondidas neste caminho.

### CAP
Get your hands dirty with courses and tutorials to learn how to build a Cloud Application Programming Model (CAP) application.

Ponha a mão na massa com cursos e tutoriais para aprender como construir uma aplicação CAP.

- [ ] *PT* Course Moovi [SAP CAP](https://moovi.curseduca.pro/m/lessons/sap-cap-1747766278946)
- [ ] *EN* Course learning.sap [Introduction to SAP Cloud Application Programming Model](https://learning.sap.com/courses/introduction-to-sap-cloud-application-programming-model)
- [ ] *EN* Course learning.sap [Develop extensions with CAP following the SAP BTP Developer's Guide](https://learning.sap.com/courses/develop-extensions-with-cap-following-the-sap-btp-developer-s-guide/)
- [ ] *EN* Hands-on capire [Getting Started](https://cap.cloud.sap/docs/get-started/#initial-setup)

### OData
OData is the default communication protocol used by SAP, and consequently by CAP. Mastering it will help you understand how your requests are automatically translated into database queries.

OData é o protocolo de comunicação padrão utilizado pela SAP e, consequentemente, pelo CAP. Dominá-lo ajudará você a entender como suas requisições são automaticamente convertidas em consultas ao banco de dados.

- [ ] *PT* Moovi [Gateway e OData](https://moovi.curseduca.pro/m/lessons/gateway-e-odata-1734443760098)
- [ ] *EN* odata.org [OData - Getting Started](https://www.odata.org/getting-started/)
- [ ] **Northwind OData example service [Northwind](https://services.odata.org/Northwind/Northwind.svc/)**
- [ ] *PT* StackOverflow [O que é e para que serve OData](https://pt.stackoverflow.com/questions/284722/o-que-%C3%A9-e-para-que-serve-odata)

### SAPUI5 (basic)
Learn the basics of SAPUI5, the front-end web framework developed by SAP, to understand what your CAP application needs to provide for an optimal experience.

Aprenda o básico do SAPUI5, o framework web front-end desenvolvido pela SAP, para entender o que sua aplicação CAP precisa fornecer para uma experiência ideal.

- [ ] *EN* Course learning.sap [Developing UIs with SAPUI5](https://learning.sap.com/courses/developing-uis-with-sapui5-1)
- [ ] *EN* ui5.sap [Get Started: Setup, Tutorials, and Demo Apps](https://ui5.sap.com/#/topic/8b49fc198bf04b2d9800fc37fecbb218)

### Fiori Elements Annotations
SAP has already set standards and guidelines for User Interfaces with [Fiori](https://www.sap.com/design-system/fiori-design-web/v1-145/discover/get-started). It has also defined an Annotation system to automatically map service data to these predefined UIs. Learn to use them and your app's UI will be ready in a matter of minutes.

A SAP já definiu padrões e diretrizes para interfaces de usuário com o Fiori. Também definiu um sistema de Anotações para mapear automaticamente os dados do serviço para essas UIs predefinidas. Aprenda a usá-los e a interface do seu aplicativo estará pronta em poucos minutos.

- [ ] *PT* Course Moovi [Fiori Elements](https://moovi.curseduca.pro/m/lessons/fiori-elements-1734443760098)
- [ ] *EN* Course learning.sap [Developing an SAP Fiori Elements App Based on a CAP OData V4 Service](https://learning.sap.com/courses/developing-an-sap-fiori-elements-app-based-on-a-cap-odata-v4-service)
- [ ] *EN* capire [Serving SAP Fiori UIs](https://cap.cloud.sap/docs/guides/uis/fiori)
- [ ] *EN* ui5.sap [Developing Apps with SAP Fiori Elements](https://ui5.sap.com/#/topic/03265b0408e2432c9571d6b3feb6b1fd)

### CDS (CDS Annotations)
The Core Data & Services language is a middle ground for all your needs in a CAP application. From it, you derive your data definitions, services, database artifacts, UI elements, and more. You probably already know it by now. Or do you? Take a closer look and discover that many things you implemented with code can be done with a simple CDS keyword.

A linguagem Core Data & Services é um meio termo para todas as suas necessidades em uma aplicação CAP. A partir dela, você deriva suas definições de dados, serviços, artefatos de banco de dados, elementos de UI e muito mais. Você provavelmente já a conhece. Será que conhece mesmo? Dê uma olhada mais atenta e descubra que muitas coisas que você implementou com código podem ser feitas com uma simples palavra-chave CDS.

- [ ] *EN* capire [CDS Docs](https://cap.cloud.sap/docs/cds/)
- [ ] *EN* Course learning.sap [Introduction to SAP Cloud Application Programming Model](https://learning.sap.com/courses/introduction-to-sap-cloud-application-programming-model)

### XSUAA (Roles & Role Collections)
Secure your CAP app with the XSUAA model. Who can be trusted? What parts of the application can be accessed? Understand the system to learn how you can easily define these settings in a CAP app.

Proteja sua aplicação CAP com o modelo XSUAA. Quem pode ser confiável? Quais partes da aplicação podem ser acessadas? Entenda o sistema para aprender como você pode facilmente definir essas configurações em uma aplicação CAP.

- [ ] *EN* help.sap [What Is the SAP Authorization and Trust Management Service?](https://help.sap.com/docs/btp/sap-business-technology-platform/what-is-sap-authorization-and-trust-management-service?locale=en-US)
- [ ] *PT* help.sap [O que é o serviço SAP Authorization and Trust Management?](https://help.sap.com/docs/btp/sap-business-technology-platform/what-is-sap-authorization-and-trust-management-service?locale=pt-BR)
- [ ] *EN* SAP Discovery Center [SAP Authorization and Trust Management Service](https://discovery-center.cloud.sap/serviceCatalog/authorization-and-trust-management-service?region=all)

### Destinations (Connectivity - Cloud Connector)
Take advantage of SAP BTP's Destination service to decouple your application from the endpoints it consumes when communicating with other systems. Understand how the Connectivity service (and the Cloud Connector) enable communication between your app in BTP and the SAP system behind the firewall of the customer's intranet.

Aproveite o serviço Destination do SAP BTP para desacoplar sua aplicação dos endpoints que ela consome ao se comunicar com outros sistemas. Entenda como o serviço Connectivity (e o Cloud Connector) possibilitam a comunicação entre seu aplicativo no BTP e o sistema SAP por trás do firewall da intranet do cliente.

- [ ] *EN* SAP Discovery Center [SAP Destination Service](https://discovery-center.cloud.sap/serviceCatalog/destination-service)
- [ ] *EN* help.sap [Destination Service](https://help.sap.com/docs/connectivity/sap-btp-connectivity-cf/destination-service?locale=en-US)
- [ ] *EN* SAP Discovery Center [SAP Connectivity Service](https://discovery-center.cloud.sap/serviceCatalog/connectivity-service)
- [ ] *EN* help.sap [Connectivity Service](https://help.sap.com/docs/connectivity/sap-btp-connectivity-cf/connectivity-service-bd2d4f45e0494121a058ad9c015ba348?locale=en-US)
- [ ] *EN* help.sap [Cloud Connector](https://help.sap.com/docs/connectivity/sap-btp-connectivity-cf/cloud-connector?locale=en-US)

## Level 2

**CAP Development Tools**

Enough theory! Now let's dive into CAP development itself and master our coding skill.

**Ferramentas para Desenvolvimento CAP**

Chega de teoria! Agora vamos mergulhar no próprio desenvolvimento CAP e dominar nossa habilidade de programação.

### Profiles (dev, hybrid, prod)
Do you want...
- it fast? Run it locally with the *development* profile. Use SQlite as your local in-memory database with test data that exists only during the app execution.
- to integrate with the BTP services? Run it locally consuming the remote BTP services with the *hybrid* profile. Learn the secret successfully connect to your Destination that uses the Connectivity service.
- to deploy it to BTP? Define the settings for the *production* profile.

Configure and choose the appropriate profile for your needs.

Voce quer...
- rapidez? Execute localmente com o perfil *development*. Use SQlite como sua base de dados em memória local com dados de teste que existem apenas durante a execução do app.
- integrar com os serviços do BTP? Execute localmente consumindo os serviços remotos do BTP com o perfil *hybrid*. Aprenda o seguredo para fazer funcionar aquela Destination que utiliza o serviço de Connectivity.
- fazer o deploy no BTP? Defina as configurações para o perfil *production*.

Configure e escolhe o perfil adequado a suas necessidades.

- [ ] *EN* capire [Configuration Profiles](https://cap.cloud.sap/docs/node.js/cds-env#profiles)
- [ ] *EN* capire [Authentication in Hybrid Setup](https://cap.cloud.sap/docs/node.js/authentication#hybrid-setup)
- [ ] *EN* capire [Using SQLite for Development](https://cap.cloud.sap/docs/guides/databases/sqlite)
- [ ] *EN* blogs.sap [SAP CAP Lessons Learned: Hybrid Development with On-Premise SAP System](https://community.sap.com/t5/technology-blog-posts-by-members/sap-cap-lessons-learned-hybrid-development-with-on-premise-sap-system/ba-p/13972708)

### .http (or Postman)
Your web browser is good enough to test GET requests of your services, though sometimes clunky when you have some parameters you want to change. Let's step to the next level. Let's have it as code, and test all GET, POST, PUT, and DELETE methods. In a CAP project you can test using the *.http* files enabled by [VSCode REST Client](https://github.com/Huachao/vscode-restclient). Or if you're already familiar with [Postman](https://www.postman.com/) or [Bruno](https://www.usebruno.com/), you may use them as well.

Seu navegador web é suficiente para testar requisições GET dos seus serviços, embora às vezes seja complicado quando você precisa alterar alguns parâmetros. Vamos para o próximo nível. Vamos ter isso como código e testar todos os métodos GET, POST, PUT e DELETE. Em um projeto CAP, você pode testar usando arquivos *.http*. Ou, se já estiver familiarizado com Postman ou Bruno, pode usá-los também.

- [ ] *EN* capire [CDS CLI HTTP](https://cap.cloud.sap/docs/tools/cds-cli#http)
- [ ] *EN* Blog LinkedIn [How to Test Your SAP CAP APIs Locally Using api.http (No Postman Needed!)](https://www.linkedin.com/pulse/how-test-your-sap-cap-apis-locally-using-apihttp-postman-khan-ysbxf/)
- [ ] *EN* GitHub repo [VSCode REST Client](https://github.com/Huachao/vscode-restclient)

### Fiori Freestyle (SAPUI5)
Eventually, Fiori Elements Annotations won't be enough to perform all the custom actions you need for your applications. You'll then need to learn how to add Extension Points to your application and use SAPUI5 elements directly, which is commonly called Freestyle.

Eventualmente, as Anotações do Fiori Elements não serão suficientes para realizar todas as ações personalizadas que você precisa em suas aplicações. Nesse momento, será necessário aprender como adicionar Extension Points à sua aplicação e usar diretamente os elementos do SAPUI5, o que é comumente chamado de Freestyle.

- [ ] *PT* Moovi [Fiori Freestyle](https://moovi.curseduca.pro/m/lessons/fiori-freestyle-1734443760098)
- [ ] *EN* ui5.sap [SAPUI5 API Reference](https://ui5.sap.com/#/api)
- [ ] *EN* ui5.sap [SAPUI5 Samples](https://ui5.sap.com/#/controls)
- [ ] *EN* ui5.sap [Extending Generated Apps Using App Extensions](https://ui5.sap.com/#/topic/340cdb2ba97c4843979f905a70a327ee)

### Fiori Launchpad Plugin
Have a local environment that simulates Fiori Launchpad (Work Zone, standard).

Tenha um ambiente local que simula o  Fiori Launchpad (Work Zone, standard).

- [ ] *EN* blogs.sap [A Fiori Launchpad Sandbox for all your CAP-based projects - Overview](https://community.sap.com/t5/technology-blog-posts-by-members/a-fiori-launchpad-sandbox-for-all-your-cap-based-projects-overview/ba-p/13528514)
- [ ] *EN* blogs.sap [A Fiori Launchpad Sandbox for all your CAP-based projects – Sample project setup](https://community.sap.com/t5/technology-blog-posts-by-members/a-fiori-launchpad-sandbox-for-all-your-cap-based-projects-sample-project/ba-p/13528575)

### HANA
In your *hybrid* or *production* profiles, you'll most likely be using a HANA database. Learn what you can assume and what you need to take care of, what your application can assume and what it must explicitly tell the database.

Nos seus perfis *hybrid* ou *production*, você provavelmente usará um banco de dados HANA. Aprenda o que você pode assumir e com o que precisa se preocupar, o que sua aplicação pode assumir e o que ela deve informar explicitamente ao banco de dados.

- [ ] *EN* [HANA Guide](https://cap.cloud.sap/docs/guides/databases/hana)
- [ ] *EN* blogs.sap [SAP CAP Lessons Learned: SQLite is single threaded, HANA is not](https://community.sap.com/t5/technology-blog-posts-by-members/sap-cap-lessons-learned-sqlite-is-single-threaded-hana-is-not/ba-p/13972788)

### External Services
Your application is not alone. Learn how to import external services, consume them, and combine them with your own. Establish seamless communication within and outside your app.

Sua aplicação não está sozinha. Aprenda como importar serviços externos, consumi-los e combiná-los com os seus próprios. Estabeleça uma comunicação perfeita dentro e fora do seu aplicativo.

- [ ] *EN* capire [Importing APIs](https://cap.cloud.sap/docs/guides/integration/calesi#odata-apis)

### capire
Finally, pin the official SAP Cloud Application Programming Model documentation site to your bookmarks bar. Make sure it's always your first option when in doubt. By doing this, you'll learn how to properly read documentation and solve most of your problems on your own.

Por fim, fixe o site oficial da documentação do SAP Cloud Application Programming Model na barra de favoritos do seu navegador. Certifique-se de que seja sempre sua primeira opção em caso de dúvida. Ao fazer isso, você aprenderá a ler a documentação corretamente e resolverá a maioria dos seus problemas sozinho.

- [ ] *EN* [capire](https://cap.cloud.sap/docs/)

## Level 3
**Advanced CAP Development Tools**

### Test: Jest/Mocha
-
### Messaging
-
### CAP TypeScript
-
