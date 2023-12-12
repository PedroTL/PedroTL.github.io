---
title: "Monthly Trade Balance Report - Metropolitan Region of Campinas (MRC)"
excerpt: "Structure of the monthly trade balance report, one of the products of the Productive Structure and Socioeconomic Development extension project <br/><img src='/images/Trade_Balance_500_300.jpg'>"
collection: portfolio
---
<style>body {text-align: justify}</style>

## Overview

The Metropolitan Region of Campinas, consisting of 21 municipalities in the state of São Paulo, was created by the complementary state law 870 of June 19, 2000. The region is one of the most dynamic in the Brazilian economic scenario and represented, in 2013, 1.8% of the national GDP (gross domestic product) and 7.81% of the GDP of São Paulo, that is, about 105.3 billion reais.

The goal of this post is to present the main aspects of the monthly balance trade report of the Metropolitan Region of Campinas (MRC), including the objectives, methodology, structure, and results. The full version is available in Portuguese, and the content was adapted to a portfolio post structure, emphasizing the key points and bringing out the main results.

[Full study available in portuguese](https://observatorio.puc-campinas.edu.br/informativo-mensal-balanca-comercial-da-regiao-metropolitana-de-campinas-22/)

## Introduction

The Monthly Balance Trade Report for the MRC was one of the products for the Productive Structure and Socioeconomic Development project. The main goal was to automate an already set report and publish it monthly for the local media and public institutions within the MRC. The data is obtained with monthly updates from the [Comex Stat](http://comexstat.mdic.gov.br/pt/home), a system for data collection about international trade in Brazil provided by the Ministry of Development, Industry, Commerce and Services.

## Methodology

The workflow for data collection and the creation of the report is straight-forward. Initially, the data is updated by the [Comex Stat](http://comexstat.mdic.gov.br/pt/home); then, the download of the latest version is made to a local machine, and lastly, with a setup R script, the main tables are created, summarizing the results, alongside a built-in text in RMarkdown that interprets the statistics.

Other data sets are used, including the complexity index from [MIT Media Lab's Economic Complexity Observatory](https://www.media.mit.edu/projects/oec-new/overview/), to calculate the complexity of exported and imported goods and the _Nomenclatura Comum do Mercosul (NCM)_ (Common Nomenclature of Mercosur), which is the regional categorization for goods in South American countries.

The structure of the statistical analysis yields six (6) main insights.

- Look at the Trade Balance of the MRC in the current month, compared with the same month in the last 12 years
- See the degree of complexity of the exported and imported goods
- Visualize the Trade Balance of the MRC in the last 12 months
- View the main products exported and imported in the current year by the MRC
- Get insights about the destination of exported goods and the origin of imported ones
Look at the overall Trade Balance between the municipalities within the RMC

There are many insights that can be drawn from the statistics in hand, especially for the industrial sector and public institutions. Overall, the MRC relies heavily on imported goods with High complexity, while the exported products are mainly Medium-High and are dependent on the imported ones.

Many studies can be made after an economic analysis, but the main idea of the automated report is to be released quickly to the local media and public institutions. Further conjecture studies can be made later, with more time. The next session will show the full structured study from June 2022, made during my time as a research assistant. All the bold text is statistics that automatically change every month, pending new data.

## Results

### Pontifical Catholic University of Campinas Observatory
### Monthly Report: Trade Balance of the Metropolitan Region of Campinas

Volume. 5 | N.07 | 2022

Responsible: Prof. Dr. Paulo Ricardo da Silva Oliveira <br> 
Assistant: João Pedro Toledo Tricoli de Lucas

Executive Summary 

This report presents and discusses the main data from the MRC trade balance for the month of **June 2022**. The data used in the analysis comes from the Ministry of Development, Industry, Commerce and Services. In addition to the quantitative data, aggregated and disaggregated by municipality, the qualification of the MRC export and import list is presented, based on cross-referencing the trade data with the Product Complexity Index calculated by the [MIT Media Lab's Economic Complexity Observatory](https://www.media.mit.edu/projects/oec-new/overview/).

Among the information analyzed, the following stand out:

1. A **44.45** increase in exports and a **23.76%** increase in imports from the MRC, resulting in a **24.29%** increase in the regional deficit for the month of **June 2022**;
2. The share of imports and exports from the state of São Paulo was **23.76%** and **7.63%** respectively;
3. Among the products exported, the growth in the value of exports of cars, construction machinery and air or vacuum pumps or other air compressors stands out;
4. Among the imports, there was an increase in the value of insecticides and agricultural products, nitrogen-containing heterocyclic compounds, electronic circuits and other inorganic compounds;
5. There was an increase in exports to all the main destinations except Belgium;

In short, despite the structural problems of the regional trade deficit caused by dependence on imports of foreign inputs, the monthly data shows an improvement in the activity of the MRC's foreign sector compared to the same period the previous year. It is important to note that trade volume statistics, which are based on monetary values, suffered significant inflationary effects in the period.

Trade Balance July

Table 1 shows the MRC's trade balance data for the months of June between 2012 and 2022.

**Table 1: Trade Balance of The MRC for the Months of June (values in millions of USD/FOB)**<br>

| Month/Year <br> | Exp. value | $\%$ Exp. SP | Imp. value | $\%$ Imp. SP | RMC Balance | Balance SP |
| :---:  | :---:  | :---: | :---: | :---: | :---: | :---: |
| JUN/12 | 428,43 | $7,92 \%$ | 1166,89 | $17,9 \%$ | $-738,46$ | $-1109,17$ |
| JUN/13 | 400,40 | $7,7 \%$ | 1295,18 | $18,74 \%$ | $-894,78$ | $-1715,71$ |
| JUN/14 | 353,96 | $6,98 \%$ | 1256,59 | $17,95 \%$ | $-902,64$ | $-1931,16$ |
| JUN/15 | 355,98 | $7,06 \%$ | 1038,30 | $18,2 \%$ | $-682,32$ | $-661,94$ |
| JUN/16 | 310,53 | $6,4 \%$ | 866,99 | $19,09 \%$ | $-556,46$ | $310,91$ |
| JUN/17 | 375,06 | $6,98 \%$ | 1013,74 | $20,41 \%$ | $-638,68$ | $402,81$ |
| JUN/18 | 369,18 | $5,94 \%$ | 1080,79 | $19,11 \%$ | $-711,61$ | $564,39$ |
| JUN/19 | 349,58 | $8,6 \%$ | 1079,33 | $21,68 \%$ | $-729,74$ | $-912,64$ |
| JUN/20 | 239,07 | $6,43 \%$ | 995,92 | $24,85 \%$ | $-756,84$ | $-287,72$ |
| JUN/21 | 384,10 | $7,35 \%$ | 1254,21 | $22,32 \%$ | $-870,11$ | $-390,69$ |
| JUN/22 | 554,83 | $7,63 \%$ | 1636,30 | $23,76 \%$ | $-1081,48$ | $389,08$ |

From Table 1, it can be seen that exports in **June 2022** amounted to **554.83** million dollars, an increase of **44.45%** compared to the same period in **2021**. This figure corresponds to the best export performance for the month of June in 10 years. In addition, the state of São Paulo's share of exports was **7.63%**, one of the highest figures for the month of **June**.

Imports totaled **16.36** billion dollars in the same period, an increase of **30.46%** compared to **June 2021**. The MRC's share of the state's imports was **23.76%**. The negative balance of trade was **-1.08** billion dollars, an increase of **24.29%** compared to the previous year.

The main products responsible for the increase in export value were cars (up 156%) construction machinery (up 207%) and air or vacuum pumps or other air compressors (up 451%). Among the falls were medicines (down 9%), waste precious metals (down 41%), insecticides, and agricultural products (down 7%).

The main increases in imports were for insecticides and agricultural products (up 31%), nitrogen-containing heterocyclic compounds (up 44%), electronic circuits (up 52%) and other inorganic compounds (up 474%), among others. However, parts and accessories of machinery (down 13%) and parts and accessories of vehicles (down 8%) fell in value.

Table 2 shows the MRC's exports for the month of **June 2022**, aggregated according to the degree of complexity of the products. Products considered more complex are produced in countries with a higher degree of technological sophistication in their production structures and,  therefore, higher levels of productivity and income.

**Table 2 - Degree of Complexity of Exports: Comparison between Jun/2022 and Jun/2021 (values in millions of USD).**<br>

| Degree of Complexity | Value of Exp. 21 | % of Total 21 | Value of Exp. 22 | % of Total 22 | % Change 21/22 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Low | 6,18 | $1,61 \%$ | 5,09 | $0,92 \%$ | $-17,64 \%$ |
| Medium-low | 61,3 | $15,96 \%$ | 72,39 | $13,05 \%$ | $18,09 \%$ |
| Medium-high | 281,72 | $73,35 \%$ | 430,83 | $77,65 \%$ | $52,93 \%$ |
| High | 33,9 | $8,83 \%$ | 42,25 | $7,61 \%$ | $24,63 \%$ |
| Total | 376,92 |  | 545,47 |  |  |

Exports increase and decrease in different complexity categories. Low complexity saw a drop of **- 17.64%**; medium-low complexity saw an increase of **18.09%**; medium-high complexity saw an increase of **52.93%**; and high complexity saw an increase of **24.63%**. However, more than **77.56%** of the region's exports were concentrated in medium-high and high complexity products.

Table 3 shows the MRC's imports for the month of **June 2022**, aggregated according to the degree of economic complexity of the imported products.

**Table 3 - Degree of Complexity of Imports: Comparison between Jun/2022 and Jun/2021, values in millions of USD.**

| Degree of Complexity | Value of Imp. 21 | % of Total 21 | Value of Imp. 22 | % of Total 22 | % Change 21/22 |
| :---: | :---: | :---: | :---: | :---: | :---: |
| Low | 6,72 | $0,54 \%$ | 7,56 | $0,46 \%$ | $12,5 \%$ |
| Medium-low | 79,58 | $6,34 \%$ | 99,47 | $6,08 \%$ | $24,99 \%$ |
| Medium-high | 908,41 | $72,43 \%$ | 1209,8 | $73,94 \%$ | $33,18 \%$ |
| High | 256,26 | $20,43 \%$ | 302,1 | $18,46 \%$ | $17,89 \%$ |
| Total | 1244,25 |  | 1611,37 |  |  |

There were increases and decreases in the values imported in different complexity categories. The low-complexity category saw an increase of **12.5%**, the medium-low category saw an increase of **24.99%**, the medium-high category saw an increase of **33.18%** and the high-complexity category saw an increase of **17.89%**. Imports of medium-high and high complexity goods accounted for over **92.4%** of all imported products.

Table 4 shows the MRC's trade balance data for the last 12 months.

**Table 4 - Regional Trade Balance 2022: Values in Millions of USD/FOB.**

| Month/Year | Value of Exp. | $\%$ EXP. RMC/SP | Value of Imp. | $\%$ IMP RMC/SP | Balance MRC | Balance SP |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| JUL/21 | 408,68 | $9,04 \%$ | 1394,07 | $23,58 \%$ | $-985,39$ | $-1390,74$ |
| AUG/21 | 447,77 | $9,27 \%$ | 1440,67 | $24,15 \%$ | $-992,90$ | $-1136,84$ |
| SEP/21 | 459,52 | $8,29 \%$ | 1412,22 | $23,74 \%$ | $-952,69$ | $-402,91$ |
| OCT/21 | 406,32 | $8,61 \%$ | 1341,16 | $24,19 \%$ | $-934,84$ | $-826,23$ |
| NOV/21 | 405,50 | $8,27 \%$ | 1357,10 | $23,4 \%$ | $-951,60$ | $-896,58$ |
| DEC/21 | 432,41 | $7,68 \%$ | 1210,56 | $21,23 \%$ | $-778,15$ | $-71,18$ |
| JAN/22 | 317,73 | $7,48 \%$ | 1204,28 | $22,67 \%$ | $-886,56$ | $-1063,40$ |
| FEB/22 | 385,43 | $7,64 \%$ | 1276,75 | $22,35 \%$ | $-891,32$ | $-669,31$ |
| MAR/22 | 463,84 | $7,36 \%$ | 1429,25 | $21,58 \%$ | $-965,41$ | $-320,49$ |
| APR/22 | 498,22 | $7,51 \%$ | 1287,84 | $21,06 \%$ | $-789,62$ | $516,17$ |
| MAY/22 | 525,15 | $8,18 \%$ | 1592,58 | $21,91 \%$ | $-1067,44$ | $-846,12$ |
| JUN/22 | 554,83 | $7,63 \%$ | 1636,30 | $23,76 \%$ | $-1081,48$ | $389,08$ |

Imports reached **1.63** billion dollars, while exports totaled **554.83** million. The imbalance between imports and exports resulted in a regional trade deficit of **-1.08** billion dollars - the state balance was **389.08** million in the same period.

Table 5 shows the value exported of the main products on the regional list in the 12 months to date, as well as the variation in relation to the same period in the previous year.

**Table 5 - Main products exported by the MRC in 2022 (values in millions of USD/FOB).**

| NCM | Product | Exp. value 22 | $\%$ Change 21/22 | Degree of Complexity |
| :---: | :---: | :---: | :---: | :---: |
| 8429 | Construction machinery | 154,18 | $123,25 \%$ | Medium-high |
| 3004 | Medicines | 139,21 | $6,97 \%$ | Medium-high |
| 8703 | Cars | 136,69 | $54,54 \%$ | Medium-high |
| 8414 | Air or vacuum pumps or other air compressors | 130,94 | $155,31 \%$ | Medium-high |
| 8409 | Engine parts | 96,28 | $9,01 \%$ | Medium-high |
| 8708 | Vehicle parts and accessories | 89,44 | $20,39 \%$ | Medium-high |
| 4011 | Tires | 89,40 | $20,06 \%$ | Medium-high |
| 3902 | Propylenes in their primary form | 75,11 | $23,68 \%$ | Medium-high |
| 3901 | Ethylene polymers in their primary form | 71,64 | $165,2 \%$ | Medium-high |
| 8502 | Electric generators and rotary <br> converters for motors | 70,08 | $39,72 \%$ | Medium-high |

The products in Table 5 account for approximately **38.36%** of total exports for the year. There was an increase in the value exported for all the main regional product groups.

Table 6 shows the value of imports for the main products in the region for the year as a whole, as well as the variation in relation to the same period in the previous year.

**Table 6 - Main products imported by the MRC in 2022 (values in millions of USD/FOB).**

| NCM | Product | Imp. value 22 | $\%$ Change 21/22 | Degree of Complexity |
| :---: | :---: | :---: | :---: | :---: |
| 3808 | Insecticides and agricultural products | 943,23 | $24,38 \%$ | Medium-high |
| 8542 | Electronic circuits | 627,97 | $29,85 \%$ | High |
| 2933 | Heterocyclic compounds with nitrogen | 561,87 | $62,42 \%$ | Medium-high |
| 8517 | Telephone handsets | 443,42 | $13,41 \%$ | Medium-high |
| 2931 | Other inorganic compounds | 357,61 | $307,41 \%$ | Medium-high |
| 8473 | Machine parts and accessories | 252,33 | $-1,79 \%$ | High |
| 8708 | Vehicle parts and accessories | 232,11 | $-14,54 \%$ | Medium-high |
| 2934 | Nucleic acids and their salts; other heterocyclic compounds | 186,59 | $22,84 \%$ | High |
| 3002 | Vaccines, blood | 186,49 | $39,32 \%$ | Medium-high |
| 8471 | Data processing machines | 177,77 | $30,51 \%$ | Medium-high |

The products listed in Table 6 account for approximately **47.1%** of the RMC's imports in **2022**. There was an increase in imports of almost all products, except for vehicle parts and accessories and machinery parts and accessories.

Assuming that imports are related to the economic activities of the chains in front of the products considered, there is evidence of an increase in activity for all sectors except automobiles and machinery. It is important to note that during this period there was a large increase in the prices of many imported goods, increasing the value of imports due to the price effect rather than the quantity effect.

Table 7 shows exports to the 10 main destinations in the MRC, accumulated for 2022, as well as the variation in exports by destination compared to 2021.

**Table 7 - RMC export destinations - values in millions of dollars FOB, accumulated 2022**

| Countries | Exp. 22 | % Exp. 222 | Var. 21/22 |
| :---: | :---: | :---: | :---: |
| Argentina | 540,60 | 19,69% | 42,31% |
| United States | 381,08 | 13,88% | 15,34% |
| China | 224,20 | 8,17% | 79,09% |
| Mexico | 177,71| 6,47% | 18,32% |
| Germany |	169,10| 6,16% | 25,18% |
| Chile | 161,88 | 5,9%	| 42,49% |
| Colombia | 143,74 | 5,24%	| 43,53% |
| Belguim | 108,20 | 3,94% | -17,96% |
| Peru | 87,89 | 3,2%	| 10,59% |
| Paraguay | 69,88 | 2,55% | 11,41% |

There was an increase in exports to all the main destinations. Noteworthy is the significant growth in exports to Argentina, the United States, China, and Mexico and a drop in exports to Belgium when compared to **2021**. It should be noted, however, that the poor performance of the base year favors the positive result. Table 8 shows the data for the 10 main origins of the MRC imports, accumulated for **2022**, as well as the variation in imports by origin compared to **2021**. 

**Table 8 - Origin of RMC Imports (values in millions of dollars FOB accumulated in 2022).**

| Countries | Imp. 22 | % Imp. 222 | Var. 21/22 |
| :---: | :---: | :---: | :---: |
| China | 2692,47 | 31,95% | 53,63% |
| United States | 1190,34 | 14,13% | 15,98% |
| Germany | 532,48 | 6,32% | 21,23% |
| Japan | 385,65 | 4,51% | 5,13% |
| India |	380,26 | 6,16% | -0,9% |
| South Korea | 357,91 | 4,25%	| 23,33% |
| Vietnam | 311,20 | 3,69%	| 28,52% |
| France | 238,39 | 2,83% | 9,41% |
| Mexico | 204,22 | 2,42%	| 13,17% |
| Taiwan  | 197,97 | 2,35% | 6,06% |

There was an increase in imports from China, the United States, and Germany, as well as a drop in imports from India.

Finally, Table 9 shows the trade balance data for the MRC municipalities for the last 12 months.

**Table 9 - Trade Balance of the MRC Municipalities in 2022 (values in millions of USD/FOB.)**

| Municipallity | Exp. Value 22 | % EXP RMC | Imp. Value | % IMP RMC | Trade Balance |
| :---: | :---: | :---: | :---: | :---: | :---: |
| PAULINIA | 938,91	| 17,7%	| 5247,28 |	31,64% | -4308,37 |
| CAMPINAS | 903,26 |	17,03% | 3171,24 | 19,12% |	-2267,98 |
| INDAIATUBA | 837,64 |	15,79% | 1584,01	| 9,55% |	-746,37 |
| AMERICAN | 550,03 | 10,37%	| 416,40 |	2,51%	| 133,63| 
| SUMARE | 412,33 | 7,77%	| 1187,34	| 7,16% |	-775,01 |
| VINHEDO	| 374,97 | 7,07% | 1008,15 | 6,08%	| -633,18 |
| SANTA BARBARA D'OESTE |	302,47 | 5,7% | 226,53 | 1,37%	| 75,94 |
| COSMOPOLIS |	160,33 | 3,02%	| 110,12 | 0,66% | 50,21
| ITATIBA	| 156,10 | 2,94% |	393,01 | 2,37% |	-236,91|
| SANTO ANTONIO DE POSSE | 153,47 |	2,89% |	177,43 | 1,07% | -23,96
