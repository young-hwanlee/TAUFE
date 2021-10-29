# TAUFE

http://www.aitimes.kr/news/articleView.html?idxno=22895&fbclid=IwAR0kRmwyI7XER8sPSuHzEo4j9hJNXtWT-U8gtIX9zrdJrfdDPHDAQ1dGjRQ

## Task-Agnostic Undesirable Feature DeactivationUsing Out-of-Distribution Data, NeurIPS, 2021

A deep neural network (DNN) has achieved great success in many machine learning tasks by virtue of its high expressive power. However, its prediction can be easily biased to undesirable features, which are not essential for solving the target task and are even imperceptible to a human, thereby resulting in poor generalization. Leveraging plenty of undesirable features in out-of-distribution(OOD) examples has emerged as a potential solution for de-biasing such features, and a recent study shows that softmax-level calibration of OOD examples can successfully remove the contribution of undesirable features to the last fully-connected layer of a classifier. However, its applicability is confined to the classification task, and its impact on a DNN feature extractor is not properly investigated. In this paper, we propose **TAUFE**, a novel regularizer that deactivates many undesirable features using OOD examples in the feature extraction layer and thus removes the dependency on the task-specific softmax layer. To show the task-agnostic nature of **TAUFE**, we rigorously validate its performance on three tasks, classification, regression, and a mix of them, on CIFAR-10, CIFAR-100, ImageNet, CUB200, and CAR datasets. The results demonstrate that **TAUFE** consistently outperforms the state-of-the-art method as well as the baselines without regularization. 


## Requirements

- python3
- pytorch v1.8.0
