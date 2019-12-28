# ShakeDrop-Pytorch
Pytorch of the implementation of the paper "ShakeDrop regularization" (https://arxiv.org/abs/1802.02375).
# Usage
This project help you can use PyramidNet_SakeDrop model just like how you use the PyramidNet model. 
You only need join the model folder into your project,and use the PyramidNet_SakeDrop model with the simple following codes:
``` python
from model import PyramidNet_ShakeDrop
net = PyramidNet_ShakeDrop(depth=101,alpha=270,num_classes=1000)
```
