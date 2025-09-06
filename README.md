# Projeto_Aplicado_III_RetailWise
- Projeto Aplicado III

- Integrantes: 
Maiki Soares e Vanessa Cordeiro

- Nome do Grupo: RetailWise

- Justificativa: O nome "RetailWise" combina "retail" (varejo) com "wise" (sábio), sugerindo um sistema inteligente que faz recomendações de produtos de forma eficaz, refletindo o objetivo do seu projeto. É simples, memorável e alinhado ao tema.


**Overview do Projeto**

- Título do Projeto: Sistema de Recomendação de Produtos para Varejo Online

- Descrição Breve: O projeto consiste no desenvolvimento de um sistema de recomendação de produtos para uma loja de varejo online, inspirado em plataformas como a Amazon. Utilizando o dataset Online Retail, que contém transações de clientes (CustomerID, StockCode, Quantity), o sistema emprega técnicas de Machine Learning, como filtragem colaborativa, para sugerir produtos relevantes com base no histórico de compras dos usuários. O objetivo é criar um modelo simples e eficiente que recomende itens que maximizem a relevância para os clientes, simulando uma experiência de e-commerce personalizada.
- Etapas Principais:
  - Pré-processamento: Carregar o dataset CSV, filtrar colunas relevantes (CustomerID, StockCode, Quantity), remover dados nulos e selecionar um subconjunto pequeno (ex.: 10.000 linhas) para facilitar o processamento.
  - Modelagem: Construir uma matriz usuário-produto e treinar um modelo de recomendação, como filtragem colaborativa (usando similaridade por cosseno ou biblioteca Surprise) ou co-ocorrência de produtos.
  - Avaliação: Medir a eficácia do sistema com métricas como precisão das recomendações (ex.: top-N recomendações) ou RMSE, se aplicável.
  - Resultados: Apresentar sugestões de produtos para clientes fictícios, mostrando como o sistema poderia ser integrado em um site de varejo.
- Impacto: O sistema demonstra como modelos de recomendação podem aumentar a satisfação do cliente e impulsionar vendas em e-commerce, com uma implementação prática e acessível, ideal para iniciantes em Machine Learning.
