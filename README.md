# Análise de diagnósticos hospitalares com Machine Learning
Este é um repositório feito para o projeto final da disciplina de aprendizado de máquina da ILUM, em que um conjunto de dados sobre pacientes com doenças graves foi estudado por 5 algoritmos diferentes de aprendizado de máquina, entre eles temos, regressão logística, algoritmo KNN, floresta aleatória, gradient boosting e SVM. Por fim, O melhor modelo foi escolhido para aplicar SHAP, um método que mede quanto cada variável de entrada contribuiu para uma previsão.


**Status**: Em andamento

---

# 💻 Instalação e Instruções 💻

Pré-requisito: [Conda](https://docs.conda.io/en/latest/) instalado. Para executar o projeto:

1. Clone o repositório e acesse a pasta:

```bash
git clone [URL DO REPOSITÓRIO]
cd [NOME DA PASTA DO REPOSITÓRIO]
```

2. Crie o ambiente virtual a partir do `environment.yml`:

```bash
conda env create -f environment.yml
```

3. Ative o ambiente:

```bash
conda activate [NOME DO AMBIENTE]
```

4. Inicie o Jupyter Lab:

```bash
jupyter lab
```

5. Abra o arquivo [NOME DO NOTEBOOK].ipynb. Caso as células não estejam executadas, clique em `Restart Kernel and Run All Cells`.


# Como navegar

O notebook segue a ordem em que o trabalho foi feito. 

| Seção | O que contém |
|---|---|
| 1. Introdução | Apresentando o notebook |
| 2. O conjunto de dados | retirado do UCI, sobre pacientes com condições graves |
| 3. Tratamento de dados | resolvendo problemas do dataset |
| 4. Divisão treino/teste | Divisão agrupada e estratificada. |
| 5. Análise exploratória | Feita só com o treino, analisando o dataset |
| 6. Pré-processamento e validação cruzada | O *pipeline* de pré-processamento e a validação cruzada para impedir vazamento. |
| 7. Os 5 modelos com otimização do Optuna em cada um | Os cinco *pipelines*, com os intervalos de busca de cada hiperparâmetro e as justificativas. |
| 8. Comparação dos modelos | procura do melhor modelo entre os feitos |
| 9. Avaliação no teste | Uso único do conjunto de teste no melhor modelo. |
| 10. Aplicação do SHAP | explicação de quanto cada atributo contribuiu para a previsão do melhor modelo. |
| Uso de IA | Como a IA foi usada no trabalho |
| Conclusões | Resultado principal e aprendizados. |
| Referências | Fontes utilizadas na produção do trabalho. |


# Desenvolvedora do projeto


