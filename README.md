# Modelo_KNN_LOL
## Cubo Gelatinoso
Projeto de Aprendizado de Máquina desenvolvido para estudar o desempenho do algoritmo K-Nearest Neighbors (K-NN) na previsão do resultado de partidas de League of Legends.

O objetivo é utilizar informações coletadas aos 10 minutos de partida para prever se o time azul vencerá ou perderá. O trabalho compara o desempenho do K-NN com um modelo baseline e analisa diferentes configurações de hiperparâmetros.

## Sobre o projeto

O projeto aborda um problema de classificação binária, no qual o modelo deve determinar o resultado da partida:

1 → Vitória do time azul
0 → Derrota do time azul

O conjunto de dados contém estatísticas de partidas de jogadores de elo High Diamond, registradas aos 10 minutos de jogo. Originalmente, o dataset possui 40 atributos, dos quais um subconjunto foi selecionado para a construção dos modelos.

O notebook utiliza a acurácia como principal métrica de avaliação.

## DataSet

O conjunto de dados utilizado foi obtido através do Kaggle e contém informações relacionadas às partidas de League of Legends.

Inicialmente, o dataset possuía:

9.879 partidas
40 atributos

Após a filtragem dos dados, foram utilizadas 9.420 partidas no estudo.

Principais informações utilizadas

Entre os atributos inicialmente selecionados estão:

* `blueWins`
*  `blueKills`
*  `blueWardsPlaced`
*  `blueFirstBlood`
*  `blueTotalMinionsKilled`
*  `blueTotalJungleMinionsKilled`
*  `blueDragons`
*  `redKills`
*  `redWardsPlaced`
*  `redTotalMinionsKilled`
*  `redTotalJungleMinionsKilled`
## Como Executar
1. Clone o repositório
2. Entre na pasta
cd Cubo-Gelatinoso
3. Instale as dependências;<br>
  - pip install pandas numpy matplotlib seaborn scikit-learn 
  
5. Inicie o Jupyter Notebook
6. Abra o Cubo gelatinoso.ipynb
7. O dataset high_diamond_ranked_10min.csv deve estar disponível no mesmo diretório do notebook.
8. Execute as células em ordem

| Categoria | Informações |
|-----------|-------------|
| **Aluno** | **Ricardo Pereira Lourenço de Carvalho**<br> GitHub: [@Ricardo-Pereira-Lourenco](https://github.com/Ricardo-Pereira-Lourenco) |
| **Docentes** | **Daniel Roberto Cassar**<br>🔗 GitHub: [@drcassar](https://github.com/drcassar)

<img loading="lazy" src="https://github.com/Lorena881/PCD_Analise_Espectroscopia/assets/172424739/c930826b-3189-41d5-b4cc-a33dbf3ee611">
