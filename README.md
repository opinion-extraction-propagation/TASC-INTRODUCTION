# TASC-INTRODUCTION

  社会媒体的情感分类对于话题是及其敏感的，并且社会媒体包含了多样性话题，以及话题具有不可预测性，导致了情感分类器经常局限于某一个特定的话题，但是对其他话题的分类效果不佳。话题自适应情感分类器（TASC）解决了这个问题。针对大规模社会媒体开放测试数据，基于spark分布式计算平台，提出了并行的多类情感分类器。<br>

TASC-* repository 描述了TASC的相关工作，包含TASC-FeatureExtraction，TASC-PTASC，TASC-Tuples.<br>

##TASC-FeatureExtraction

TASC-FeatureExtraction repository包含针对社会媒体数据集抽取特征的过程<br>

##TASC-PTASC

TASC-PTASC repository是并行话题自适应多类情感分类算法<br>

##TASC-Tuples

TASC-Tuples repository包括抽取社会媒体数据包含的词语之间的依赖关系，抽取和扩展话题相关情感词集，生成代表用户情感的三元组<用户，情感词，目标词><br>
