
![download](https://github.com/user-attachments/assets/4877fadd-e5e1-46fa-a8c2-99e6e91f4ce2)

# $${\color{green}\text{Previsão de Atrasos em Voos - Machine Learning}}$$

Projeto desenvolvido com base no curso da **Alura** ministrado pelo **Instrutor Bruno Raphaell**, com o objetivo de construir um modelo de Machine Learning capaz de prever os atrasos em voos a partir de um conjunto de dados reais.

---

## $${\color{green}\text{📊 O que foi realizado neste projeto?}}$$

1. **Análise Exploratória dos Dados (EDA):**
   - Análise das estatísticas descritivas.
   - Verificação de valores nulos e tipos das colunas.
   - Construção de visualizações gráficas para melhor compreensão dos dados.
   - Análise da distribuição das variáveis numéricas com a Regra de Freedman-Diaconis. 

2. **Preparação dos Dados (Feature Engineering & Encoding):**
   - Criação de novas colunas relevantes para o modelo (Ex.: is_weekend, day_name).
   - Transformação de variáveis categóricas via `get_dummies` (One-Hot Encoding).
   - Análise de correlação para identificar e remover colunas não relevantes, visando evitar overfitting.

3. **Construção de Modelos de Machine Learning:**
   - Construção de um modelo **baseline** utilizando o DummyRegressor.
   - Construção de um modelo mais robusto com **RandomForestRegressor**.
   - Avaliação dos modelos pelas métricas **RMSE**, **MAE** e **R² Score**.

4. **Validação Cruzada e Visualizações:**
   - Validação cruzada (KFold Cross-Validation) para garantir a robustez do modelo.
   - Visualizações gráficas de **Erro de Previsão** e **Resíduos**.
   - Análise das **Features mais Importantes** para o modelo.

5. **Otimização de Hiperparâmetros (GridSearchCV):**
   - Ajuste fino dos hiperparâmetros do Random Forest para melhorar a performance.
   - Re-treinamento do modelo com as melhores configurações encontradas.

6. **Salvamento e Carregamento do Modelo:**
   - O modelo final foi salvo em arquivo `.pkl` para uso futuro.
   - Carregamento do modelo salvo para previsões posteriores.

---

## $${\color{green}\text{🛠️ Tecnologias e Ferramentas Utilizadas:}}$$
- Python 3.x
- Pandas
- NumPy
- Seaborn & Matplotlib
- Scikit-learn
- Yellowbrick
- Jupyter Notebook / Google Colab
- Pickle
