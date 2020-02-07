# Momentum Contrast for Unsupervised Visual Representation Learning
Unofficial pytorch implementation of Momentum Contrast for Unsupervised Visual Representation Learning ([Paper](https://arxiv.org/abs/1911.05722)).  

## Requirements  
- PyTorch 1.4.0
- torchvision 0.5.0
- PIL 7.0.0
- matplotlib 2.0.2
- PyYAML 3.12 (Optional)  

## Dataset  
### ImageNet  
``` 
cd dataset  
wget http://www.image-net.org/challenges/LSVRC/2012/nnoupb/ILSVRC2012_img_train.tar  
tar xvf ILSVRC2012_img_train.tar  
```  

### STL-10  
PyTorch offers this dataset. See dataloader.py for details.  
