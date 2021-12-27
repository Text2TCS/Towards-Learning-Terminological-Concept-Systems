# Towards Learning Terminological Concept Systems from Multilingual Natural Language Text

## Reference
Wachowiak, L., Lang, C., Heinisch, B., & Gromann, D. (2021). Towards Learning Terminological Concept Systems from Multilingual Natural Language Text. In 3rd Conference on Language, Data and Knowledge (LDK 2021). Schloss Dagstuhl-Leibniz-Zentrum für Informatik.
Chicago	[(PDF)](https://drops.dagstuhl.de/opus/volltexte/2021/14558/pdf/OASIcs-LDK-2021-22.pdf)

## Try it Out
If you just want to try out the service without using the code provided here you can use our [implementation made available on the European Language Grid](https://live.european-language-grid.eu/catalogue/tool-service/8122). However, the implemenation on the European Language Grid utilizes a slightly improved architecture as well as a different dataset for model-training; an updated description will be made available soon. 


## Architecture
Architecture for extracting terminological concepts systems from natural language.
![PicArchitecture](/architecture.png)

## Example Output
The resulting terminological concept system is returned in a TBX format as well as connected graph (see below).   
<img src="/example_output_graph.png" alt="PicExampleGraphOutput" width="400"/>

## Term Extraction Scores

|  Dataset | Precicion |  Recall |  F1 |  
|---|---|---|---|
|  TermEval2020 EN |  54.9 | 62.2  | 58.3  |   
| TermEval2020 FR |  65.4 | 51.4  | 57.6  |   
|  TermEval2020 NL |  67.9 | 71.7  | 69.8  |
|  ACL RD-TEC Annotator 1 |  74.4 | 77.2  | 75.8  |
|  ACL RD-TEC Annotator 2 |  80.1 | 79.3  | 80.0  |

## Relation Extraction Scores

|  Relation Type | Precicion |  Recall |  F1 |  
|---|---|---|---|
|  synonymy|  0.85 |  0.76 |  0.80 |   
| activityRelation (e1,e2) |  0.93 | 0.97 |  0.95 |   
|  activityRelation (e2,e1) |  0.00 | 0.00 | 0.00  |
|  associativeRelation |  0.90 | 0.92  | 0.91  |
|  causalRelation (e1,e2) | 0.90  |  0.95 |  0.92 |
|  causalRelation (e2,e1) |  0.92 |  0.91 |  0.91 |
|  genericRelation (e1,e2) |  0.90 | 0.93  | 0.92  |
|  genericRelation (e2,e1) |  0.46 | 0.41  | 0.43  |
|  instrumentalRelation (e1,e2) | 0.72  | 0.68  |  0.70 |
|  instrumentalRelation (e2,e1) |  0.85 |  0.88 |  0.86 |
|  none | 0.69  |  0.44 |  0.54 |
|  originationRelation (e1,e2) | 0.83  |  0.89 |  0.86 |
|  originationRelation (e2,e1) |  0.84|  0.83 | 0.83  |
|  partitiveRelation (e1,e2) |  0.90 |  0.85 |  0.87 |
|  partitiveRelation (e2,e1) |  0.77 |  0.77 |  0.77 |
|  spatialRelation (e1,e2) |  0.90 |  0.91 |  0.91 |
|  spatialRelation (e2,e1) |  0.90 |   0.82| 0.86  |
