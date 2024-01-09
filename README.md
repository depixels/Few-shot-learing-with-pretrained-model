# 参考自：[LibFewShot](https://arxiv.org/abs/2109.04898)

将项目精简至报告中所用模型。

Make few-shot learning easy.

## Supported Methods
### Non-episodic methods (a.k.a Fine-tuning based methods)
+ [Baseline (ICLR 2019)](https://arxiv.org/abs/1904.04232)

## Quick Installation

Please refer to [install.md](https://libfewshot-en.readthedocs.io/en/latest/install.html)([安装](https://libfewshot-en.readthedocs.io/zh_CN/latest/install.html)) for installation.

Complete tutorials can be found at [document](https://libfewshot-en.readthedocs.io/en/latest/)([中文文档](https://libfewshot-en.readthedocs.io/zh_CN/latest/index.html)).


##pth放置预训练文件
You can also find these checkpoints at [model_zoo](https://drive.google.com/drive/u/1/folders/16DWKKqjzALoq4qb8LZQ6oELD9SGlYWe_).
##result存放训练结果权重
基于miniImageNet的Conv64F和resnet18在Webcaricature上微调的5-way-1-shot和5-way-5-shot的模型权重，可以在[Google Drive](https://drive.google.com/drive/folders/1GHbIbzIZUur43WHlrOzUP7T2XPJwpXyc?usp=drive_link)中找到

## Acknowledgement
LibFewShot is an open source project designed to help few-shot learning researchers quickly understand the classic methods and code structures. We welcome other contributors to use this framework to implement their own or other impressive methods and add them to LibFewShot. This library can only be used for academic research. We welcome any feedback during using LibFewShot and will try our best to continually improve the library.

## Citation
If you use this code for your research, please cite our paper.
```
@article{li2021LibFewShot,
title = {LibFewShot: A Comprehensive Library for Few-Shot Learning},
author={Li, Wenbin and Wang, Ziyi and Yang, Xuesong and Dong, Chuanqi and Tian, Pinzhuo and Qin, Tiexin and Huo Jing and Shi, Yinghuan and Wang, Lei and Gao, Yang and Luo, Jiebo},
journal = {IEEE Transactions on Pattern Analysis &amp; Machine Intelligence},
year = {2023},
number = {01},
issn = {1939-3539},
pages = {1-18}
}
```
