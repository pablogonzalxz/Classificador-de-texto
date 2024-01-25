<h1>Classificador-de-texto</h1>


1. **Carregamento de Dados:**
   - O script carrega um conjunto de dados chamado "20 newsgroups", contendo documentos de 20 newsgroups diferentes (categorias).
   - Dois conjuntos são criados para treinar e testar o modelo.

2. **Modelo de Classificação de Texto:**
   - O modelo é construído usando o algoritmo Naive Bayes, um método de classificação probabilístico.
   - Os dados de texto são transformados em características numéricas usando o vetorizador TF-IDF.
   - Um classificador Naive Bayes multinomial é treinado nos dados transformados usando um pipeline.

3. **Avaliação do Modelo:**
   - O desempenho do modelo é avaliado usando uma matriz de confusão e um mapa de calor.
   - A matriz de confusão representa visualmente quão bem o modelo prevê as categorias em comparação com os rótulos reais.
   - Abaixo está a imagem do mapa de calor:
     ![Sem título1](https://github.com/pablogonzalxz/Classificador-de-texto/assets/157144024/5b8cef9f-5445-487e-8442-988db31d4fe9)

4. **Tradução de Texto e Predição:**
   - O script inclui funções para traduzir texto não inglês para inglês usando o Google Translate.
   - Uma função prevê a categoria de um texto dado usando o modelo Naive Bayes treinado.
   - Opcionalmente, os usuários podem inserir texto para testar a função de classificação de texto.

5. **Dependências:**
   - O código depende de bibliotecas como NumPy, Matplotlib, Seaborn, Scikit-learn e Googletrans. Certifique-se de que essas bibliotecas estejam instaladas.
