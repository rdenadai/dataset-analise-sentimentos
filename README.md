# Dataset para Análise de Sentimentos

## Objetivo

Prover datasets contendo frases classificadas de acordo com polaridade e em maior granularidade emoções.

No caso da polaridade, um dataset contendo 3 polaridades:
 - Positivo
 - Negativo
 - Neutro

Já no caso das emoções, ter um dataset contendo as emoções definidas na teoria psicoevolucionária integrativa das emoções de Robert Plutchik.
    
- Básicas:
    - Alegria
    - Surpresa
    - Confiança
    - Antecipação
    - Medo
    - Raiva
    - Desgosto
    - Tristeza
- Secundárias:
    - Otimismo (Alegria + Antecipação)
    - Amor (Alegria + Confiança)
    - Submissão (Confiança + Medo)
    - Temor (Medo + Surpresa)
    - Desaprovação (Surpresa + Tristeza)
    - Remorso (Tristeza + Desgosto)
    - Desprezo (Desgosto + Raiva)
    - Agressividade (Raiva + Antecipação)


A ligação entre as emoções primárias e secundárias propostas por Plutchik pode ser observada na famosa **Rodas das Emoções**.

<img src="https://raw.githubusercontent.com/rdenadai/dataset-analise-sentimentos/main/img/plutchik.png" width="500px" />

> Uma questão inicialmente não levantada no projeto é a possibilidade de se avaliar um cálculo de valência para a emoção. Isso pode ser futuramente avaliado a viabilidade de criação desta nova dimensão no dataset.