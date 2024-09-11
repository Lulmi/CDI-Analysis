# CDI-Analysis

### Project : CDI Analysis

**Description:**

The CDI Analysis Project aims to calculate the profitability of CDI using data directly from the Central Bank, developing a return calculator that analyzes profitability since 1994 and evaluates return windows. The project is divided into two main questions:

### Question 1

**Challenge:** Create a program to calculate the total profit of a fund, given an initial capital amount, over a specific period with different frequencies. Profit is calculated based on compound interest using the SELIC interest rate.

**Steps Taken:**

1. **Installation and Import of Modules and Libraries:** Install and import necessary libraries such as `pandas`, `numpy`, and `requests` for data manipulation and calculation.

2. **User Data Collection:** Develop an interface or script to collect user data, including the initial capital amount, start date, end date, and frequency (daily, monthly, or yearly).

3. **Data Processing:** Validate and process the user-provided data to ensure it is in the correct format and meets the established constraints.

4. **Retrieval of SELIC Data:** Make requests to the Central Bank to obtain historical SELIC rate data. This can be done through public APIs or other reliable data sources.

5. **Calculation of Period Return:** Implement the logic to calculate the total return using compound interest based on the SELIC rate, considering the chosen frequency.

### Question 2

**Challenge:** Identify the most profitable 500-day period between 2000-01-01 and 2022-03-31. Determine the period during which an investment of capital C would have generated the highest return within this range.

**Steps Taken:**

1. **Filtering SELIC Data:** Filter SELIC data for the date range from 2000-01-01 to 2022-03-31.

2. **Calculation of 500-Day Window Profitability:** Use a sliding window approach to calculate the profitability for all 500-day windows within the provided date range.

3. **Creation of Date Range Table:** Generate a date range corresponding to the 500-day windows and store the information in a table.

4. **Identification of Highest Return:** Analyze the table to find the 500-day period with the highest return and record the start and end dates of this period.

---

### Projeto: Análise CDI

#### Descrição do Projeto

O Projeto de Análise CDI tem como objetivo calcular a rentabilidade do CDI utilizando dados diretamente do Banco Central, desenvolvendo uma calculadora de retorno que analisa a rentabilidade desde 1994 e avalia janelas de retornos. O projeto é dividido em duas questões principais:

### Question 1

**Desafio:** Criar um programa que calcule o lucro total de um fundo, dado um valor inicial de capital, em um determinado período de tempo com diferentes frequências. O lucro é calculado com base no juro composto usando a taxa de juros SELIC.

**Passos realizados:**

1. **Instalação e Importação de Módulos e Bibliotecas:** Instalar e importar as bibliotecas necessárias, como `pandas`, `numpy`, e `requests`, para manipulação de dados e cálculo.

2. **Coleta de Dados do Usuário:** Desenvolver uma interface ou script para coletar dados do usuário, incluindo o valor inicial do capital, a data de início, a data de término e a frequência (dia, mês ou ano).

3. **Tratamento dos Dados Coletados:** Validar e processar os dados fornecidos pelo usuário para garantir que estejam no formato correto e dentro das restrições estabelecidas.

4. **Obtenção de Dados da SELIC:** Fazer requisições para o Banco Central para obter os dados históricos da taxa SELIC. Isso pode ser feito através de APIs públicas ou outras fontes de dados confiáveis.

5. **Cálculo do Retorno do Período:** Implementar a lógica para calcular o retorno total utilizando o juro composto com base na taxa SELIC, considerando a frequência escolhida.

### Question 2

**Desafio:** Identificar o período mais lucrativo de 500 dias corridos entre 2000-01-01 e 2022-03-31. Determinar o período em que um investimento de capital C teria gerado o maior retorno durante esse intervalo.

**Passos realizados:**

1. **Filtragem de Dados da SELIC:** Filtrar os dados da SELIC para o intervalo de datas entre 2000-01-01 e 2022-03-31.

2. **Cálculo da Rentabilidade das Janelas de 500 Dias:** Utilizar uma abordagem de janela deslizante para calcular a rentabilidade para todas as janelas de 500 dias dentro do intervalo de datas fornecido.

3. **Criação do Intervalo de Datas na Tabela:** Gerar um intervalo de datas correspondente às janelas de 500 dias e armazenar as informações em uma tabela.

4. **Identificação do Maior Retorno:** Analisar a tabela para encontrar o período de 500 dias com o maior retorno e registrar as datas de início e término desse período.


