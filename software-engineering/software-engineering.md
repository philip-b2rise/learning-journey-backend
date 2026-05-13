# Software Engineering
# Engenharia de Software

| [Level 1](#level-1) <br> Nível 1 <br> Fundamentos e conceitos essenciais para iniciar a jornada | [Level 2](#level-2) <br> Nível 2 <br> Especialização e domínio intermediário das tecnologias | [Level 3](#level-3) <br> Nível 3 <br> Conceitos avançados, visão de arquitetura e inovações |
|----|----|----|
| [MVC](#mvc) | [Design Patterns](#design-patterns) | [Algorithm Complexity](#algorithm-complexity) |
| [Client-Server](#client-server) | [Separation of Concerns](#separation-of-concerns) | [Microservices](#microservices) |
| [Events](#events) | [Event-Driven Architecture](#event-driven-architecture) | [Observability](#observability) |
| [APIs](#apis) | [SOLID](#solid) | |
| [REST and OData](#rest-and-odata) | | |



## Level 1
**Web development engineering patterns**

The web has become so dominant that today even native applications are built using web technologies. Therefore, regardless of your technology of choice, it is fundamental to learn about Web Development Engineering.

**Padrões de engenharia de desenvolvimento web**

A web se tornou tão dominante que hoje até mesmo aplicações nativas são construídas usando tecnologias web. Portanto, independentemente da tecnologia de sua escolha, é fundamental aprender sobre Engenharia de Desenvolvimento Web.

### MVC
The Model-View-Controller (MVC) pattern is an important guideline to organize software code, avoiding confusion during development and making it more readable and maintainable.

O padrão Model-View-Controller (MVC) é uma diretriz importante para organizar o código do software, evitando confusão durante o desenvolvimento e tornando-o mais legível e fácil de manter.

- [ ] *EN* Wikipedia [Model-view-controller](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller)
- [ ] *PT* Wikipedia [MVC](https://pt.wikipedia.org/wiki/MVC)
- [ ] *PT* Blog Devmedia [Padrão MVC - Java Magazine](https://www.devmedia.com.br/padrao-mvc-java-magazine/21995)


### Client-Server
The Client-Server model is an early pattern defined for decentralizing applications. It's fundamental to understand the concept to know when to implement a feature or when to delegate it to the next tier.

O modelo Cliente-Servidor é um dos primeiros padrões definidos para descentralizar aplicações. É fundamental compreender esse conceito para saber quando implementar uma funcionalidade ou quando delegá-la para o próximo nível.

- [ ] *EN* Wikipedia [Client-server model](https://en.wikipedia.org/wiki/Client%E2%80%93server_model)
- [ ] *PT* Wikipedia [Modelo cliente-servidor](https://pt.wikipedia.org/wiki/Modelo_cliente%E2%80%93servidor)
- [ ] *EN* Blog Medium [Client-Server Architecture Explained with Examples, Diagrams, and Real-World Applications](https://medium.com/nerd-for-tech/client-server-architecture-explained-with-examples-diagrams-and-real-world-applications-407e9e04e2d1)
- [ ] *EN* Blog Geeks for Geeks [Client-Server Model](https://www.geeksforgeeks.org/system-design/client-server-model/)


### Events
Reactive programming starts with the understanding of the Event concept. Start your learning with web page events and you'll easily grasp the meaning of an event in Software Engineering.

A programação reativa começa com a compreensão do conceito de Evento. Inicie seu aprendizado com eventos de páginas web e você entenderá facilmente o significado de um evento em Engenharia de Software.

- [ ] *EN* W3Schools [JavaScript Events](https://www.w3schools.com/js/js_events.asp)
- [ ] *PT* MDN [Introdução a Eventos](https://developer.mozilla.org/pt-BR/docs/Learn_web_development/Core/Scripting/Events)

### APIs
An Application Programming Interface, as the name implies, is an interface. This means that if you want to interact with it, you must follow the interface definition, like a contract between you and whatever is behind the API. It also means that the API is not the software itself, but rather an agreement on how to communicate with the server that's providing it.

Uma Interface de Programação de Aplicações, como o nome sugere, é uma interface. Isso significa que, se você quiser interagir com ela, deve seguir a definição da interface, como um contrato entre você e o que está por trás da API. Também significa que a API não é o próprio software, mas sim um acordo sobre como se comunicar com o servidor que a fornece.

- [ ] *EN* Wikipedia [API](https://en.wikipedia.org/wiki/API)
- [ ] *PT* Wikipedia [Interface de programação de aplicações](https://pt.wikipedia.org/wiki/Interface_de_programa%C3%A7%C3%A3o_de_aplica%C3%A7%C3%B5es)
- [ ] *EN* Github [What is an API?](https://github.com/resources/articles/what-is-an-api)

### REST and OData
Learn about the principles of REpresentational State Transfer (REST) and understand how much you can rely on the other systems your application communicates with.
In the SAP world, the Open Data Protocol (OData) is the go-to protocol for communication. Learn how to use it and master the communication of your application.

Conheça os princípios do REpresentational State Transfer (REST) e entenda até que ponto você pode confiar nos outros sistemas com os quais sua aplicação se comunica.
No mundo SAP, o Open Data Protocol (OData) é o protocolo padrão para comunicação. Aprenda a utilizá-lo e domine a comunicação da sua aplicação.

- [ ] *EN* Tutorial [What is REST?](https://restfulapi.net/)
- [ ] *PT* Wikipedia [REST](https://pt.wikipedia.org/wiki/REST)
- [ ] *EN* odata.org [OData - Getting Started](https://www.odata.org/getting-started/)
- [ ] **Northwind OData example service [Northwind](https://services.odata.org/Northwind/Northwind.svc/)**
- [ ] *PT* StackOverflow [O que é e para que serve OData](https://pt.stackoverflow.com/questions/284722/o-que-%C3%A9-e-para-que-serve-odata)
- [ ] *PT* Sobre - [Filtros em APIS ](https://medium.com/@coderik1996/filtros-em-apis-rest-n%C3%A3o-s%C3%A3o-s%C3%B3-query-params-b7d8046d5988)

## Level 2
**Software engineering patterns**

As your software grows, so do its problems. Performance, maintenance, and readability are just a few to be named. In order to evolve software in a healthy way, some patterns must be set for organization. Luckily, smarter people have already identified and documented them.

**Padrões de engenharia de software**

À medida que seu software cresce, seus problemas também aumentam. Desempenho, manutenção e legibilidade são apenas alguns exemplos. Para evoluir um software de forma saudável, alguns padrões devem ser definidos para organização. Felizmente, pessoas mais experientes já os identificaram e documentaram.

### Design Patterns
While programming your next project, you may find yourself solving the same problem you encountered before, just with different names. You realize that, regardless of the application's context, some challenges belong to the domain of Software Engineering and are common to all applications. Design patterns are like blueprints for solving specific design problems in your code.

Ao programar seu próximo projeto, você pode perceber que está resolvendo o mesmo problema que já encontrou antes, apenas com nomes diferentes. Você percebe que, independentemente do contexto da aplicação, alguns desafios pertencem ao domínio da Engenharia de Software e são comuns a todas as aplicações. Padrões de projeto são como diagramas para resolver problemas específicos de design no seu código.

- [] *EN* refactoring.guru [What is a Design Pattern?](https://refactoring.guru/design-patterns/what-is-pattern)
- [ ] *PT* refactoring.guru [O que é um padrão de projeto](https://refactoring.guru/pt-br/design-patterns/what-is-pattern)
- [ ] *PT* Wikipedia [Padrão de projeto de software](https://pt.wikipedia.org/wiki/Padr%C3%A3o_de_projeto_de_software)
- [ ] *EN* Geeks for Geeks [Design Patterns Tutorial](https://www.geeksforgeeks.org/system-design/software-design-patterns/)

### Separation of Concerns
Ideally, every source code should be transferable and understandable in a reasonable time. You should be able to invite a new team member to your team and have them work on it. The Separation of Concerns principle breaks down the responsibility of each module so it can be more easily understood and maintained.

Idealmente, todo código-fonte deve ser transferível e compreendido em um tempo razoável. Você deve ser capaz de convidar um novo membro para sua equipe e permitir que ele trabalhe no projeto. O princípio da Separação de Responsabilidades divide a responsabilidade de cada módulo para que ele possa ser mais facilmente entendido e mantido.

- [ ] *PT* Blog Devmedia [Amadurecendo com Separation Of Concerns](https://www.devmedia.com.br/amadurecendo-com-separation-of-concerns/18699)
- [ ] *EN* Geeks for Geeks [Separation of Concerns (SoC)](https://www.geeksforgeeks.org/software-engineering/separation-of-concerns-soc/)


### Event-Driven Architecture
There are many thing-driven architectures, and they all share a purpose: to drive the evolution of your software with the same north, the "thing". I believe we should focus on the Event-Driven Architecture (EDA) because SAP's CAP is built ready to support it.

- [ ] *PT* RedHat [Arquitetura orientada a eventos?](https://www.redhat.com/pt-br/topics/integration/what-is-event-driven-architecture)
- [ ] *EN* SAP [What is event-driven architecture?](https://www.sap.com/croatia/resources/what-is-event-driven-architecture)

### SOLID
Wouldn't it be nice to have a few very general, but very accurate, guidelines to design software? By using SOLID principles, people have learned how to write software today that won't need to be completely rewritten tomorrow.

Não seria ótimo ter algumas diretrizes muito gerais, mas muito precisas, para projetar um software? Usando os princípios SOLID, as pessoas aprenderam a escrever software hoje que não precisará ser totalmente reescrito amanhã.

- [ ] *PT* Wikipedia [SOLID](https://pt.wikipedia.org/wiki/SOLID)
- [ ] *EN* PDF Source document [Design Principles and Design Patterns](https://objectmentor.com/resources/articles/Principles_and_Patterns.pdf)
- [ ] *EN* Blog CleanCoder [Solid Relevance](https://blog.cleancoder.com/uncle-bob/2020/10/18/Solid-Relevance.html)
- [ ] *PT* Blog [Entenda o SOLID de uma vez por todas e por que é tão importante!](https://medium.com/@gabrielfernandeslemos/entenda-o-solid-de-uma-vez-por-todas-e-por-que-%C3%A9-t%C3%A3o-importante-bfc967eeb6a9)

## Level 3
**Advanced software engineering**

Advanced concepts that impact the architecture of the software you're developing.

**Engenharia de software avançada**

Conceitos avançados que impactam na arquitetura do software que você está desenvolvendo.

### Algorithm Complexity
As Computer Scientists know, the best software in the world is not enough to beat a high complexity algorithm. Learn Big O notation and how to identify the complexity of the main algorithms.

Como os Cientistas da Computação sabem, o melhor software do mundo não é suficiente para vencer um algoritmo de alta complexidade. Aprenda a notação Big O e como identificar a complexidade dos principais algoritmos.
![Big-O Chart](big-o%20chart.png)

- [ ] *PT* Wikipedia [Complexidade Computacional](https://pt.wikipedia.org/wiki/Complexidade_computacional)
- [ ] *EN* Geeks for Geeks Tutorial [Complete Guide On Complexity Analysis - Data Structure and Algorithms Tutorial](https://www.geeksforgeeks.org/dsa/complete-guide-on-complexity-analysis/)
- [ ] *PT* Blog Iugu [Análise da Complexidade de Algoritmos](https://www.iugu.com/blog/analise-complexidade-algoritmos)
- [ ] *PT* Lapix [Complexidade de Algoritmos](https://lapix.ufsc.br/ensino/estrutura-de-dados/complexidade-de-algoritmos/)

- [ ] *EN* Big-O Cheat Sheet [Know Thy Complexities](https://www.bigocheatsheet.com/)

### Microservices
Larger applications in similar contexts share common features. Break down those features into distinct small (micro) services and share them across your applications.

Aplicações maiores em contextos semelhantes compartilham funcionalidades comuns. Separe essas funcionalidades em pequenos (micro) serviços distintos e compartilhe-os entre suas aplicações.

- [ ] *EN* microservices.io [What are microservices?](https://microservices.io/)
- [ ] *PT* AWS [Microsserviços](https://aws.amazon.com/pt/microservices/)
- [ ] *EN* Geeks for Geeks [Microservices](https://www.geeksforgeeks.org/system-design/microservices/)
- [ ] *EN* Martin Fowler [Microservices](https://martinfowler.com/articles/microservices.html)

### Observability
As systems become distributed, spreading across platforms and servers, how do you keep track if they're running fine? Many applications fail but don't stop, appearing falsely healthy. Learn how you can monitor the health of your applications by monitoring the data they produce: metrics, logs, and traces.

À medida que os sistemas se tornam distribuídos, espalhando-se por plataformas e servidores, como garantir que estão funcionando corretamente? Muitas aplicações falham, mas não param, aparentando estar saudáveis. Aprenda como monitorar a saúde das suas aplicações acompanhando os dados que elas produzem: métricas, logs e rastreamentos.

- [ ] *PT* IBM [O que é observabilidade?](https://www.ibm.com/br-pt/think/topics/observability)
- [ ] *PT* IBM [Engenharia de Observabilidade](https://www.ibm.com/br-pt/think/topics/observability-engineering)
- [ ] *EN* Blog Mia Platform [Observability in Software Engineering – Metrics, Logs, Traces](https://mia-platform.eu/blog/observability-software-engineering/)
- [ ] *EN* Dynatrace [The Developer's Guide to Observability](https://www.dynatrace.com/resources/ebooks/developers-guide-to-observability/)
- [ ] *PT* Instituto Eldorado [Observabilidade e Monitoramento: Conceitos e Aplicação](https://www.eldorado.org.br/blog/observabilidade-e-monitoramento-conceitos-e-aplicacao/)
