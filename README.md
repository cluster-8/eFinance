# eFinance

## 📑 Table of Content

* [Application Overview](https://github.com/cluster-8/eFinance#-application-overview)
* [Challenge](https://github.com/cluster-8/eFinance#-challenge)
* [Project](https://github.com/cluster-8/eFinance#-project)
* [Planning](https://github.com/cluster-8/eFinance#-planning)
* [Prioritized User Stories](https://github.com/cluster-8/eFinance#-prioritized-user-stories)
* [Sprints Deliveries](https://github.com/cluster-8/eFinance#-sprints-deliveries)
* [Product Backlog](https://github.com/cluster-8/eFinance#-product-backlog)
* [Prototype](https://github.com/cluster-8/eFinance#-prototype)
* [Codes](https://github.com/cluster-8/eFinance#-codes)
* [Technologies](https://github.com/cluster-8/eFinance#-technologies)
* [Team](https://github.com/cluster-8/eFinance#-team)

## Application Overview

### 🪙 Service Fee Panel

When selecting the financial institution and the type of service, the application presents the services and their respectives prices. By default, the selected type will be for Individuals;

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/melhorias-sprint2.gif)

#### 🧑‍💼 Higher and Lower Tariffs Rank for Physical Services

When selecting the type of service and type of rank (higher or lower tariffs based on it mean value), the application presents the Financial Instituitions Rank. By default, the selected service type will be "All"

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/maiores-menores-pf.gif)

#### 🏢 Higher and Lower Tariffs Rank for Juridical Services

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/maiores-menores-pj.gif)

#### 🧑‍💼 🏢 Higher and Lower Tariffs Rank for All Services

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/maiores-menores-todos.gif)

### 🥇 Top 5 Financial Instituitions by Service

When selecting the type of service, the application presents the services that matches selected type, when selecting the service, the application presents the top 5 financial instituitions with lower tariffs for the selected service, when selecting the final date, the application presents the top 5 financial instituitions until that date. By default, the selected date will be the current date and the service type will be "All"

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/top5.gif)

### 📊 Fare Comparison

When selecting a service, the user must then select the financial institutions to be compared. The user can select more than one service to compare, but can only select two financial institutions at a time.

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/comparator.gif)

### 🤖 History Tariff Variation and Trend

The user selects the institution and the service to be viewed, the application displays a time series graph with the variation in the fee value with a trend calculated by the prediction model.

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/history-variation-and-prediction.gif)

## 📌 Challenge

Since 2020, the Central Bank of Brazil has been working to establish a new form of intercommunication between banks, companies and customers; the platform named Open Finance Brasil. Traditionally, banks have always been huge vaults when it comes to storing their customers' data, and now there is a new paradigm that will generate infinite possibilities for integration and the creation of new products and services. As a way of analyzing the amounts charged for various services among Open Finance participants, we have the challenge of presenting, in an intuitive and fluid way, a price comparison tool using the data provided through Open Finance.

## 🏁 Project

**eFinance** is a web platform for monitoring fees for services and products offered by Brazilian financial institutions through open data made available by them and by the National Financial System.

At the end of development, the platform should have the following features:

* **Service Fee Panel**: view of service fees offered by a selected institution.

* **Ranking of Financial Institutions**: visualization of the classification of financial institutions according to the value of the selected service fee.

* **Top 5 Lowest Rates**: view of the ranking of the five institutions with the lowest rates for a selected service.

* **Fare Comparison**: visualization of the comparison of tariffs between the selected financial institutions.

* **History of Tariff Variation and Trend**: visualization of the selected tariff variation over a period and with a trend line.

## 📅 Planning

| Sprints               |                   Deliverables                    |          Date           | Status      | Access Link       |
| :-------------------: | :-----------------------------------------------: | :---------------------: | :--------:  | :---------------: |
|   `Kik-off`           | Knowing the challenge                             | 02/13/2023 a 03/03/2023 | ✅          | 🚩                |
|   `Sprint 1`          | US01 - Service Fee Panel                          | 03/13/2023 a 04/02/2023 | ✅          | [🔗 Click here](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint1)       |
|   `Sprint 2`          | US02 - Ranking of Financial Instituitions e US03 - Top 5 Lowest Rates | 04/03/2023 a 04/23/2023 | ✅     | [🔗 Click here](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint2) |    
|   `Sprint 3`          | US04 - Fare Comparison                            | 04/24/2023 a 05/14/2023 | ✅          | [🔗 Click here](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint3)       |
|   `Sprint 4`          | US05 - History of Tariff Variation and Trend      | 05/15/2023 a 06/04/2023 | ✅          | [🔗 Click here](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint4)                |
|   `Solution Fair`     | Demonstration of results                          | 06/13/2023 a 06/14/2023 | 🚧          | 🔒                |

## 🏅 Prioritized User Stories

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/prioritized-user-stories.jpeg)

## 🎁 Sprints Deliveries

Access the items delivered in each stage of project development:

### Sprint 1

* [US01 - Service Fee Panel](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint1)

### Sprint 2

* [US02 - Ranking of Financial Instituitions](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint2)

* [US03 - Top 5 Financial Instituitions](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint2)


### Sprint 3

* [US04 - Fare Comparison](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint3)

* [Preliminar Prediction Machine Learning Model](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint3)

### Sprint 4

* [US05 - History of Tariff Variation and Trend](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint4)

* [Log System](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint4)

* [Application Metrics](https://github.com/cluster-8/eFinance/tree/main/docs/sprints-deliveries/sprint4)

## 📃 Product Backlog

* [PDF Document access link](https://github.com/cluster-8/eFinance/blob/main/docs/v03_dbf_eFinance_-_Product_Backlog.pdf)

## 💻 Prototype

* [Figma Prototype access link](https://www.figma.com/proto/NomgcHgPjuGxlI8yZCOrYx/API-6?node-id=225-2&scaling=min-zoom&page-id=0%3A1)

## 📃 Codes

* [Frontend Code access link](https://github.com/cluster-8/eFinance-front)
* [Backend Code access link](https://github.com/cluster-8/eFinance-api)
* [OpenData Scrapper Code access link](https://github.com/cluster-8/eFinance-odata-scrapper)
* [Machine Learning Model Code access link](https://github.com/cluster-8/eFinance-ml-model)

## 🎁 Latest releases

* [eFinance-front-v1.3.0](https://github.com/cluster-8/eFinance-front/releases/tag/v1.3.0)

* [eFinance-api-v1.3.0](https://github.com/cluster-8/eFinance-api/releases/tag/v1.3.0)

* [eFinance-odata-scrapper-v1.3.0](https://github.com/cluster-8/eFinance-odata-scrapper/releases/tag/v1.3.0)

* [eFinance-ml-model-v1.1.0](https://github.com/cluster-8/eFinance-ml-model/releases/tag/v1.1.0)

## 🛠 Technologies

For the construction of the web application, the following technologies are being used:

<img src="https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D">
<img src="https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E">
<img src="https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=java&logoColor=white">
<img src="https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white">
<img src="https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue">
<img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white">

For the construction of the machine learning model

<img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=for-the-badge&logo=Keras&logoColor=white">
<img src="https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=TensorFlow&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
  
## 👨‍💻 Team

| Student              | Function             | GitHub Profile                                                              | LinkedIn Profile                                                                                         |
| --------------------- | ------------------ | ------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------- |                               
| **Eduarda Giudice**           | _Scrum Master_     | [![](https://bit.ly/3f9Xo0P)](https://github.com/EduardaGiudice)    | ![](https://bit.ly/2P1ZogM)     |
| **Guilherme Garcia**         | _Developer Team_   | [![](https://bit.ly/3f9Xo0P)](https://github.com/guilherme4garcia) | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/guilherme-garcia-dev?original_referer=https%3A%2F%2Fgithub.com%2F) |
| **Hariel Thums**      | _Developer Team_ | [![](https://bit.ly/3f9Xo0P)](https://github.com/HarielThums)       | [![](https://bit.ly/2P1ZogM)](https://bit.ly/3f9bjUH)                                             |
| **Matheus Emboaba**      | _Developer Team_ | [![](https://bit.ly/3f9Xo0P)](https://github.com/MatheusEmboabaTeteu)       | [![](https://bit.ly/2P1ZogM)](https://www.linkedin.com/in/matheus-emboaba-a21970236)                                             |
| **Vinícius Oliveira** | _Product Owner_    | [![](https://bit.ly/3f9Xo0P)](https://github.com/vinicius-hso)      | [![](https://bit.ly/2P1ZogM)](https://bit.ly/3fdl0BE)                                             |
