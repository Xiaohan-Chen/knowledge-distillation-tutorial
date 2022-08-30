## Knowledge distillation tutorial
This is a simple tutorial for knowledge distillation (KD) (source: [Distilling the Knowledge in a Neural Network](https://arxiv.org/abs/1503.02531)). 

The student model and teacher model are applied VGG11 and VGG16 respectively. If the VGG11 model was directly trained on the CIFAR10 dataset, the accuracy of the VGG11 can only achieve 58.53%. But if we introduced knowledge distillation, the accuracy achieved 67.75%, as shown below:

|            | Accuracy(%) |
|:----------:|:-----------:|
| Without KD |     58.53   |
|    KD      |    67.75    |

References:  
[1] https://nn.labml.ai/distillation/index.html  
[2] https://github.com/peterliht/knowledge-distillation-pytorch.git  
[3] [Distilling the Knowledge in a Neural Network, Hinton et al., 2015.](https://arxiv.org/abs/1503.02531)
