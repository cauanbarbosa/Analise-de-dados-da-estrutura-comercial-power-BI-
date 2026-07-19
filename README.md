# Analise-de-dados-da-estrutura-comercial-power-BI-
Utilizando SQLite no VScode para analisar e realizar alguns tratamentos de dados e analises dos mesmo, utilizando também o Power BI para demonstrar esses dados de forma clara e objetiva

##### Dashboard no PowerBI
<img width="1439" height="807" alt="image" src="https://github.com/user-attachments/assets/9c709d06-22f6-4cc5-a105-b21c2d7a36c9" />

- Tendo um nini dashboard em cada grafico
<img width="1443" height="806" alt="image" src="https://github.com/user-attachments/assets/c465663b-74ea-4868-902f-664cd29a6d8c" />

Informações relevantes que obtive com a analise do SQLite onde dividi em:
##### Base:

- ##### Objetivo: Encontrar as principais empresas com maiores eventos

Tabela de empresas e seus eventos

| Empresa | QntEventos |
| --- | --- |
| Alpha Energia | 98 |
| Atlas Construções | 86 |
| Beta Log | 99 |
| Delta Saúde | 108 |
| Gama Agro | 115 |
| Litoral Saneamento | 83 |
| Minas Steel | 111 |
| Nordeste Foods | 100 |
| Omega Tech | 100 |
| Solar Bahia | 100 |

Conseguindo ver as 3 maiores e a moda 

- ##### Objetivo: encontrar a categoria que mais se repete

Tabela de categorias e seus eventos

| Categoria | QntEventos |
| --- | --- |
| Aquisição | 169 |
| Assembleia | 163 |
| Emissão | 141 |
| Mudança Rating | 170 |
| Pagamento | 181 |
| Resultado | 176 |

- ##### Objetivo: Qual status mais se repete

Tabela de categorias e seus eventos

| Status | QntStatus |
| --- | --- |
| Aprovado | 354 |
| Enviado | 334 |
| Pendente | 312 |

- ##### Objetivo: Saber qual periodo a tabela cobre

Tabela das datas inicial e final
| datas |
| --- |
| 2025-12-31 |
| 2024-01-01 |

##### Analise descritiva

- ##### Objetivo: Quantos eventos há por estado e qual o que têm mais eventos

- Estados e seus eventos

| Estado | QntEstados |
| --- | --- |
| BA | 133 |
| CE | 139 |
| GO | 122 |
| MG | 122 |
| PE | 124 |
| PR | 119 |
| RJ | 118 |
| SP | 123 |

Tendo o Ceará com o maior número de eventos

- ##### Objetivo: Qual o rating tem a maior quantidade de eventos

- Rating e seus eventos

| Rating | QntRating |
| --- | --- |
| A | 201 |
| A+ | 210 |
| AA | 196 |
| AA+ | 204 |
| AAA | 189 |

Temos o A+ em maior quantidade e logo em seguida A 

##### Analise Financeira

- A soma dos valores é de R$:2432452.31 
- Tendo sua média de R$: 2432.45
  
- ##### Objetivo: Qual a empresa com maior e menor valor pago com Status aprovado

| Empresa | Estado | Status | Categoria | valor |
| --- | --- | --- | --- | --- |
| Delta Saúde | PE | Aprovado | Mudança Rating | 4985.17 |
| Omega Tech | GO | Aprovado | Pagamento | 53.29 |

- ##### Objetivo: Qual informações consigo do maior evento a ser pago

| Solar Bahia | BA | Enviado | Resultado | 4991.82 |
| --- | --- | --- | --- | --- |

- ##### Objetivo: Qual o voleme monetario dos estados

| Estado | Valor |
| --- | --- |
| BA | 335746.52 |
| CE | 355735.51 |
| GO | 294412.27 |
| MG | 281084.13 |
| PE | 310153.23 |
| PR | 257823.49 |
| RJ | 300740.07 |
| SP | 296757.09 |

-  Ceará detem o maior volume

- ##### Objetivo: Valor distribuido por rating

| Rating | Valor |
| --- | --- |
| A | 479905.17 |
| A+ | 502192.56 |
| AA | 487996.95 |
| AA+ | 473256.4 |
| AAA | 489101.23 |

-  A+ o que mais concentra valor

##### Analise Temporal

- ##### Objetivo: Quantos Eventos houveram por ano?

| QntEventos | anos |
| --- | --- |
| 496 | 2024 |
| 504 | 2025 |

- ##### Objetivo: Quantos eventos há por mês?

| QntEventos | Mes_Ano |
| --- | --- |
| 31 | 2024-01 |
| 38 | 2024-02 |
| 37 | 2024-03 |
| 45 | 2024-04 |
| 43 | 2024-05 |
| 41 | 2024-06 |
| 45 | 2024-07 |
| 38 | 2024-08 |
| 37 | 2024-09 |
| 50 | 2024-10 |
| 42 | 2024-11 |
| 49 | 2024-12 |
| 42 | 2025-01 |
| 43 | 2025-02 |
| 36 | 2025-03 |
| 36 | 2025-04 |
| 42 | 2025-05 |
| 41 | 2025-06 |
| 49 | 2025-07 |
| 45 | 2025-08 |
| 47 | 2025-09 |
| 34 | 2025-10 |
| 47 | 2025-11 |
| 42 | 2025-12 |

-O mês 10-2024 têm a maior quanatidade de eventos
- Os meses 10-2024 e 07-2025 são os meses com maior quantidade de eventos nos seus respectivos anos
