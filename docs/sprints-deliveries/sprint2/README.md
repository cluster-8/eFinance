# 🏁 Sprint 2

Below are all items produced during Sprint 2 as previously established through planning:

## 📑 Table of Contents

* [User Stories](https://github.com/cluster-8/eFinance#-user-stories)
* [Sprint backlog](https://github.com/cluster-8/eFinance#-sprint-backlog)
* [DoR](https://github.com/cluster-8/eFinance#-dor)
    * [Documentation](https://github.com/cluster-8/eFinance#-documentation)
    * [Database Modeling](https://github.com/cluster-8/eFinance#-database-modeling)
    * [Prototype](https://github.com/cluster-8/eFinance#-prototype)
* [DoD](https://github.com/cluster-8/eFinance#-dod)
* [Codes](https://github.com/cluster-8/eFinance#-codes)
* [Sprint Burndown](https://github.com/cluster-8/eFinance#-sprint-burndown)
* [Implemented Funcionalities](https://github.com/cluster-8/eFinance#-implemented-funcionalities)

## 👤 User Stories

The table below shows selected **User Stories** to be developed during Sprint 2:

| ID    | Priority | User Story                                                                                           | Funcionalities                                                                                                       |
| ----- | ---------- | ---------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------- |
| US_02 | Essential | As a user, I would like to view a Financial Instituitions Rank. | 1. When selecting the type of service and type of rank (higher or lower tariffs based on it mean value), the application must present the Financial Instituitions Rank. By default, the selected service type will be "All"; |
| US_03 | Desirable | As a user, I would like to view the Top 5 Financial Instituitions by Service. | 1. When selecting the type of service, the application must present the services that matches selected type, when selecting the service, the application must present the top 5 financial instituitions with lower tariffs for the selected service, when selecting the final date, the application must present the top 5 financial instituitions until that date. By default, the selected date will be the current date and the service type will be "All"; |

## 📝 Sprint Backlog

The image below shows the [**Product Backlog**](https://github.com/cluster-8/eFinance/blob/main/docs/v02_ad2_eFinance_-_Product_Backlog.pdf) items in order of priority referring to Sprint 2:

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/user-stories-sprint2.jpeg)

## 📜 DoR (Definition of Ready)

### 📂 Documentation

* [Product Backlog access link](https://github.com/cluster-8/eFinance/blob/main/docs/)

### 🎲 Database Modeling

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/database-model-sprint-2.png)

### 🖥️ Prototype

* [Prototype access link](https://www.figma.com/proto/NomgcHgPjuGxlI8yZCOrYx/API-6?node-id=225-2&scaling=min-zoom&page-id=0%3A1)


## 📜 DoD (Definition of Done)

* **US02 - Financial Instituitions Rank**

    * Application must present a rank of financial instituitions based on score (tariffs mean) by service type and rank type, lowest or highest values selected by user.

* **US03 - Top 5 Lowest Rates**

    * Application must present a top 5 lowest rates financial instituitions by service and date selected by user.

## 📃 Codes

### Frontend

* [Repository](https://github.com/cluster-8/eFinance-front)
* [Release v1.1.0]()

### Backend

* [Repository](https://github.com/cluster-8/eFinance-api)
* [Release v1.1.0]()

### Open Data Scrapper

* [Repository](https://github.com/cluster-8/eFinance-odata-scrapper)
* [Release v1.1.0]()

<!-- ## 📉 Sprint Burndown

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/) -->

## 💫 Implemented Funcionalities

### 🏆 Financial Instituitions Rank

#### 🧑‍💼 Higher and Lower Tariffs Rank for Physical Services

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/maiores-menores-pf.gif)

#### 🏢 Higher and Lower Tariffs Rank for Juridical Services

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/maiores-menores-pj.gif)

#### 🧑‍💼 🏢 Higher and Lower Tariffs Rank for All Services

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/maiores-menores-todos.gif)

### 🥇 Top 5 Financial Instituitions by Service

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/top5.gif)

### 💎 Improvements on Service Fee Panel

* Addition of Minimum Value

* Addition of ilustrative image for no data displayed cases

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/melhorias-sprint2.gif)
