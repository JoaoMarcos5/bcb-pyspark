# Análise de Dados da API do Banco Central com PySpark

Este projeto utiliza um dos recursos da API pública do Banco Central do Brasil (BCB) para coletar e transformar dados de transações com cartões, aplicando operações de transformação e ação usando PySpark.

## Objetivo

Aplicar pelo menos 5 operações de Transformação e Ação sobre uma base de dados retornada da API do Banco Central, conforme solicitado na atividade acadêmica.
O processamento é feito utilizando PySpark no ambiente do Google Colab.

## API Utilizada

 Endpoint:

https://olinda.bcb.gov.br/olinda/servico/MPV_DadosAbertos/versao/v1/odata/Quantidadeetransacoesdecartoes(trimestre=@trimestre)?@trimestre='2023'&$top=100&$format=json


Essa API retorna informações públicas sobre quantidade e valor de transações com cartões (crédito, débito e pré-pago) em diferentes trimestres.

## Operações Aplicadas
Transformações

Seleção de colunas específicas (select)

## Filtragem de dados (filter)

Agrupamento por modalidade e bandeira (groupBy)

Agregação com soma e média (agg)

Ordenação dos resultados (orderBy)

## Ações

Exibição dos dados no console (show)

Contagem total de registros (count)

Coleta de resultados (collect)

Exibição de médias e totais calculados (show)

Conversão para Pandas para visualização final (toPandas)

## Tecnologias Utilizadas

Python 3

PySpark


Google Colab

Requests (para consumir a API REST)

JSON

## Execução

Acesse o Google Colab.

Importe o notebook do projeto.

Execute todas as células sequencialmente:

Instalação e configuração do Java e PySpark

Criação da sessão Spark

Requisição e leitura dos dados da API

Aplicação das transformações e ações

Os resultados serão exibidos diretamente nas células de saída do notebook.


## Conclusão

O projeto demonstra a integração entre:

Dados públicos via API do Banco Central

Processamento distribuído com PySpark

Transformações e ações práticas sobre dados reais

Com isso, é possível realizar análises escaláveis de dados econômicos e extrair insights sobre o comportamento de transações com cartões no Brasil.
