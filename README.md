
<div align="center">   

# BERT based Transformers lead the way in Extraction of Health Information from Social Media
[Sidharth R](https://github.com/RSid8), [Abhiraj Tiwari](https://github.com/abhirajtiwari), [Parthivi Choubey](https://github.com/parthivi1607), [Saisha Kashyap](https://github.com/SaishaKashyap), [Sahil Khose](https://github.com/sahilkhose), Kumud Lakara, Nishesh Singh, Ujjwal Verma
### [NAACL Paper](https://www.aclweb.org/anthology/2021.smm4h-1.5.pdf)
</div>

## Submission to SMM4H
This repo contains the codes for Task 1a, 1b, Task 6 of the Social Media Mining for Health Applications Workshop

--------------------------------------------------------------------------------------------
## Abstract
This paper describes our submissions for the Social Media Mining for Health (SMM4H)2021 shared tasks. We participated in 2 tasks:(1) Classification, extraction and normalization of adverse drug effect (ADE) mentions in English tweets (Task-1) and (2) Classification of COVID-19 tweets containing symptoms(Task-6). Our approach for the first task uses the language representation model RoBERTa with a binary classification head. For the second task, we use BERTweet, based on RoBERTa. Fine-tuning is performed on the pre-trained models for both tasks. The models are placed on top of a custom domain-specific processing pipeline. Our system ranked first among all the submissions for subtask-1(a) with an F1-score of 61%. For subtask-1(b), our system obtained an F1-score of 50% with improvements up to +8% F1 over the score averaged across all submissions. The BERTweet model achieved an F1 score of 94% on SMM4H 2021 Task-6. 

--------------------------------------------------------------------------------------------
## Results
### Task 1a
We ranked 1st on the test set (F1).
|               | Precision  | Recall | F1   |
| ---           | ---        | ---    | ---  |
| RoBERTa (our) | 0.515      | 0.752  | 0.61 |
| Median        | 0.505      | 0.409  | 0.44 |
### Task 1b
We ranked 2nd on the test set (F1).
|                       | Precision  | Recall | F1   |
| ---                   | ---        | ---    | ---  |
| en_core_web_trf (our) | 0.493      | 0.505  | 0.50 |
| Median                | 0.493      | 0.458  | 0.42 |
### Task 6 
We ranked 2nd on the test set (F1).
|                | Precision | Recall   | F1   |
| ---            | ---       | ---      | ---  |
| BERTweet (our) | 0.94      | 0.94  | 0.94 |
| Median         | 0.93      | 0.93  | 0.93 |
--------------------------------------------------------------------------------------------
## Citation
```
@inproceedings{ramesh-etal-2021-bert,
    title = "{BERT} based Transformers lead the way in Extraction of Health Information from Social Media",
    author = "Ramesh, Sidharth  and
      Tiwari, Abhiraj  and
      Choubey, Parthivi  and
      Kashyap, Saisha  and
      Khose, Sahil  and
      Lakara, Kumud  and
      Singh, Nishesh  and
      Verma, Ujjwal",
    booktitle = "Proceedings of the Sixth Social Media Mining for Health ({\#}SMM4H) Workshop and Shared Task",
    month = jun,
    year = "2021",
    address = "Mexico City, Mexico",
    publisher = "Association for Computational Linguistics",
    url = "https://www.aclweb.org/anthology/2021.smm4h-1.5",
    pages = "33--38",
    abstract = "This paper describes our submissions for the Social Media Mining for Health (SMM4H) 2021 shared tasks. We participated in 2 tasks: (1) Classification, extraction and normalization of adverse drug effect (ADE) mentions in English tweets (Task-1) and (2) Classification of COVID-19 tweets containing symptoms (Task-6). Our approach for the first task uses the language representation model RoBERTa with a binary classification head. For the second task, we use BERTweet, based on RoBERTa. Fine-tuning is performed on the pre-trained models for both tasks. The models are placed on top of a custom domain-specific pre-processing pipeline. Our system ranked first among all the submissions for subtask-1(a) with an F1-score of 61{\%}. For subtask-1(b), our system obtained an F1-score of 50{\%} with improvements up to +8{\%} F1 over the median score across all submissions. The BERTweet model achieved an F1 score of 94{\%} on SMM4H 2021 Task-6.",
}
```