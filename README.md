# Adversarial_Validation_Case_Study

交叉验证（Cross Validation）是常用的一种用来评估模型效果的方法。

当样本分布发生变化时，交叉验证无法准确评估模型在测试集上的效果，这导致模型在测试集上的效果远低于训练集。

通过本文，你将通过一个kaggle的比赛实例了解到，样本分布变化如何影响建模，如何通过对抗验证辨别样本的分布变化，以及有哪些应对方法。

文章链接：https://zhuanlan.zhihu.com/p/93842847


# Recommended Python packages

After my own attempts, the following versions of Python packages can run the code：

`python=3.8.18`

`numpy==1.18 pandas==1.0.5 scikit-learn==0.23.2 scipy==1.4.1 matplotlib==3.2.2 seaborn==0.10.1 tqdm==4.46.0 lightgbm==3.1.0`

## Installation command:

`pip install numpy==1.18 --no-deps`

`pip install pandas==1.0.5 scikit-learn==0.23.2 scipy==1.4.1 matplotlib==3.2.2 seaborn==0.10.1 tqdm==4.46.0 lightgbm==3.1.0 --no-deps`

## tips:
Parameter `--no-deps` Skip automatic dependency check (requires manual completion of other dependencies)
