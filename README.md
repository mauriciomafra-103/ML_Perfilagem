# Machine learning para predição de Litologia com dados de Perfilagem

O objetivo do projeto é utilizar dados geofísicos de perfilagem para determinar a litologia do local utilizando Machine Learning

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Nome        | **Machine learning para predição de Litologia com dados de Perfilagem**
| :label: Tecnologias | Python, Scikt_Learn (tecnologias utilizadas)


![](data:image/png;base64,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#vitrinedev)

## Detalhes do projeto

O projeto foi realizado no ano de 2020 e proposto pela XEEK com o objetivo de interpretação litológica com Machine Learning. 
Peguei os dados do projeto e solucionei a minha maneira para explicar o aprendizado de máquina, processamento de dados e aplicação geofísica e geológica na realidade.
O projeto consegue utilizar uma boa quantidade dados e assim é possível fazer boas previsões com os dados. 
