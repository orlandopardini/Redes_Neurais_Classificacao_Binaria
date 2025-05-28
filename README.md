# Classificação Binária com Redes Neurais Artificiais (RNA)

As **Redes Neurais Artificiais (RNAs)** são modelos computacionais inspirados no funcionamento do cérebro humano, capazes de aprender padrões a partir de exemplos. Quando aplicadas à **classificação binária**, as RNAs distinguem entre duas classes (ex: sim/não, 0/1, positivo/negativo).

Elas são compostas por camadas de neurônios artificiais, onde cada neurônio realiza uma operação matemática sobre os dados e transmite o resultado para os próximos neurônios.

### Por que RNAs são eficazes?

- Aprendem **relações complexas não-lineares**
- Adaptam-se a qualquer tipo de dado (numérico, categórico, normalizado)
- Podem ser otimizadas com **múltiplas camadas, regularização e validação cruzada**
- Aplicáveis a diversas áreas: saúde, finanças, indústria etc.

### Funcionamento Intuitivo

Imagine uma rede que recebe os dados de um paciente (idade, pressão, colesterol) e classifica se há risco cardíaco. A RNA aprende com exemplos anteriores e **ajusta seus pesos internos** para tomar decisões com base nesses padrões.

---

## 📂 Estrutura dos Notebooks

### 1. `RNA1_Classificacao_Binaria_Simples_Orlando.ipynb`
**📌 Tarefa:** Classificação simples com RNA  
**📚 Dataset:** Dados sintéticos ou reais com duas classes  
**🔍 Destaques:**
- Arquitetura com uma camada oculta
- Treinamento e avaliação básica
- Curvas de acurácia e erro

### 2. `RNA2_Classificacao_Binaria_Validacao_Cruzada_Orlando.ipynb`
**📌 Tarefa:** Avaliação robusta com validação cruzada  
**📚 Dataset:** Mesmo problema com divisão em folds  
**🔍 Destaques:**
- Aplicação de `KFold` para medir a generalização
- Cálculo de média e desvio de métricas
- Comparação de performance entre execuções

### 3. `RNA3_Classificacao_Binaria_Classificar_um_registro_Orlando.ipynb`
**📌 Tarefa:** Classificação de um novo registro  
**📚 Dataset:** Após treinamento, nova entrada é classificada  
**🔍 Destaques:**
- Treinamento da rede e classificação pontual
- Uso de `.predict()` com novos dados
- Interpretação do resultado da RNA

### 4. `RNA4_Classificacao_Binaria_Tuning_de_parametros_Orlando.ipynb`
**📌 Tarefa:** Otimização de hiperparâmetros  
**📚 Dataset:** Mesmo conjunto com diferentes configurações  
**🔍 Destaques:**
- Testes com diferentes números de neurônios e épocas
- Comparação gráfica entre modelos
- Escolha do melhor conjunto de parâmetros

---

## 📈 Métricas e Avaliação

As RNAs de classificação binária foram avaliadas por:

- **Acurácia**
- **Precisão, Recall e F1-score**
- **Curva ROC e AUC**
- **Validação cruzada e métricas agregadas**

---

## ⚙️ Técnicas Utilizadas

- Funções de ativação Sigmoid e ReLU
- Otimizadores como Adam e SGD
- Validação cruzada (`KFold`)
- Visualização com `Matplotlib` e `Seaborn`
"""
