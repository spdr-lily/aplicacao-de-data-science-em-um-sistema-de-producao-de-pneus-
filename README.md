## **Projeto de Aplicação de Ciência de Dados em um Sistema de Produção de Pneus**

**1\. Introdução**

Este projeto demonstra a aplicação de técnicas de Ciência de Dados para otimizar a produção e melhorar a eficiência operacional em uma fábrica de pneus. Os principais desafios abordados incluem a previsão de demanda, gestão de estoque e manutenção preditiva de equipamentos.

**2\. Coleta e Visualização de Dados**

* Foi realizada a coleta de dados de produção, defeitos e manutenção, criando um DataFrame do pandas para estruturar as informações.  
* A produção acumulada foi calculada para cada dia.  
* Um gráfico de barras foi gerado para visualizar a produção diária de pneus, facilitando a identificação de tendências e padrões.

**3\. Manutenção Preditiva**

* Utilizou-se o algoritmo de Random Forest Regressor para prever a probabilidade de falhas nos equipamentos.  
* Dados fictícios de manutenção e produção foram usados para treinar o modelo.  
* O modelo foi capaz de prever a probabilidade de falha com base nos dias desde a última manutenção e na produção atual.

**4\. Previsão de Demanda**

* Empregou-se o modelo ARIMA para prever a demanda futura de pneus.  
* Dados de vendas fictícios foram utilizados para treinar o modelo.  
* O modelo forneceu previsões de demanda para os próximos três dias, permitindo ajustes na produção e estoque.

**5\. Resultados e Conclusões**

* A aplicação de Ciência de Dados mostrou-se eficaz na otimização dos processos da fábrica.  
* A manutenção preditiva pode reduzir o tempo de inatividade e evitar falhas inesperadas, aumentando a eficiência operacional.  
* A previsão de demanda permite uma resposta mais ágil às mudanças do mercado, otimizando a produção e o estoque.
