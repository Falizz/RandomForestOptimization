# Otimização de Random Forest para Classificação de Vinhos

## Descrição do Projeto
Este projeto teve como objetivo otimizar um modelo de **Random Forest** para prever a qualidade de vinhos com base em suas características químicas. O modelo inicial, fornecido pelo professor, apresentava uma acurácia de **88%**, e minha tarefa foi utilizar diferentes técnicas de busca de hiperparâmetros para aumentar essa taxa.

## Estratégias de Otimização Utilizadas
Para melhorar a performance do modelo, foram aplicadas três abordagens diferentes de **tuning de hiperparâmetros**:

### **Randomized Search**
- Testa um conjunto aleatório de hiperparâmetros dentro de um espaço predefinido.
- Método eficiente para encontrar boas combinações rapidamente, sem testar todas as possibilidades.
- Resultados: Pequena melhora, mas sem ganhos significativos.

### **Bayesian Search**
- Utiliza probabilidades para escolher os próximos conjuntos de hiperparâmetros com base em testes anteriores.
- Mais eficiente do que uma busca aleatória, pois foca em regiões promissoras do espaço de hiperparâmetros.
- Resultados: Pequena melhora na acurácia, mas ainda abaixo do esperado.

### **Grid Search**
- Explora **exaustivamente** todas as combinações possíveis dentro de um espaço de busca definido.
- Mais demorado, mas garante encontrar a melhor configuração dentro do grid.
- Resultados: O melhor desempenho encontrado foi **89% de acurácia**, porém sem grandes ganhos devido ao desbalanceamento da base de dados.

## Resultados
Após a aplicação das técnicas de otimização, a acurácia do modelo aumentou de **88% para 89%**, mostrando que o modelo já estava bem ajustado inicialmente
