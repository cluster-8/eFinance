# Aprendizagem por Projetos Integrados 2023-1

## Tema

Sistema para acompanhamento de serviços utilizando Análise de Dados com perfis de usuários bem definidos

## Conhecimento exigidos

* Implementar Aplicaçãp usando SpringBoot e características técnicas mais avançadas
* Implementar FrontEnd SPA (Single Page Application) com Vue.js
* Desenvolver aplicação em Machine Learning, com base no modelo CRISP, utilizando paradigma Supervisionado ou Não Supervisionado

## Desafio

Desde de 2020, o Banco Central do Brasil vem trabalhando para estabelecer uma nova forma de intercomunicação entre bancos, empresas e clientes; a plataforma batizada de Open Finance Brasil.Tradicionalmente,   os   bancos   sempre   foram   enormes   caixas-fortes   quando   se   tratam   do armazenamento dos dados de  seus clientes e, agora, há um novo paradigma que  gerará infinitas possibilidades de integrações e criação de novos produtos e serviços. Como forma de analisar os valores cobrados por diversos serviços entre os participantes do Open Finance, temos o desafio de apresentar de forma intuitiva e fluida, uma ferramenta de comparação de preços utilizando os dados fornecido através do Open Finance.

## Requisitos iniciais

### Requisitos Funcionais

* Desenvolver um **painel de tarifas de produtos/serviços**: 
    
    * Banco
    * Produto/Serviço
    * Moeda
    * Tarifa
    * Faixa
    * Taxa

* Desenvolver um **dashboard de rankings**: 
    
    * Banco com menores, maiores tarifas; 
    * Linha do tempo da média de uma tarifa com tendência; 
    * Top 5 bancos com menores tarifas ao longo de um período

* Desenvolver um **comparador de preços de tarifas**: 
    
    * Produtos/Serviços
    * Bancos
    * Moeda

obs.: No comparador, apresentar a instituição e oferece o menor custo para os Produtos/Serviços selecionados

### Requisitos Não Funcionais

* O tempo de resposta do site deve ser abaixo de 1000ms em 99.99% das requisições
* O mecanismo de logging da aplicação deve gerar as trilhas em formato JSON (opcional)
* O sistema deve conter métricas que ajudem a observar o seu comportamento: 

    * Qte de requisições
    * Tempo de resposta
    * Qtd e % de falhas ao obter dados dos Golden Sources

### Tecnologias Obrigatórias

* Framework SpringBoot
* Linguagem Java Web Server Side
* Linguagem Python (IA - Machine Learning)
* Scikit-learn (IA - Machine Learning)
* Tensorflow ou Keras ou Pytorch (IA  - Deep Learning)

