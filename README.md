# Hate Speech Classifier
## Como utilizar
Para utilizar este projeto é necessário que se tenha instaldo o Docker (a imagem do projeto está disponível neste [link](https://hub.docker.com/r/tiverons/jupyternotebook)), 
tendo satisfeito este requisito, dentro da pasta do projeto execute o comando:

```sudo docker-compose up```

Este comando irá gerar uma token de acesso como este: 
![link](https://github.com/GabrielTiveron/HateSpeechClassifier/blob/master/images/imagem.png "Generated Token")



Sendo assim, basta colar o link gerado (ultima linha) no navegador e assim ter acesso ao projeto em sí.
O projeto consiste na classificação de tweets (com e sem discurso de ódio).
Para a realização do projeto foram utilizadas as dependencias: nltk, pandas, scikit-learn; todas presentes na imagem do Docker.
