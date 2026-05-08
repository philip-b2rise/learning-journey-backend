# SAP

| [Level 1](#level-1) <br> Nível 1 <br> Fundamentos e conceitos essenciais para iniciar a jornada | [Level 2](#level-2) <br> Nível 2 <br> Especialização e domínio intermediário das tecnologias | [Level 3](#level-3) <br> Nível 3 <br> Conceitos avançados, visão de arquitetura e inovações |
|----|----|----|
| [SAP](#sap-erp) | [S/4HANA (and ECC)](#s4hana-and-ecc) | [SAP T-Codes](#sap-t-codes) |
| [SAP BTP](#sap-btp) | [SAP Cloud ERP](#sap-cloud-erp) | [Integration Suite (CPI)](#integration-suite-cpi) |
| [BTP Services](#btp-services) | [Job Scheduler](#job-scheduler) | [Official Documentation (help.sap.com)](#official-documentation-helpsapcom) |
| [Cloud Foundry](#cloud-foundry)| [HANA](#hana) | [SAP for me](#sap-for-me) |
| [Work Zone (Standard)](#work-zone-standard) | [Kyma](#kyma) | |
| [Clean Core](#clean-core) | [HTML5 App Repository](#html5-app-repository) | |

## Level 1
**What are SAP and BTP?**

First, understand what an ERP and a Cloud Platform are. Then, learn about the SAP environment and how BTP complements S/4HANA.

**O que são SAP e BTP?**

Primeiro, entenda o que é um ERP e uma Plataforma em Nuvem. Depois, aprenda sobre o ambiente SAP e como o BTP complementa o S/4HANA.

### SAP (ERP)
Learn what Enterprise Resource Planning (ERP) software is and how it is generally organized. Explore the main SAP modules to understand what information they managed.

Saiba o que é um software de Planejamento de Recursos Empresariais (ERP) e como ele é geralmente organizado. Explore os principais módulos do SAP para entender quais informações eles gerenciam.

- [ ] *PT* Playlist Youtube KA Solution [SAP em 5 minutos](https://www.youtube.com/playlist?list=PLvOO1q9F-HhWjbrVZ0CZSTjy9S2HETimW)
- [ ] *PT* SAP [O que é SAP?](https://www.sap.com/brazil/about/what-is-sap.html)
- [ ] *PT* SAP [O que é ERP?](https://www.sap.com/brazil/resources/what-is-erp)
- [ ] *EN* Blog [Top SAP Modules For Freshers: Which SAP Module Should You Learn First?](https://infycletechnologies.com/top-sap-modules-for-freshers-which-sap-module-should-you-learn-first/)
- [ ] *EN* Blog [An Overview of the Most Important SAP Modules](https://ecosio.com/en/blog/an-overview-of-the-most-important-sap-erp-modules/)

### SAP BTP
A Cloud Platform must be able to support its applications by either providing the resources and services they need or enabling access to external service providers. SAP's own take on this is called SAP Business Technology Platform, because it provides the resources and services a business needs.

Uma Plataforma em Nuvem deve ser capaz de suportar suas aplicações, seja fornecendo os recursos e serviços de que elas precisam, seja permitindo o acesso a provedores de serviços externos. A solução da SAP para isso é chamada de SAP Business Technology Platform, pois oferece os recursos e serviços necessários para um negócio.

- [ ] *PT* Moovi [SAP BTP Essentials](https://moovi.curseduca.pro/m/lessons/sap-btp-essentials-1742323798510)
- [ ] *PT* SAP [SAP Business Technology Platform](https://www.sap.com/brazil/products/technology-platform.html)
- [ ] *EN* Course learning.sap [Becoming an SAP BTP Solution Architect](https://learning.sap.com/courses/becoming-an-sap-btp-solution-architect/)

### BTP Services
There are dozens of services available in BTP. First, understand that any resource your application needs is called a service: you don't own it, but you have access to it. Then, learn the basics about the main services that you'll use:

Existem dezenas de serviços disponíveis no BTP. Primeiro, entenda que qualquer recurso que sua aplicação precise é chamado de serviço: você não é o proprietário, mas tem acesso a ele. Depois, aprenda o básico sobre os principais serviços que você irá utilizar:

```
Authorization and Trust Management Service
Cloud Foundry Runtime
Destination Service
Connectivity Service
SAP HANA Cloud
SAP Build Workzone, standard edition
HTML5 Application Repository Service
```

And have at least a notion of what these services do:

E tenha pelo menos uma noção do que estes serviços fazem:
```
Business Application Studio
Job Scheduling Service
Event Mesh
Kyma Runtime
Integration Suite
PosgreSQL, Hyperscaler Option
```

- [ ] *EN* SAP Discovery Center [SAP BTP Services](https://discovery-center.cloud.sap/viewServices?solution=foundation/crossservices)
- [ ] *PT* Blog AlfaERP [Funcionalidades e recursos do SAP BTP](https://alfaerp.com.br/blog/sap-btp-sap-business-technology-platform/#elementor-toc__heading-anchor-1)

### Cloud Foundry
Cloud Foundry is the main runtime of SAP BTP. It enables quick and efficient deployment of applications, easily managing startup, restart, shutdown, scaling, and integration with platform services.

Cloud Foundry é o principal runtime do SAP BTP. Ele permite a implantação rápida e eficiente de aplicações, gerenciando facilmente inicialização, reinicialização, desligamento, escalabilidade e integração com os serviços da plataforma.

- [ ] *EN* cloudfoundr.oth [Cloud Foundry Introduction](https://tutorials.cloudfoundry.org/cf4devs/introduction/)
- [ ] *EN* learning.sap [Developing Applications for SAP BTP, Cloud Foundry runtime](https://learning.sap.com/courses/developing-applications-for-sap-btp-cloud-foundry-runtime)
- [ ] *PT* Red Hat [O que é o Cloud Foundry?](https://www.redhat.com/pt-br/topics/application-modernization/what-is-cloud-foundry)

### Work Zone (Standard)
The [Fiori](https://www.sap.com/design-system/fiori-design-web/v1-145/discover/get-started) design is present everywhere in modern SAP technologies. One of its core features is the standard [Launchpad](https://www.sap.com/design-system/fiori-design-web/v1-145/foundations/integration-and-services/sap-fiori-launchpad/launchpad), which has now evolved and is called Work Zone.

O design Fiori está presente em todas as tecnologias modernas da SAP. Um de seus principais recursos é o Launchpad padrão, que agora evoluiu e se chama Work Zone.

- [ ] *PT* Moovi [SAP Build Workzone](https://moovi.curseduca.pro/m/lessons/sap-build-workzone-1753803811834)
- [ ] *EN* SAP Discovery Center [SAP Build Work Zone, standard edition](https://discovery-center.cloud.sap/serviceCatalog/sap-build-work-zone-standard-edition)
- [ ] *EN* Tutorial developers.sap [Create a Business Site Using SAP Build Work Zone, standard edition, and Add Applications and UI5 Cards to It](https://developers.sap.com/mission.launchpad-cf.html)
- [ ] *EN* help.sap [What Is SAP Build Work Zone, standard edition?](https://help.sap.com/docs/build-work-zone-standard-edition/sap-build-work-zone-standard-edition/what-is-sap-build-work-zone-standard-edition?locale=en-US)
- [ ] *PT* help.sap [O que é SAP Build Work Zone, standard edition?](https://help.sap.com/docs/build-work-zone-standard-edition/sap-build-work-zone-standard-edition/what-is-sap-build-work-zone-standard-edition?locale=pt-BR)

### Clean Core
What is the Core and why do we want to keep it Clean? As companies realized, adding customizations to their SAP systems came with a cost when evolving and maintaining them. SAP's guideline is to keep SAP's core functionality as standard as possible, so it can evolve more easily and not disrupt any additional features added by the customer.

O que é o Core e por que queremos mantê-lo Clean? As empresas perceberam que adicionar customizações aos seus sistemas SAP trazia um custo na hora de evoluir e manter esses sistemas. A orientação da SAP é manter a funcionalidade central (core) do SAP o mais padrão possível, para que ela possa evoluir mais facilmente e não prejudique recursos adicionais implementados pelo cliente.

- [ ] *PT* SAP [O que é clean core?](https://www.sap.com/brazil/resources/what-is-a-clean-core)
- [ ] *EN* blogs.sap **ABCD Tiers** [ABAP Extensibility Guide](https://community.sap.com/t5/technology-blog-posts-by-sap/abap-extensibility-guide-clean-core-for-sap-s-4hana-cloud-august-2025/ba-p/14175399)
- [ ] *EN* learning.sap [Practicing Clean Core Extensibility for SAP S/4HANA Cloud](https://learning.sap.com/courses/practicing-clean-core-extensibility-for-sap-s-4hana-cloud/)

## Level 2
**S/4HANA and More BTP**
You now know the basics of SAP and BTP. It's time to dive deeper and learn how SAP's technology has evolved over the years, because many customers are stuck in the past and need your help to get up to date with the latest technologies.

Você já conhece o básico de SAP e BTP. Agora é hora de se aprofundar e aprender como a tecnologia SAP evoluiu ao longo dos anos, pois muitos clientes ainda estão presos ao passado e precisam da sua ajuda para se atualizar com as tecnologias mais recentes.

### S/4HANA (and ECC)
What we generally call SAP has come a long way from R/2, R/3, ECC, to S/4HANA. It started as a purely German software and now it's an international (default English) one. Due to the memory limits of its time, it has many field size limits and acronyms to reduce consumption, which have remained. Learn how SAP evolved the legacy into modern software.

O que geralmente chamamos de SAP percorreu um longo caminho desde o R/2, R/3, ECC até o S/4HANA. Começou como um software puramente alemão e hoje é internacional (padrão em inglês). Devido às limitações de memória da época, possui muitos limites de tamanho de campo e siglas para reduzir o consumo, que permanecem até hoje. Entenda como a SAP evoluiu o legado para um software moderno.

- [ ] *PT* Moovi [SAP S/4HANA Essentials](https://moovi.curseduca.pro/m/lessons/s-4hana-para-funcionais-copia-2025-03-06-15-16-53?moduleId=626)
- [ ] *EN* Blog SAP LeanIX [SAP ECC, HANA, R/3, and S/4HANA](https://www.leanix.net/en/wiki/tech-transformation/sap-ecc-vs-hana-vs-r3-vs-s4hana)
- [ ] *PT* Blog [SAP ECC vs S/4HANA: entenda as principais diferenças entre os dois sistemas](https://freirecruz.com/aprenda-as-principais-diferencas-do-sap-ecc-para-o-sap-s-4hana/)
- [ ] *EN* Blog SAP Press [An Overview of the SAP S/4HANA VDM](https://blog.sap-press.com/an-overview-of-the-sap-s4hana-vdm)

### SAP Cloud ERP
The final evolution of the SAP ERP is the SAP Cloud ERP. It is a highly standardized software that is updated frequently and automatically. Initially, it struggled because it was not ready to meet customers' custom needs, but over the years it has improved and become more open to extensions (in a controlled manner).

A evolução final do SAP ERP é o SAP Cloud ERP. É um software altamente padronizado, atualizado com frequência e de forma automática. No início, enfrentou dificuldades porque não estava pronto para atender às necessidades personalizadas dos clientes, mas ao longo dos anos melhorou e se tornou mais aberto a extensões (de forma controlada).

- [ ] *PT* SAP [SAP Cloud ERP (anteriormente, SAP S/4HANA Cloud Public Edition)](https://www.sap.com/brazil/products/erp/s4hana.html)
- [ ] *EN* blogs.sap 2022 [Difference between SAP S/4HANA :Public Vs Private edition : RISE with SAP](https://community.sap.com/t5/technology-blog-posts-by-members/difference-between-sap-s-4hana-public-vs-private-edition-rise-with-sap/ba-p/13546250)
- [ ] *PT* Blog Delaware [SAP S/4HANA Cloud: Private vs. Public](https://www.delaware.pro/pt-br/blogs/sap-s4hana-cloud-public-vs-private)

### Job Scheduler
Whenever you need to trigger your application periodically, the Job Scheduling Service is your first option.

Sempre que você precisar acionar sua aplicação periodicamente, o Job Scheduling Service é sua primeira opção.

- [ ] *EN* SAP Discovery Center [SAP Job Scheduling Service](https://discovery-center.cloud.sap/serviceCatalog/job-scheduling-service?region=all)
- [ ] *EN* help.sap [What is Job Scheduling Service?](https://help.sap.com/docs/job-scheduling/sap-job-scheduling-service/rest-apis?locale=en-US)
- [ ] *PT* help.sap [O que é o serviço SAP Job Scheduling?](https://help.sap.com/docs/job-scheduling/sap-job-scheduling-service/what-is-sap-job-scheduling-service?locale=pt-BR)

### HANA
SAP HANA is not only SAP's proprietary database, but also a powerful in-memory database. It stands out from traditional databases due to its speed and analytical capabilities, enabled by storing and working with data in memory rather than on disk. Eventually, it made its way to the cloud into SAP BTP and it's now called SAP HANA Cloud.

O SAP HANA não é apenas o banco de dados proprietário da SAP, mas também um poderoso banco de dados em memória. Ele se destaca dos bancos de dados tradicionais devido à sua velocidade e capacidades analíticas, possibilitadas pelo armazenamento e trabalho dos dados em memória, ao invés de em disco. Finalmente, ele chegou à nuvem no SAP BTP e agora é chamado de SAP HANA Cloud.

- [ ] *PT* SAP [HANA](https://www.sap.com/brazil/products/data-cloud/hana/what-is-sap-hana.html)
- [ ] *EN* SAP Press [Learning SAP HANA](https://learning.sap-press.com/sap-hana)
- [ ] *EN* SAP Discovery Center[SAP HANA Cloud](https://discovery-center.cloud.sap/serviceCatalog/sap-hana-cloud)
- [ ] *EN* help.sap [SAP HANA Cloud Getting Started Guide](https://help.sap.com/docs/hana-cloud/sap-hana-cloud-getting-started-guide/sap-hana-cloud-and-sap-business-technology-platform-sap-btp?locale=en-US)
- [ ] *PT* help.sap [Guia de introdução do SAP HANA Cloud](https://help.sap.com/docs/hana-cloud/sap-hana-cloud-getting-started-guide/sap-hana-cloud-and-sap-business-technology-platform-sap-btp?locale=pt-BR)

### Kyma
In order to keep up with the latest technologies in the market for application development (and especially DevOps), SAP has chosen the open-source project [Kyma](https://kyma-project.io/) as its managed [Kubernetes](https://kubernetes.io/) runtime.

Para acompanhar as tecnologias mais recentes do mercado de desenvolvimento de aplicações (e especialmente DevOps), a SAP escolheu o projeto open-source Kyma como seu runtime gerenciado de Kubernetes.

- [ ] *EN* kyma-project.io [What is Kyma?](https://kyma-project.io/README.html)
- [ ] *EN* help.sap [Kyma Environment](https://help.sap.com/docs/btp/sap-business-technology-platform/kyma-environment?locale=en-US)
- [ ] *PT* help.sap [Ambiente Kyma](https://help.sap.com/docs/btp/sap-business-technology-platform/kyma-environment?locale=pt-BR)

### HTML5 App Repository
Static resources such as web pages (HTML) can be stored and managed separately from your applications. The HTML5 App Repository allows you to decouple your app from its UI, resulting in easier maintenance.

Recursos estáticos, como páginas web (HTML), podem ser armazenados e gerenciados separadamente das suas aplicações. O HTML5 App Repository permite desacoplar sua aplicação da interface do usuário, facilitando a manutenção.

- [ ] *EN* SAP Discovery Center [SAP HTML5 Application Repository Service for SAP BTP](https://discovery-center.cloud.sap/serviceCatalog/html5-application-repository-service)
- [ ] *EN* help.sap [Developing HTML5 Applications in the Cloud Foundry Environment](https://help.sap.com/docs/btp/sap-business-technology-platform/developing-html5-applications-in-cloud-foundry-environment?locale=en-US)
- [ ] *PT* help.sap [Desenvolvimento de aplicações HTML5 no ambiente Cloud Foundry](https://help.sap.com/docs/btp/sap-business-technology-platform/developing-html5-applications-in-cloud-foundry-environment?version=Cloud&locale=pt-BR&state=PRODUCTION)

## Level 3
**Further SAP Services and Resources**

### SAP T-Codes

- [ ] *EN* List NAV IT [SAP ABAP transaction codes list – A Comprehensive Guide](https://nav-it.com/sap-abap-transaction-codes-list-a-comprehensive-guide/)
- [ ] *EN* List Pathlock [List of (T-Codes) Transaction Codes in SAP ABAP](https://pathlock.com/blog/transaction-codes-in-sap-abap/)

### Integration Suite (CPI)
### SAP for me
### Official Documentation (help.sap.com)
