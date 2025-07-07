# Biomarcador_ChagasAguda

Este repositório contém os códigos, dados e análises desenvolvidas no projeto de pesquisa de prospecção de biomarcadores na Doença de Chagas. 

# Objetivo deste projeto

Avaliar o desempenho das moléculas de adesão celular (MAC) como biomarcadores para discriminar indivíduos infectados e não-infectados, utilizando algoritmos de machine learning.

# Contexto deste projeto

A Doença de Chagas é uma enfermidade negligenciada com elevada morbidade nas Américas. A fase aguda representa uma janela crítica para diagnóstico e intervenção terapêutica. 
Este trabalho investiga a aplicabilidade de MAC solúveis (como CD106, CD62P, CD62L, CD62E) e exames parasitológicos, sorológicos (IgM) e moleculares (qPCR) como biomarcadores discriminatórios na fase aguda da doença.

# Tecnologias e Bibliotecas utilizadas
- Python 3.10+
- Pandas
- Numpy
- Scikit-Learn
- Matplotlib
- Seaborn
- SHAP

# Metodologia de análise
• Matriz de Confusão + Métricas
    - Avaliação de acurácia, precisão, recall, F1 e AUC.
    - Visualização dos acertos e erros do modelo.

• Importância das Features
    - Análise global da contribuição de cada biomarcador.
    - Interpretação dos pesos dados pelo modelo.

• Análise com SHAP Values
    - Interpretabilidade local e global do modelo.
    - Entendimento de como cada variável impacta a predição em cada indivíduo.
