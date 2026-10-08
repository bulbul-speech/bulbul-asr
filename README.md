# Bulbul: A Dataset for Dialectal Arabic Speech Recognition

Bulbul reports the zero-shot performance of 12 ASR models over 11 different dialects from Arab region. This study aim to quanitfy the performance of the SOTA ASR models over the different dialect from the arab region. 

What unique about Bulbul?
1. Data is private and models are not trained on them
2. Recorded under controlled environment. This eliminate the noise effect on the ASR model and keeps only the dialectal differences
3. The data covers 11 different dialect
4. The diversity of the dataset over gender and age
5. ...

Three families of models were evaluated on our dataset: general-puspose, OmniLLM, OmniCTC

The code is divided into three files:

1. `Bulbul_ASR_1.ipynb`: For general-purpose
2. `Bulbul_ASR_2.ipynb`: OmniLLM
3. `Omni_ASR.ipynb`: OmniCTC
