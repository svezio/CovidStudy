# CovidStudy
This repository contains the models and the results  produced for the paper "Bottrighi et al., A machine learning approach for predicting high risk hospitalized patients with COVID-19 SARS-Cov-2" submitted to "BMC medical informatics and decision medicine".

THE REPOSITORY STRUCTURE IS THE FOLLOWING

```
UNSUPERVISED/  ;;unsupervised models tested  in Weka format (.model)
   |
   ├─RESULTS/ ;; unsupervised models results
   |
WHITEBOX/      ;;supervised white box models in Weka format (.model)
   |
   ├─RESULTS/
        |
        ├─10_FOLD_CROSS_VALIDATION/  ;;models results with 10-fold cross validation
        |
        ├─EXTERNAL_DATASET/          ;;models results with the external dataset from 3rd wave
        |
BLACKBOX/     ;;supervised black box models   in Weka format (.model)
   |
   ├─RESULTS/
        |
        ├─10_FOLD_CROSS_VALIDATION/  ;;models results with 10-fold cross validation
        |
        ├─EXTERNAL_DATASET/          ;;models results with the external dataset from 3rd wave
        |
```




FOR REVIEWERS ONLY

Two Weka datasets are availble:
Dataset1.arff and Dataset2.arff

Dataset1.arff contains the anonimised data recorded at the admission time of all hospitalized patients between February 24, 2020 and December 31, 2020, and approximately refers to the first and the second pandemic waves. The purged dataset contains 824 records.

Dataset2.arff refers to the first 100 cases observed during the third wave, in the course of the spreading of the  Delta variant (B.1.617.2), collected from February 15, 2021 to April 4, 2021. The purged dataset contains 77 records.
