# Machine Learning

O aprendizado de máquina (em inglês, machine learning) se baseia na ideia de que sistemas podem analisar e aprender com dados para então identificar padrões e tomar decisões com o mínimo de intervenção humana.


    O algoritmo pode encontrar padrões "apenas" se fornecermos recursos (informações) para que ele possa
    aprender. Mas depois disso, para nos dizer como os dados devem ser classificados, ele também precisa
    de um conjunto de classes/valores/respostas possíveis (rótulos/labels) para que ele saiba o que
    fazer com cada dado que inserimos. Para que ele saiba como classificá-los.

    > Explicado brevemente, uma feature seria um input (os dados de entrada) que você forneceu ao sistema e o label (rótulo) seria o output (a resposta/previsão) que se espera.

    >  Features são padrões, cores, formas ... ou seja, 'nomes de colunas' no conjunto de dados de treinamento.
       Label é o valor que queremos prever. A resposta que obtemos do nosso modelo após o treinamento.
       
A aplicação dos algoritmos de ML se resume a:
      
      - Separar dados de treino (features - X) e teste (labelS - y)
            - X, y - de treino 
            - X, y - de teste
      - Criar o modelo
            - Escolher o mais adequado.
            - Criar o objeto() do modelo para ter acesso a seus métodos.
            - Passar os dados de treinamento.
            - Fazer as predições com os dados de teste.
            - Checar a precisão do modelo comparando os dados de teste com as as respostas previstas pelo algoritmo.
      

(X, y) de treinamento: Agem no modelo.

(X, y) de teste: validam o modelos.

Os recursos de treinamento são os dados que fornecemos ao nosso modelo durante o treinamento, juntamente com as respostas corretas. O objetivo é que o modelo faça um mapeamento entre as features e os labels.

O conjunto de recursos de teste é usado para avaliar o modelo treinado. **O modelo não tem permissão para ver as respostas para o conjunto de testes e deve fazer previsões usando apenas os recursos de treinamento**. Conhecemos as respostas para o conjunto de testes para que possamos comparar as previsões do teste com as respostas.
