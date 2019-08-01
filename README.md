# TASH-PT

O TASH-PT é um dataset para análise de sentimentos na língua portuguesa com dados coletados do Twitter. Os tweets foram anotados por voluntários humanos de acordo com os sentimentos expressados (positivo, negativo ou neutro).

O dataset é composto por um arquivo CSV que contém duas colunas. A primeira traz o ID do tweet coletado e a segunda o seu sentimento (-1 = negativo, 0 = neutro, 1 = positivo). No total tem-se 2.787 tweets, sendo 888 positivos, 881 negativos e 1.018 neutros.
 
O dataset não possui o conteúdo textual dos tweets, pois tal disponibilização fere
as regras de privacidade do Twitter. Por isso, é necessário utilizar a API do Twitter
para recuperar o conteúdo das mensagens através dos IDs.
