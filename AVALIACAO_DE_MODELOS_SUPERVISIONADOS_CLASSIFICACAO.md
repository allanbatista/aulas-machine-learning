## Tabela de Predição

**TP = True Positive**
A quantidade de tudo que era classe X e foi classificado como X.

**FP = False Positive**
A quantidade de tudo que era classe **não X** e foi classificado como X.

**FN = False Negative**
A quantidade de tudo que era X e foi classificado como **não X**

**TN = True Negative**
A quantidade de tudo que era **não X** e foi classificado como **Não X**

|          | True | False |
|----------|------|-------|
| Positive | TP   | FP    |
| Negative | FN   | TN    |

## Tabela de Exemplo

|          | True | False |
|----------|------|-------|
| Positive | 50   | 30    |
| Negative | 20   | 10    |

## precision or positive predictive value (PPV)

É a proporção de tudo X classificado corretamente.

ex.: 

    precision = TP / TP + FP = 50 / 50 + 30 = 5/8

## sensitivity, recall, hit rate, or true positive rate (TPR)

É a proporção de tudo que foi classificado como X corretamente.

ex.:
        
    sensitivity = TP / TP + FN = 50 / 50 + 20 = 5/7
    
## specificity, selectivity or true negative rate (TNR)

Este é o inverso do **precision** sendo a proporção de tudo que não era X classificado corretamente.

ex.: 

    specificity = TN / TN + FP = 10 / 10 + 30 = 1/4


## ROC curve

y = sensitivity

x = 1 - specificity