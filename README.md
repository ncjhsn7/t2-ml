# T2 - Aprendizado de Máquina
# Detecção de Fraudes

## Integrantes:
- Giovani Cancherini - (19111124)
- Nicolas Pietro - (19102850)

## Dados utilizados:
- Dataset BO`s    [https://www.kaggle.com/datasets/inquisitivecrow/crime-data-in-brazil]
- Dataset Fraudes [https://www.kaggle.com/competitions/ieee-fraud-detection/data?select=train_transaction.csv]

## Processamento dos dados:
1. Limpeza - precisa pegar todos os ids de usuários que já cometeram uma fraude, remover todos os usuários que nunca cometeram uma fraude.
2. Clustering - Mapear perfil dos usuários que cometeram uma fraude (separar em perfil 1, 2 ou 3...).
3. (x = atributo, y = count distinct id, stack = is_fraude) mapear os atributos para o eixo X e y sendo count distinct dos ids para descobrir os atributos que mais possuem impacto para realização de fraude.
4. manter informação de cartões.
5. remover colunas não necessárias



