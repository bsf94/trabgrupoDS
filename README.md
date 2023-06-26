# Análise de Cidades para Abertura de Clínicas de Fisioterapia no Brasil

# Objetivo
Este projeto de ciência de dados tem como objetivo analisar cidades no Brasil e identificar aquelas que indicam melhores oportunidades para a abertura de clínicas de fisioterapia. Por meio dessa análise, busca-se fornecer informações para orientar a abertura ou expansão de clínicas de fisioterapia em regiões que apresentem maior necessidade ou oportunidade desses serviços.

## Contexto e relevância
O contexto da análise engloba todos os municípios do Brasil, embora dados sobre todos os municípios não foram encontrados para todas as variáveis. A relevância da escolha pode ser explicada pelos seguintes pontos:

- **Impacto na saúde pública:** A fisioterapia desempenha um papel crucial na reabilitação e tratamento de lesões e condições físicas. Ao identificar as cidades que podem se beneficiar da abertura de mais clínicas de fisioterapia, contribui-se para melhorar a saúde pública nessas áreas, proporcionando acesso adequado a serviços de reabilitação.

- **Oportunidades de negócios:** Ao determinar as cidades com demanda insuficiente ou subatendida de clínicas de fisioterapia, empresários e investidores podem identificar oportunidades de negócios. Isso pode incentivar a abertura de novas clínicas e promover o empreendedorismo nessa área específica da saúde.

- **Planejamento de recursos de saúde:** Ao analisar os dados e identificar as cidades que precisam de mais clínicas de fisioterapia, espera-se obter informações valiosas para o planejamento estratégico de recursos de saúde. 

- **Melhoria na qualidade de vida:** A disponibilidade de serviços de fisioterapia adequados em uma comunidade pode contribuir para melhorar a qualidade de vida dos seus moradores. 

# Primeira parte do projeto

A primeira parte do projeto utiliza técnicas de coleta de dados, pré-processamento e análise exploratória para alcançar os objetivos propostos.

## Coleta e pré-processamento dos dados

Antes de realizar a análise, os dados coletados passaram por um processo de pré-processamento para garantir sua qualidade e consistência. Nessa etapa, foram tratados valores ausentes, removidos duplicatas e os dados foram transformados em um formato adequado para análise. Foram realizadas manipulações e engenharia de recursos, bem como normalização dos dados, quando necessário.

Os dados foram coletados dos seguintes sites:
* Ministério da Saúde (TABNET): 
Disponivel em: https://datasus.saude.gov.br/informacoes-de-saude-tabnet/

* Ministério da Fazenda: 
Disponivel em: https://dados.gov.br/dados/conjuntos-dados/cadastro-nacional-da-pessoa-juridica---cnpj 

* Agência Nacional de Saúde Suplementar: 
Disponivel em: https://www.ans.gov.br/perfil-do-setor/dados-gerais

* IBGE https://www.ibge.gov.br/estatisticas/economicas/contas-nacionais/9088-produto-interno-bruto-dos-municipios.html

## Análise exploratória

Após a organização dos dados, com o dataframe DSP_data, diversos passos de análise exploratória foram realizados.

## Dicionário de dados

| Nome da Variável        | Descrição                                                  | Tipo         |
|-------------------------|------------------------------------------------------------|--------------|
| Nome                    | Nome do município                                          | Texto        |
| Codigo                  | Código do município                                        | Numérico     |
| 20 a 29 anos            | Número de pessoas na faixa etária de 20 a 29 anos          | Numérico     |
| 30 a 39 anos            | Número de pessoas na faixa etária de 30 a 39 anos          | Numérico     |
| 40 a 49 anos            | Número de pessoas na faixa etária de 40 a 49 anos          | Numérico     |
| 50 a 59 anos            | Número de pessoas na faixa etária de 50 a 59 anos          | Numérico     |
| 60 a 69 anos            | Número de pessoas na faixa etária de 60 a 69 anos          | Numérico     |
| 70 a 79 anos            | Número de pessoas na faixa etária de 70 a 79 anos          | Numérico     |
| 80 anos e mais          | Número de pessoas com 80 anos ou mais                      | Numérico     |
| Menor que 1 a 9 anos    | Número de pessoas com idade inferior a 10 anos             | Numérico     |
| 10 a 19 anos            | Número de pessoas na faixa etária de 10 a 19 anos          | Numérico     |
| Total_População         | Total da população do município                            | Numérico     |
| Total_BeneficiariosPlanoSaude | Total de beneficiários de plano de saúde no município   | Numérico     |
| PH_Articulacoes | Número de procedimentos hospitalares relacionados a articulações | Numérico     |
| PH_Ortopedicas  | Número de procedimentos hospitalares relacionados a ortopedia | Numérico     |
| AcidTransito   | Número de acidentes de trânsito no município               | Numérico     |
| PIB/capita   | Pib por capita do município               | Numérico     |
| PIB   | PIB do município               | Numérico     |
| VABServiços   | Valor adicionado bruto de serviços               | Numérico     |



## Repositório

Esse repositório contém 3 branches: main (com os dados em .csv), apresentação (com o arquivo da apresentação em pdf) e código (com o arquivo em .ipynb). O repositório possui as bases de dados originais, assim como dataframes criados após limpeza de dados (df_....csv).

Projeto criado por Brenda Farias e Fabricio Leal, para a disciplina de Introdução à Data Science (ADM01007) da Universidade Federal do Rio Grande do Sul.
