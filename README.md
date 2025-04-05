# Brent Vision

![Dashboard](https://img.shields.io/badge/Dashboard-Streamlit-blue) ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Time%20Series-orange) ![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)

## Descrição do Projeto
Este repositório contém o projeto desenvolvido para o **Tech Challenge - Fase 4** da Pós Tech. O objetivo principal é analisar os dados históricos do preço do petróleo e desenvolver soluções que auxiliem na tomada de decisão de um grande cliente do setor energético. 

O projeto inclui:
- Um **dashboard interativo** com insights relevantes para análise estratégica.
- Um **modelo de Machine Learning** para previsão diária dos preços do petróleo.
- Um **MVP funcional** implementado com Streamlit.
- Um **storytelling** que conecta as análises e previsões com eventos geopolíticos e econômicos.

## Objetivos
1. Criar um **dashboard interativo** que apresente insights sobre a variação do preço do petróleo.
2. Desenvolver um **modelo preditivo de Machine Learning** utilizando séries temporais.
3. Implementar o **deploy do modelo em produção** com ferramentas adequadas.
4. Apresentar um **MVP funcional** utilizando Streamlit.
5. Elaborar um vídeo explicativo de até 5 minutos detalhando o desenvolvimento do projeto.

## Estrutura do Repositório

📂 ouro-negro-insights/\
├── 📁 data/ # Base de dados histórica (não incluída, consulte as instruções para download)\
├── 📁 notebooks/ # Notebooks Jupyter utilizados na análise exploratória (EDA)\
├── 📁 src/ # Scripts principais (modelos, pré-processamento, etc.)\
├── 📁 dashboard/ # Código relacionado ao dashboard interativo (Streamlit)\
├── 📁 docs/ # Documentação adicional e relatórios\
├── 📁 videos/ # Vídeo explicativo do projeto\


## Tecnologias Utilizadas
As principais ferramentas e bibliotecas utilizadas no projeto são:
- **Python**: Linguagem principal para análise de dados e desenvolvimento do modelo.
- **Pandas e NumPy**: Manipulação e análise de dados.
- **Matplotlib e Seaborn**: Visualização de dados.
- **Scikit-learn**: Desenvolvimento e avaliação dos modelos de Machine Learning.
- **Statsmodels ou TensorFlow/Keras**: Para modelagem de séries temporais (ARIMA, LSTM, etc.).
- **Streamlit**: Deploy do MVP interativo.
- **GitHub Projects**: Gerenciamento das tarefas.

Para mais detalhes sobre o modelo ou a análise, consulte os notebooks na pasta `notebooks`.

## Insights Relevantes no Dashboard
O storytelling no dashboard apresenta os seguintes insights:
1. Impacto de eventos geopolíticos no preço do petróleo (ex.: guerras, sanções).
2. Relação entre crises econômicas globais e a volatilidade dos preços.
3. Tendências sazonais ou padrões anuais nos preços históricos.
4. Influência da demanda global por energia nas flutuações dos preços.

## Modelo Preditivo
O modelo preditivo foi desenvolvido utilizando técnicas de séries temporais, como ARIMA ou LSTM, para prever o preço diário do petróleo Brent com base nos dados históricos.

### Avaliação do Modelo
O desempenho foi avaliado utilizando métricas como:
- RMSE (Root Mean Squared Error)
- MAE (Mean Absolute Error)

Os resultados detalhados estão disponíveis no notebook `notebooks/`.

## Deploy em Produção
O deploy foi planejado para ser realizado com Streamlit, permitindo que o cliente visualize os insights e previsões em tempo real.

### Como Acessar o MVP:
Após executar o comando `streamlit run`, acesse o endereço local fornecido no terminal (ex.: http://localhost:8501).

## Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests.

## Licença
Este projeto é apenas para fins educacionais e não possui licença específica.

---

Desenvolvido por [TIME 1] como parte do Tech Challenge da Pós Tech - Fase 4 🚀.


