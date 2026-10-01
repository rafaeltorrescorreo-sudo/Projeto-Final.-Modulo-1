# Sistema de Manutenção Preditiva (Indústria 4.0)

## Qual o problema resolvido?
Este projeto atua no setor industrial, onde paradas inesperadas geram prejuízos milionários. O sistema utiliza dados históricos de sensores (rotação, torque, etc.) para prever avarias em equipamentos mecânicos antes que ocorram, utilizando algoritmos de aprendizado de máquina (KNN e Árvore de Decisão).

## Técnicas e Tecnologias
- **Linguagem:** Python 3
- **Ambiente:** Jupyter Notebook
- **Bibliotecas:** Pandas, NumPy (Data Prep), Matplotlib, Seaborn (EDA), Scikit-Learn (Modelagem), Imblearn (Balanceamento com SMOTE).
- **Abordagem Técnica:** Tratamento de Outliers, Feature Engineering, Combate a Vazamento de Dados (Data Leakage) e Controle de Overfitting.

## Como executar
1. Clone o repositório.
2. Instale as dependências executando: `pip install -r requirements.txt`
3. Execute o arquivo notebook `.ipynb` em um ambiente Jupyter. (Os dados devem estar contidos na pasta `/data`).

## Melhorias Futuras
- Implementar modelos de ensemble como Random Forest ou XGBoost para comparar performances.
- Realizar validação cruzada (Cross-Validation) k-fold para uma métrica ainda mais robusta.
- Desenvolver uma API com Flask ou FastAPI para consumir as predições em tempo real.
