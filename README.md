# Credit Score Classification

Este projeto utiliza técnicas de Machine Learning para classificar o score de crédito de indivíduos com base em características como renda, idade, posse de imóvel e educação. O modelo foi desenvolvido usando Árvore de Decisão, e os dados foram balanceados com SMOTE para lidar com o desequilíbrio das classes.

## Índice
1. [Visão Geral](#visão-geral)
2. [Técnicas Utilizadas](#técnicas-utilizadas)
3. [Resultados](#resultados)
4. [Como Executar](#como-executar)
5. [Próximos Passos](#próximos-passos)
6. [Contribuições](#contribuições)
7. [Licença](#licença)

## Visão Geral

O objetivo deste projeto é prever o score de crédito de indivíduos com base em características demográficas e financeiras. O modelo pode ser útil para instituições financeiras que desejam avaliar o risco de crédito de seus clientes.

- **Problema:** Classificar o score de crédito em três categorias: Baixo, Médio e Alto.
- **Público-Alvo:** Analistas de dados, cientistas de dados e entusiastas de Machine Learning.

## Técnicas Utilizadas

- **Pré-processamento de dados:** Tratamento de valores nulos, codificação de variáveis categóricas e normalização.
- **Balanceamento de classes:** Aplicação de SMOTE para lidar com o desequilíbrio das classes.
- **Modelagem:** Utilização de uma Árvore de Decisão para classificação.
- **Avaliação:** Análise de métricas como acurácia, precisão, recall e F1-score.
- **Ferramentas:** Python, Pandas, Scikit-learn, Seaborn, Matplotlib.

## Resultados

- **Acurácia do modelo:** 94% no conjunto de teste.
- **Variáveis mais importantes:** Renda (Income) e Posse de Imóvel (Home Ownership).
- **Desempenho por classe:**
  - **Alto Score:** 97% de recall.
  - **Médio Score:** 82% de recall.
  - **Baixo Score:** 100% de recall.

### Insights:
- A **renda** e a **posse de imóvel** são os principais fatores que influenciam o score de crédito.
- A **classe 2 (Baixo Score)** foi perfeitamente classificada, enquanto a **classe 0 (Médio Score)** apresentou oportunidades de melhoria.

## Como Executar

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/seu-usuario/credit-score-classification.git

### Próximos Passos
- Ajuste de hiperparâmetros: Melhorar o desempenho do modelo com técnicas como Grid Search.
- Teste de outros modelos: Experimentar algoritmos como Random Forest e XGBoost.
- Análise de features: Criar novas variáveis para melhorar a classificação da classe "Médio Score".
-Deploy do modelo: Implementar o modelo em uma aplicação web ou API para uso prático.


# Contribuições

Contribuições são bem-vindas! Siga os passos abaixo para contribuir:

1. **Faça um fork do repositório.**

2. **Crie uma branch para sua feature:**
   ```bash
   git checkout -b minha-feature

## Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

![Captura de Tela](images/Captura de tela 2025-03-13 002356.png)
