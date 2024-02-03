# topis-pretrain-102116071
## Ikjot Singh
### 3CS11
### 102116071


## Models Tested
- codellama/CodeLlama-7b-hf
- mistralai/Mistral-7B-v0.1
- h2oai/h2o-danube-1.8b-chat
- HuggingFaceH4/zephyr-7b-beta

## Evaluation parameters:
- Bert Score (precision, recall, f1 score)
- Bleu Score

## Output

Prompt  1 : Discuss the importance of early childhood education.
   Precision    Recall  F1_Score  Bleu_Score  Topsis Score  Rank
0   0.246164  0.241937  0.244125    0.127179      0.010628     3
1   0.245831  0.244135  0.245023    0.123120      0.006161     4
2   0.253092  0.255440  0.254225    0.244090      0.318706     2
3   0.254913  0.258488  0.256628    0.505612      1.000000     1


Prompt  2 : Explain the concept of differentiation in education.
   Precision    Recall  F1_Score  Bleu_Score  Topsis Score  Rank
4   0.243366  0.237680  0.240625    0.096982      0.000000     4
5   0.251576  0.253277  0.252410    0.163093      0.179213     3
6   0.249975  0.256505  0.253087    0.481029      0.986742     1
7   0.255084  0.252538  0.253878    0.258896      0.424021     2


Prompt  3 : Discuss the principles of democracy and their significance in modern politics.
    Precision    Recall  F1_Score  Bleu_Score  Topsis Score  Rank
8    0.238038  0.236913  0.237495    0.051687      0.000000     4
9    0.255984  0.258254  0.257101    0.191570      0.221559     2
10   0.256010  0.259542  0.257738    0.697424      1.000000     1
11   0.249968  0.245291  0.247666    0.059319      0.029412     3


Prompt  4 : Describe the rules and objective of soccer.
    Precision    Recall  F1_Score  Bleu_Score  Topsis Score  Rank
12   0.237232  0.227537  0.232473    0.018369      0.000000     4
13   0.259582  0.257543  0.258638    0.398382      0.715691     2
14   0.247728  0.250509  0.249116    0.032980      0.060928     3
15   0.255458  0.264411  0.259772    0.550269      0.992338     1


Prompt  5 : Discuss the health benefits of regular physical activity and sports participation.
    Precision    Recall  F1_Score  Bleu_Score  Topsis Score  Rank
16   0.243267  0.243930  0.243620    0.020946      0.000000     4
17   0.252524  0.248898  0.250785    0.046859      0.058485     3
18   0.251197  0.260201  0.255518    0.511372      0.996315     1
19   0.253012  0.246970  0.250078    0.420823      0.813573     2
