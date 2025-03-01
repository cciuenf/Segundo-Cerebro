---
Data: 27/02/205
---
#ProcessosEstocásticos  #Anotação 
# Introdução

Este conjunto de notas trata das diferentes classificações que podemos atribuir a processos estocásticos. Cada processo é estudado segundo critérios como:
- **Homogeneidade vs. Heterogeneidade**: se as probabilidades de transição (ou de mudança de estados) permanecem constantes ao longo do tempo ou não.
- **Tempo Discreto vs. Contínuo**: se as observações do processo são feitas em instantes discretos ou continuamente no tempo.
- **Espaço de Estados**: descreve quais valores (ou conjuntos de valores) o processo pode assumir.
- **Enumerabilidade**: se o espaço de estados é enumerável (contável) ou não enumerável (pode ser infinito e não contável).
- **Estacionariedade vs. Não-Estacionariedade**: se as distribuições de probabilidade do processo se mantêm inalteradas ao longo do tempo ou mudam conforme o processo evolui.

## Continuação: [[PE - homogeneos vs heterogeneos]]
---

## Exemplos de Processos Estocásticos do Cotidiano

A seguir, 10 exemplos de processos estocásticos que encontramos no dia a dia, acompanhados de suas classificações e justificativas.

1. **Lançamento de um dado de 6 lados**  
   - **Homogêneo**: As probabilidades não mudam a cada lançamento.  
   - **Discreto no tempo**: O resultado só é observado a cada lançamento, em instantes pontuais.  
   - **Espaço de estados enumerável**: Possíveis resultados são {1, 2, 3, 4, 5, 6}, um conjunto finito contável.  
   - **Estacionário**: A distribuição de probabilidades para cada face não se altera ao longo do tempo.  

2. **Lançamento de uma moeda**  
   - **Homogêneo**: A chance de dar cara ou coroa é a mesma a cada lançamento.  
   - **Discreto no tempo**: Observamos o resultado em cada lançamento.  
   - **Espaço de estados enumerável**: {Cara, Coroa}, finito e contável.  
   - **Estacionário**: A probabilidade de cair cara ou coroa não muda com o tempo (assumindo a moeda não sofre desgastes que alterem o equilíbrio).  

3. **Chegada de clientes em uma fila de supermercado**  
   - **Homogêneo**: Se as taxas de chegada permanecem constantes (por exemplo, em certos horários estáveis).  
   - **Contínuo no tempo**: Os clientes podem chegar a qualquer instante.  
   - **Espaço de estados enumerável**: Podem chegar 0, 1, 2, ... clientes, mas é contável.  
   - **Pode ser estacionário ou não**: Se a taxa de chegada for fixa, é estacionário; se variar conforme o dia/hora, não-estacionário.  

4. **Preço de ações na bolsa**  
   - **Heterogêneo**: As estatísticas de variação podem mudar ao longo de diferentes períodos (por exemplo, em crises ou em euforia de mercado).  
   - **Contínuo no tempo**: As cotações variam a qualquer momento.  
   - **Espaço de estados não enumerável**: O preço pode assumir virtualmente qualquer valor real em certo intervalo.  
   - **Geralmente não-estacionário**: As propriedades estatísticas mudam ao longo do tempo (volatilidade pode crescer ou diminuir dependendo do contexto).  

5. **Chamadas telefônicas em uma central de atendimento**  
   - **Homogêneo** (por curtos períodos) ou **heterogêneo** (ao longo do dia, a taxa pode variar muito).  
   - **Contínuo no tempo**: As ligações podem chegar a qualquer segundo.  
   - **Espaço de estados enumerável**: Contamos o número de chamadas (0, 1, 2, ...).  
   - **Pode ser estacionário em um intervalo** ou **não-estacionário** se observarmos todo o dia (picos em horários específicos).  

6. **Nível de água em um reservatório**  
   - **Heterogêneo**: A taxa de entrada de água (chuvas, afluentes) e saída (uso humano, evaporação) podem mudar ao longo das estações.  
   - **Contínuo no tempo**: O nível de água varia de forma contínua.  
   - **Espaço de estados não enumerável**: Pode assumir qualquer valor em um intervalo contínuo.  
   - **Não-estacionário**: Varia de acordo com a sazonalidade, com as chuvas, etc.  

7. **Tráfego de dados em uma rede de computadores**  
   - **Homogêneo** em intervalos curtos, **heterogêneo** em períodos longos (horários de pico vs. horários ociosos).  
   - **Contínuo no tempo**: Os pacotes podem chegar a qualquer instante.  
   - **Espaço de estados enumerável**: Geralmente contamos o número de pacotes ou conexões (inteiros).  
   - **Estacionário ou não**: Pode ser aproximado como estacionário em períodos curtos; globalmente, não-estacionário.  

8. **População de bactérias em uma cultura**  
   - **Heterogêneo**: As taxas de reprodução e morte mudam com a disponibilidade de nutrientes.  
   - **Contínuo no tempo**: A população pode crescer ou decrescer a cada instante.  
   - **Espaço de estados enumerável**: É contável (embora possa ser muito grande).  
   - **Não-estacionário**: Conforme o tempo, a disponibilidade de recursos muda a dinâmica de crescimento.  

9. **Temperatura ambiente ao longo do dia**  
   - **Heterogêneo**: As estatísticas mudam (manhã, tarde, noite, estações do ano).  
   - **Contínuo no tempo**: Varia a cada instante.  
   - **Espaço de estados não enumerável**: A temperatura pode assumir qualquer valor em um intervalo contínuo.  
   - **Não-estacionário**: O comportamento muda de forma cíclica (diário, sazonal).  

10. **Tempo de vida de lâmpadas em uma fábrica**  
   - **Homogêneo**: Se assumirmos um padrão de desgaste igual ao longo do tempo (ex.: distribuição exponencial).  
   - **Contínuo no tempo**: A falha pode ocorrer a qualquer instante.  
   - **Espaço de estados enumerável** (se contamos falhas) ou não enumerável (se consideramos o tempo como variável real).  
   - **Estacionário** (para lâmpadas novas e idênticas) ou **não-estacionário** (caso haja diferentes lotes ou condições de uso).  

Esses exemplos ilustram a diversidade de processos estocásticos do cotidiano, bem como suas principais características e classificações. A depender das hipóteses e do contexto (por exemplo, se as probabilidades se mantêm ou não ao longo do tempo), o mesmo fenômeno pode ser modelado de formas distintas.
