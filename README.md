# IDCL
PyTorch implementation of Inter-Domain Curriculum Learning

## Description
![figure1](https://user-images.githubusercontent.com/44395361/114139096-8a7c5b00-9949-11eb-8a1c-dd00b4bd13e0.png)
</br>
The purpose of domain generalization is to learn a domain-invariant representation from multiple source domains so that a model can generalize well across unseen target domains. 
Such models are often trained with examples presented randomly from all source domains, making the training unstable because of optimization in conflicting gradient directions. 
Here, we explore inter-domain curriculum learning (IDCL), where the source domains are exposed in a meaningful order to gradually provide more complex ones. 
The experiments show that significant improvements can be achieved in both the PACS and Office-Home benchmarks, and ours shows a 1.08% improvement over the state-of-the-art method.

## Requirements
- python>=3.6
- torch==1.7.1
- torchvision==0.8.1

But, maybe it will work well if torch version is more than 1.2.0.

## PACS dataset (official split ver)
1. Download dataset from below link:
- https://drive.google.com/file/d/11zfQb-IAClxCHUy-EH8uVaum27fJmexT/view?usp=sharing

2. Unzip pacs_official.zip in ```IDCL/codes/```
