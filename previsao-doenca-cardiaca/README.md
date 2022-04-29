## projeto 11 características clínicas para prever eventos de doença cardíaca.
 
Este projeto tem por objetivo desenvolver um algoritmo de Machine Learning para prever a tendência de uma pessoa desenvolver algum tipo de doença cardíaca com base em alguns fatores clínicos e laboratoriais de referência.

**As tecnologias mas utilizadas são**

- Python
- jupyter notebook

**Contexto**
As doenças cardiovasculares (DCVs) são a causa número 1 de morte em todo o mundo, levando cerca de 17,9 milhões de vidas a cada ano, o que representa 31% de todas as mortes em todo o mundo. Quatro das mortes por 5CVD são devido a ataques cardíacos e derrames, e um terço dessas mortes ocorre prematuramente em pessoas com menos de 70 anos de idade. A insuficiência cardíaca é um evento comum causado por DCV e este conjunto de dados contém 11 características que podem ser usadas para prever uma possível doença cardíaca.

Pessoas com doença cardiovascular ou com alto risco cardiovascular (devido à presença de um ou mais fatores de risco, como hipertensão, diabetes, hiperlipidemia ou doença já estabelecida) precisam de detecção e gerenciamento precoces, onde um modelo de aprendizado de máquina pode ser de grande ajuda.

**Informações de atributo**
- Idade: idade do paciente [anos]
- Sexo: sexo do paciente [M: Masculino, F: Feminino]
- ChestPainType: tipo de dor no peito [TA: Angina Típica, ATA: Angina Atípica, NAP: Dor Não Anginosa, ASY: Assintomática]
- PA de repouso: pressão arterial de repouso [mm Hg]
- Colesterol: colesterol sérico [mm/dl]
- FastingBS: glicemia em jejum [1: se FastingBS > 120 mg/dl, 0: caso contrário]
- ECG de repouso: resultados do eletrocardiograma de repouso [Normal: normal, ST: com anormalidade da onda ST-T (inversões da onda T e/ou elevação ou depressão de ST > 0,05 mV), HVE: mostrando provável ou definitiva hipertrofia ventricular esquerda pelos critérios de Estes]
- MaxHR: frequência cardíaca máxima alcançada [Valor numérico entre 60 e 202]
- ExercícioAngina: angina induzida por exercício [S: Sim, N: Não]
- Pico antigo: pico antigo = ST [Valor numérico medido em depressão]
- ST_Slope: a inclinação do segmento ST do exercício de pico [Up: upsloping, Flat: flat, Down: downsloping]
- HeartDisease: classe de saída [1: doença cardíaca, 0: normal]
