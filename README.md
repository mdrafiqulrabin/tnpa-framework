# [Testing Neural Program Analyzers](https://arxiv.org/abs/1908.10711)

Neural program analyzers use (deep) neural networks to analyze programs in software engineering tasks. They take a program and make predictions about some characteristics of the program. Evaluating the robustness of neural models that process source code is of particular importance because their robustness would impact the correctness of the encompassing analyses that use them. In this study, we propose a transformation-based testing framework to test the correctness of state-of-the-art neural models running on the programming task.

| <img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/demo/npa.png" alt="NPA" width="420"/>  |  <img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/demo/workflow.png" alt="workflow" width="420"/> |
:-------------------------:|:-------------------------:
|Fig. 1. Neural Program Analyzer. | Fig. 2. An overview for testing neural program analyzers.|

- - -

# Motivating Example and Result:

| <img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/demo/example.png" alt="example" width="420"/>  |  <img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/demo/result.png" alt="result" width="420"/> |
:-------------------------:|:-------------------------:
|Fig. 3. A misprediction in [code2vec](https://github.com/tech-srl/code2vec) revealed by the loop transformation. | Fig. 4. Results of evaluating [code2vec](https://github.com/tech-srl/code2vec) on java-small/validation/libgdx project.|

- - -

# Type of Transformations:

## 1) Variable Renaming:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Variable-Renaming.png" alt="Variable-Renaming"/>

## 2) Boolean Exchange:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Boolean-Exchange.png" alt="Boolean-Exchange"/>

## 3) Loop Exchange:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Loop-Exchange.png" alt="Loop-Exchange"/>

## 4) Switch to If:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Switch-to-If.png" alt="Switch-to-If"/>

## 5) Permute Statement:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Permute-Statement.png" alt="Permute-Statement"/>

## 6) Reorder Condition:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Reorder-Condition.png" alt="Reorder-Condition"/>

## 7) Dead Code Insertion:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Dead-Code-Insertion.png" alt="Dead-Code-Insertion"/>

## 8) Log Statement Insertion:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Log-Statement-Insertion.png" alt="Log-Statement-Insertion"/>

## 9) Try Catch Insertion:
<img src="https://github.com/mdrafiqulrabin/tnpa-framework/blob/master/examples/Try-Catch-Insertion.png" alt="Try-Catch-Insertion"/>

- - -

# Citation:

[Testing Neural Program Analyzers](https://arxiv.org/abs/1908.10711)

```
@inproceedings{rabin2019tnpa,
  title={Testing Neural Program Analyzers},
  author={Rabin, Md Rafiqul Islam and  Wang, Ke and Alipour, Mohammad Amin},
  booktitle={34th IEEE/ACM International Conference on Automated Software Engineering (Late Breaking Results-Track)},
  url={https://arxiv.org/abs/1908.10711},
  year={2019}
}
```

- - -

# LBR References:

•	https://2019.ase-conferences.org/track/ase-2019-Late-Breaking-Results?track=ASE%20Late%20Breaking%20Results \
•	https://2019.ase-conferences.org/details/ase-2019-Late-Breaking-Results/17/Testing-Neural-Programs 
