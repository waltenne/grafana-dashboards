# QUALITOR DASHBOARD

<div> 
  <a href="https://github.com/waltenne" target="_blank"><img src="https://img.shields.io/badge/Grafana-F6DDCC?style=for-the-badge&logo=Grafana&logoColor=E67E22" target="_blank"></a> 
</div>

Este **Dashboard** realiza a consulta no banco de dados do Qualitor para retornar alguns valores estratégicos utilizando o filtro de data do Grafana.

This **Dashboard** performs database query into Qualitor Data Base to return strategic data using time filter of Grafana.

#### A Versão 2.0 do dashboard foi separado nas seguintes ROWS para organização

* [**GERAL**](#GENERAL/GERAL)
* [**IMPLANTACAO**](#IMPLEMENTATION/IMPLEMENTAÇÃO)
* [**AVALIAÇÔES**](#RATING/AVALIAÇÔES)
* [**CATEGORIAS**](#CATEGORY/CATEGORIAS)
* [**RANKING**](#RANKING)
* [**SUSPENSOS**](#RANKING/SUSPENDED)

#### Version 2.0 of the dashboard has been separated into the following ROWS for organization

* [**GENERAL**](#GENERAL/GERAL)
* [**IMPLEMENTATION**](#IMPLEMENTATION/IMPLEMENTAÇÃO)
* [**RATING**](#RATING/AVALIAÇÔES)
* [**CATEGORY**](#CATEGORY/CATEGORIAS)
* [**RANKING**](#RANKING)
* [**SUSPENDED**](#RANKING/SUSPENDED)
## **Visão Geral / General View**

![main](./screenshots/main.png)

### **GENERAL / GERAL**

 Será apresentados os dados atuais por quantidade de Tickets nas seguintes categorias:

  * EM ATENDIMENTO
  * CANCELADOS
  * ATRASADOS
  * SUSPENSOS
  * AGUARDANDO ATENDIMENTO
  * ENCERRADOS
  * ABERTOS COM ITERAÇÂO

Will present the current data by number of Tickets in the following categories:

  * IN SERVICE
  * CANCELED
  * DELAYED
  * SUSPENDED
  * WAITING FOR SERVICE
  * CLOSED
  * OPEN WITH ITERATION

![main](./screenshots/general.png)

### **IMPLEMENTATION / IMPLANTAÇÂO**

 Será apresentados os dados das implantações divididos em:

  * ENCERRADOS
  * CATEGORIA
  * EM ATENDIMENTO

Current deployment data will be presented divided into:

  * CLOSED
  * CATEGORY
  * IN SERVICE

![main](./screenshots/implementation.png)

### **RATING / AVALIAÇÔES**

 Será apresentados os das avaliações divididos em:

 Tanto como para tickets normais e para abertos via chat e seu detalhamento por quantidade divididos pela sua categoria

  * AVALIADOS
  * NÂO AVALIADOS

Current evaluation data will be presented, divided into:

 As for normal tickets and for open tickets via chat and their breakdown by quantity divided by their category

  * ASSESSED
  * NOT ASSESSED

![main](./screenshots/rating.png)


### **CATEGORY / CATEGORIAS**

 Será apresentados os dados das categorias divididos em:

 Tanto como para tickets normais e para abertos via chat e seu detalhamento por quantidade divididos pela sua categoria

  * AVALIADOS
  * NÂO AVALIADOS

Current category data will be presented, divided into:

 As for normal tickets and for open tickets via chat and their breakdown by quantity divided by their category

  * ASSESSED
  * NOT ASSESSED

![main](./screenshots/category-1.png)
![main](./screenshots/category-2.png)

### **RANKING**

 Será apresentados os dados de ranking:

  * TOP 10 EMPRESAS POR QUANTIDADE
  * TOP CATEGORIAS DE TICKET

Ranking data will be displayed:

  * TOP 10 COMPANIES BY AMOUNT
  * TOP TICKET CATEGORIES


![main](./screenshots/ranking.png)

### **SUSPENDED / SUSPENSOS**

 Será apresentados os dados dos chamados suspensos em uma tabela, pegando o número da atividade (REDMINE) inserida no titulo do chamado começando com #

The suspended ticket data will be presented in a table, taking the activity number (REDMINE) inserted in the ticket title starting with #


![main](./screenshots/suspended.png)