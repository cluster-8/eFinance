# 🏁 Sprint 3

Below are all items produced during Sprint 3 as previously established through planning:

## 📑 Table of Contents

- [User Stories](https://github.com/cluster-8/eFinance#-user-stories)
- [Sprint backlog](https://github.com/cluster-8/eFinance#-sprint-backlog)
- [DoR](https://github.com/cluster-8/eFinance#-dor)
  - [Documentation](https://github.com/cluster-8/eFinance#-documentation)
  - [Database Modeling](https://github.com/cluster-8/eFinance#-database-modeling)
  - [Prototype](https://github.com/cluster-8/eFinance#-prototype)
- [DoD](https://github.com/cluster-8/eFinance#-dod)
- [Codes](https://github.com/cluster-8/eFinance#-codes)
- [Sprint Burndown](https://github.com/cluster-8/eFinance#-sprint-burndown)
- [Implemented Funcionalities](https://github.com/cluster-8/eFinance#-implemented-funcionalities)

## 👤 User Stories

The table below shows selected **User Stories** to be developed during Sprint 3:

| ID    | Priority  | User Story                                                                          | Funcionalities                                                                                                                                                                                                     |
| ----- | --------- | ----------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| US_04 | Important | As a user, I would like to view and compare a certain selected service fee by bank. | 1. When selecting a service, the user must then select the financial institutions to be compared. The user can select more than one service to compare, but can only select two financial institutions at a time.; |

## 📝 Sprint Backlog

The image below shows the [**Product Backlog**](https://github.com/cluster-8/eFinance/blob/main/docs/v03_dbf_eFinance_-_Product_Backlog.pdf) items in order of priority referring to Sprint 3:

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/user-stories-sprint3.jpeg)

## 📜 DoR (Definition of Ready)

### 📂 Documentation

- [Product Backlog access link](https://github.com/cluster-8/eFinance/blob/main/docs/v03_dbf_eFinance_-_Product_Backlog.pdf)

### 🎲 Database Modeling

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/database-model-sprint-2.png)

### 🖥️ Prototype

- [Prototype access link](https://www.figma.com/proto/NomgcHgPjuGxlI8yZCOrYx/API-6?node-id=225-2&scaling=min-zoom&page-id=0%3A1)

## 📜 DoD (Definition of Done)

- **US04 - Fare Comparison**

  - Application must present a service fee comparator for two selected financial institutions. When there are no service fees for one or more selected institutions, the application must inform the user.

## 📃 Codes

### Frontend

- [Repository](https://github.com/cluster-8/eFinance-front)
- [Release v1.2.0](https://github.com/cluster-8/eFinance-front/releases/tag/v1.2.0)

### Backend

- [Repository](https://github.com/cluster-8/eFinance-api)
- [Release v1.2.0](https://github.com/cluster-8/eFinance-api/releases/tag/v1.2.0)

### Open Data Scrapper

- [Repository](https://github.com/cluster-8/eFinance-odata-scrapper)
- [Release v1.2.0](https://github.com/cluster-8/eFinance-odata-scrapper/releases/tag/v1.2.0)

### Machine Learning Model

- [Repository](https://github.com/cluster-8/eFinance-ml-model)
- [Release v1.0.0](https://github.com/cluster-8/eFinance-ml-model/releases/tag/v1.0.0)

## 📉 Sprint Burndown

[Burndown access link](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/sprint-3-burndown.jpeg)

## 💫 Implemented Funcionalities

### 📊 Fare Comparison

![](https://github.com/cluster-8/eFinance/blob/main/docs/gifs/comparator.gif)

### 🤖 Preliminar Machine Learning model for Service fee Forecasting

[Code access link](https://github.com/cluster-8/eFinance-ml-model)

#### Raw data

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/raw-data.png)

#### Training, validation and testing data

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/train-val-test-data.png)

#### Training Predictions

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/train-predictions.png)

#### Validation Predictions

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/validation-predictions.png)

#### Testing Predictions

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/testing-predictions.png)

#### Training, validations and testing results

![](https://github.com/cluster-8/eFinance/blob/main/docs/imgs/train-val-test-results.png)