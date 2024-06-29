[iphone_price_history_brazil.csv](https://github.com/user-attachments/files/16040245/iphone_price_history_brazil.csv)
## 📊 Previsão de Cálculo de Preço Inteligente na AWS com [SageMaker Canvas](https://aws.amazon.com/pt/sagemaker/canvas/)

### Introdução

Seja bem-vindo ao desafio de projeto "Previsão de Cálculo de Preço Inteligente na AWS com SageMaker Canvas". Neste Lab DIO, você terá a oportunidade de utilizar o SageMaker Canvas para criar previsões de preços com base em Machine Learning (ML). Através deste desafio, você poderá:

* Aprofundar seus conhecimentos em Machine Learning
* Dominar o SageMaker Canvas
* Desenvolver habilidades práticas de Data Science
* Aprimorar seu portfólio profissional

Queria deixar claro que a base de dados não foi corretamente montada com precisão para realmente obter os verdaderiros preços do iphone, e seus respectivos preços em diferentes loja. Foi apenas um preço buscado em uma única fonte de dados (Chat GPT 4)
### A Jornada da Criação de um Conjunto de Dados Único

Neste projeto, partimos do zero para construir um conjunto de dados robusto e personalizado para alimentar nosso modelo de previsão de preços de smartphones. Através do poder da inteligência artificial (IA), embarcamos em uma jornada empolgante de coleta e processamento de dados históricos, extraindo insights valiosos para aprimorar a precisão das previsões.

**1. Coleta Inteligente de Dados Históricos:**

* **IA como Aliada:** Empregamos técnicas avançadas de IA para vasculhar a web em busca de preços históricos de smartphones desde seus lançamentos.
* **Abrangência e Precisão:** Coletamos dados de diversas fontes confiáveis, garantindo a abrangência e a precisão das informações coletadas.
* **Organização do Prompt para criar meu Dataset:**
    Conduct a comprehensive research on the weekly price history of iPhone 13 128GB, iPhone 14 128GB, and iPhone 15 128GB in Brazil, starting from their respective launch dates up to June 2024. Gather the data meticulously to ensure consistency and accuracy across all   
         entries. After collecting the data, create a CSV file with the following columns:
  
    model: The iPhone model (e.g., iPhone 13 128GB, iPhone 14 128GB, iPhone 15 128GB).
    date: The date of the price data in timestamp format (YYYY-MM-DD HH).
    price_brl: The price of the iPhone in Brazilian Real (BRL) in numerical format.
    launch_date: The launch date of the respective iPhone model in timestamp format (YYYY-MM-DD HH).
    Ensure that the date and launch_date columns are formatted correctly as timestamps and that the price is recorded as a numeric value. Collect the price data on a weekly basis from the launch date of each model to June 2024.
  

* ** Estruturamos os dados de forma organizada e eficiente, facilitando o acesso e a análise posterior. Segue abaixo estruturaa csv (commea separated) dos dados criados com o CHAT GPT 4o:
model,date,price_brl,launch_date
iPhone 13 128GB,2021-09-26,6999,2021-09-24
iPhone 13 128GB,2021-10-03,6988,2021-09-24
iPhone 13 128GB,2021-11-21,6808,2021-09-24
iPhone 14 128GB,2022-09-18,7999,2022-09-16
iPhone 14 128GB,2022-10-23,7874,2022-09-16
iPhone 14 128GB,2024-06-30,5744,2022-09-16
iPhone 15 128GB,2023-09-24,8999,2023-09-22
iPhone 15 128GB,2023-10-01,8968,2023-09-22
iPhone 15 128GB,2024-06-30,8070,2023-09-22

**2.🚀 Processamento e Enriquecimento do Conjunto de Dados:**

* **Limpeza e Pré-processamento:** Aplicamos técnicas de pré-processamento para garantir a qualidade e consistência dos dados coletados.
![image](https://github.com/henriqueCaruso/lab-aws-sagemaker-canvas-price-prediction/assets/47475037/c34fa2b4-ba6d-4452-9add-d78db2260e0c)


* **Tratamento de Inconsistências:** Identificamos e tratamos inconsistências nos dados, como valores ausentes ou outliers, para garantir a confiabilidade das análises.
* **Enriquecimento com Features Relevantes:** Extraímos e adicionamos features relevantes ao nosso conjunto de dados, como especificações técnicas, datas de lançamento e tendências do mercado.

**3. 🤔  Análise e Interpretação dos Resultados***

Ao final da jornada, obtivemos um conjunto de dados único e personalizado, rico em informações valiosas para o nosso modelo de previsão de preços de smartphones. Este conjunto de dados robusto nos permitirá:

![image](https://github.com/henriqueCaruso/lab-aws-sagemaker-canvas-price-prediction/assets/47475037/e93b79df-364e-4838-ab6e-eccd3917e954)

![image](https://github.com/henriqueCaruso/lab-aws-sagemaker-canvas-price-prediction/assets/47475037/70e65821-0372-4de8-85df-6740f6dca1b7)


* **Treinar um modelo de ML mais preciso:** Com dados históricos abrangentes e precisos, podemos treinar um modelo de ML que aprende com os padrões do passado para prever preços futuros com maior confiabilidade.
* **Identificar Fatores Influenciadores:** Através da análise das features enriquecidas, podemos identificar os principais fatores que influenciam os preços dos smartphones, como tendências do mercado, especificações técnicas e datas de lançamento.
* **Tomar Decisões Estratégicas:** As previsões geradas pelo modelo, embasadas em dados históricos e insights valiosos, podem auxiliar na tomada de decisões estratégicas de negócios, como definição de preços competitivos e otimização de lucros.
* **Como Eu acho que poderia ter sido melhor** Com uma base da dados maior, tendo outros dados importante coletados como, loja, feriados, preço por estado, histórico de Vendas eu poderia ter obtido um resulto mais preciso sobre o real preço esperado dos iphones.
### Desafio e Recursos Adicionais

**Continue sua jornada:**

* **Construção e Treinamento do Modelo:** Utilize o SageMaker Canvas para construir seu modelo de ML de forma intuitiva e treine-o com o conjunto de dados criado.
* **Análise e Interpretação dos Resultados:** Avalie o desempenho do modelo, identifique os fatores que mais impactam as previsões e refine o modelo para alcançar a máxima precisão.
* **Previsões e Aplicações:** Utilize o modelo treinado para gerar previsões de preços, explore diferentes cenários e utilize as insights para embasar decisões estratégicas de negócios.

**Recursos Adicionais:**

* Documentação do SageMaker Canvas: [https://docs.aws.amazon.com/sagemaker/latest/dg/canvas.html](https://docs.aws.amazon.com/sagemaker/latest/dg/canvas.html)
* Tutoriais do SageMaker Canvas: [https://docs.aws.amazon.com/sagemaker/latest/dg/canvas-getting-started.html](https://docs.aws.amazon.com/sagemaker/latest/dg/canvas-getting-started.html)
* Comunidade do SageMaker: [https://aws.amazon.com/events/asean/community-and-events/](https://aws.amazon.com/events/asean/community-and-events/)

**Compartilhe sua Jornada!**
Ao concluir o desafio, envie a URL do seu repositório na plataforma da DIO e compartilhe suas experiências com a comunidade. Mostre ao mundo suas habilidades em Machine Learning e Data Science!
