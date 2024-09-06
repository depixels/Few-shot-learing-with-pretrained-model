# miniImageNet

#### baseline

* baseline-conv64 (pre-trained miniImageNet)
  + 5-way-1-shot (test)
  + 5-way-5-shot (test)√
* baseline-resnet18(pre-trained miniImageNet)
  +  5-way-1-shot(test)
  +  5-way-5-shot(test)

* baseline-conv64

  + 5-way-1-shot(test)√

  + 5-way-5-shot(test)√

* baseline-resnet18

  + 5-way-1-shot(test)√

  + 5-way-5-shot(test)√

##  使用预训练模型在漫画数据集上微调，性能明显优于直接基于漫画数据集训练。

数据消融实验。

+ 对比使用预训练文件模型微调和不适用预训练文件在漫画数据集上直接训练的模型性能。
  + 介绍预训练模型在原数据集上acc。
+ 对比不同的backbone对于实验结果的效果。
  + backbone: resnet18 v.s Conv64F (介绍框架参数量、分析特征提取效果好坏)
  + 仅采用简单baseline分类(介绍baseline、特征提取出来直接分类)

(Pre-trained v.s None)

5-way-1-shot ：Train_Acc, Test_acc

5-way-5-shot ：Train_Acc, Test_acc

使用resnet18作为backbone优于Conv64F。？

得出最优性能的best_model.pth

The structure of the residual network. Conv-64-3-1 denotes a conv layer with 64 filters of size 3 and stride 1
