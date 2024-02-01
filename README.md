[![Python 3.7+](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-360/) [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0) 

<sub> 📂 Projeto - Data Science - Sarah F. Rezende

##  **Projeto** - **Análise Risco de Crédito** 💳

[PROJETO (COLAB)](https://github.com/SarahFeanor/Credit_Risk_Project/blob/main/A_An%C3%A1lise_de_Risco_de_Cr%C3%A9dito.ipynb)

Bem-vindos(as). Este repositório foi criado com o propósito de estudo. Vale ressaltar que todos os dados são exclusivamente para fins de demonstração, garantindo total privacidade e conformidade ética.

<p align="center">
  <a href="https://github.com/SarahFeanor?tab=repositories">
    <img src="https://cdn.discordapp.com/attachments/1063559719291199599/1202630786210201620/download_2.png?ex=65ce2833&is=65bbb333&hm=bbbedb3eb5c0357f3407bf192f9a2ad84ed599df7de0ef03105d25469da238b4&" alt="capa" width="500" height="300">
  </a>
</p> <p align="center"> <sup> Risco de Crédito — Foto de CBBR</sup> </p>

## **Análise de Risco de Crédito** 

Um dos maiores desafios das instituições financeiras reside na gestão do risco de crédito, pois a falta de cumprimento das obrigações de pagamento pode desencadear perdas financeiras substanciais. A habilidade de avaliar a capacidade de um indivíduo em honrar suas responsabilidades financeiras é de importância crucial para o êxito das instituições financeiras. Como resposta a essa demanda, têm sido elaboradas soluções cada vez mais sofisticadas visando atenuar o risco associado à inadimplência.

* **Default**: um termo amplamente utilizado para caracterizar a inadimplência, o qual indica a incapacidade do mutuário em cumprir com suas obrigações financeiras. Geralmente, a falta de pagamento resulta da fragilidade financeira do cliente, podendo ser ocasionada por diversos fatores, como a perda de emprego, enfermidade ou circunstâncias imprevistas.

A crescente colaboração entre grandes **bancos** e **fintechs** tem intensificado o investimento em modelos de Machine Learning visando evitar a inadimplência de clientes. Esses modelos se baseiam em histórico de pagamentos, pontuação de crédito, renda e outros dados para avaliar riscos, embasando decisões sobre empréstimos e investimentos.

## 📍 **Objetivo**

Este projeto visa explorar dados do ***Nubank***, uma instituição financeira, para realizar uma análise minuciosa e construir um modelo de previsão de inadimplência.

* **Desenvolver um modelo de previsão de inadimplência do cliente.**
O intuito é criar um modelo que não apenas reduza as perdas financeiras do Nubank, mas também minimize a ocorrência de falsos positivos.

## 📂 Dados

Os dados deste Projeto de Data Science originam-se de uma competição promovida pela **Startup Nubank**, visando identificar talentos para possível contratação na Fintech. O conjunto de dados utilizado na análise pode ser acessado através deste [link](http://dl.dropboxusercontent.com/s/xn2a4kzf0zer0xu/acquisition_train.csv?dl=0).

Embora não contenham informações explícitas, os nomes das colunas fornecem pistas relevantes para compreender a natureza do problema.

## **Conclusão**

Este estudo abordou o desafio significativo da inadimplência de crédito enfrentado pelas instituições financeiras. Desenvolvemos e testamos diversos modelos de aprendizado de máquina, empregando diferentes técnicas de pré-processamento de dados, balanceamento de classes e seleção de características.

A análise detalhada dos dados e a feature engineering desempenharam papéis essenciais na melhoria do desempenho dos modelos, permitindo uma representação mais eficaz dos dados e um aprendizado mais efetivo. Observamos que a feature selection conduziu a modelos mais simples e eficientes, sem comprometer a precisão da classificação. Esse processo permitiu que nos concentrássemos nas características mais relevantes, o que consequentemente levou a uma melhoria na performance dos modelos.

A aplicação de técnicas de balanceamento de classes, como RandomUnderSampling, SMOTE e SMOTE-TOMEK, foi fundamental para mitigar o problema do desbalanceamento de classes presente nos dados. Essas técnicas melhoraram a capacidade dos modelos em identificar corretamente a classe minoritária, ou seja, os clientes inadimplentes.

No entanto, é crucial salientar que, apesar dessas melhorias, ainda há espaço para aperfeiçoamento. A precisão na identificação de clientes inadimplentes, particularmente no contexto de recall, ainda pode ser melhorada. Além disso, a interpretação dos resultados e a avaliação das implicações finance
