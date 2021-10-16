# Clusterização de Dados de Sensores de Bomba


#### Aluno: [Hadriel Toledo Lima](https://github.com/hadriellima)
#### Orientadora: [Manoela Kohler](https://github.com/manoelakohler)



---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".


- [Código da Modelagem do Problema](Clustering Pump Sensor Data.ipynb.ipynb).
- [Código da Análise de Resultados](Results Analysis.ipynb).


---


## Resumo



## 1. Introdução

O monitoramento preditivo de equipamentos críticos em uma indústria é um processo importante para a continuidade da operação. Quanto mais cedo for possível prever que um equipamento vai falhar, mais tempo as equipes de manutenção tem para impedir que a falha ocorra. É um tema que tem sido objeto de estudo de utilização de aplicação de algoritmos de aprendizado de máquina pois tem potencial de redução de custo de manutenção e, principalmente, diminuir as paradas não programadas na linha de produção. 
A aplicação de métodos de aprendizado de máquina supervisionado é difícil neste tipo de problema porque rotular os dados é uma atividade complexa e de custo alto. Outro problema é que os equipamentos falham pouco e dificilmente será possível obter um rótulos de falhas para todos os problemas possíveis de ocorrer com um equipamento. 
Diante desse cenário tem sido muito utilizado algortimos de detecção de anomalia onde o modelo busca representar o estado de funcionamento normal do equipamento e considera como falha os estados de funcionamento fora do padrão representado no modelo. Como primeira abordagem para o problema é um excelente método pois é uma abordagem mais rápida e barata de ser construída e agrega valor ao processo de manutenção. Porém o algoritmo não é capaz de predizer qual tipo de falha vai ocorrer e  diante da necessidade de evolução no algoritmo de predição de falhas, o custo e a dificuldade de rotular os dados deve ser avaliado.
Na rotualação dos dados neste tipo de problema, mais importante que o rótular das falhas, é a identificação do período antes da falha em que o processo de falha iniciou. O objetivo 

O objetivo deste trabalho é utilizar métodos de clusterização como uma ferramenta de suporte ao especialista na análise de períodos transientes. 


## 2. Descrição dos dados

A base de dados escolhida para o trabalho foi encontrada no Kaggle com o nome *Pump sensor data for predictive maintenance* [link](https://www.kaggle.com/nphantawee/pump-sensor-data). Possui 220.320 registros de estados de funcionamento de uma bomba de água de abastecimento de uma cidade. Existem apenas 7 registros de falh, como é tipico neste tipo de problema. os atributos são: 
* **Timestamp:** Data, hora, minuto e segundo relativo aos dados. A coleta dos dados foi feita a cada 1 minuto. 
* **52 sensores:**: Valores de 52 sensores nesta bomba animizados; 
* **machine status:** Status de funcioanmento da máquina com os valores NORMAL, RECOVERING e **BROKEN**. No estudo os valores com RECOVERING foram considerados como de funcionamento normal.  



## 3. Modelagem



### 4. Resultados




### 5. Conclusão



---

Matrícula: 192.671.068

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
