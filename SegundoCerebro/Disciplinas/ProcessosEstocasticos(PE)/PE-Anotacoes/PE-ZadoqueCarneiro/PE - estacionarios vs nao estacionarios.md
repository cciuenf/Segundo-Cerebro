---
Data: 27/02/205
---

#ProcessosEstocásticos  #Anotação 

## Processos Estacionários

- **Definição**: Processos cujas propriedades estatísticas não mudam ao longo do tempo.
- **Tipos de estacionariedade**:
    - **Estacionariedade estrita**: Todas as distribuições de probabilidade conjuntas são invariantes a deslocamentos no tempo
    - **Estacionariedade fraca (ou de segunda ordem)**: Média e covariância são invariantes no tempo
- **Características**:
    - E[X(t)] = μ (constante)
    - Cov[X(t), X(t+h)] depende apenas de h, não de t
- **Exemplos**:
    - **Ruído branco**: Sequência de variáveis aleatórias independentes e identicamente distribuídas
    - **Processos AR, MA e ARMA estacionários**: Modelos de séries temporais com parâmetros constantes
    - **Processo de Ornstein-Uhlenbeck**: Processo contínuo com tendência a retornar à média

## Processos Não-Estacionários

- **Definição**: Processos cujas propriedades estatísticas variam ao longo do tempo.
- **Características**:
    - Média, variância ou outras distribuições de probabilidade mudam com o tempo
    - Exibem tendências, sazonalidades ou mudanças estruturais
- **Exemplos**:
    - **Passeio aleatório**: A variância aumenta linearmente com o tempo
    - **Processos com tendência**: Média varia sistematicamente com o tempo
    - **Processos ARIMA não-estacionários**: Modelos de séries temporais que precisam de diferenciação para se tornarem estacionários
    - **Processo de Poisson não-homogêneo**: Taxa de ocorrência de eventos varia com o tempo


## Continuação: [[PE - tipos]]]