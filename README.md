<img src="animation.gif" />
# base.py
PixelCNN on grayscale celeb/mnist/cifar 28x28.
```
python train.py --ds mnist
python train.py --ds cifar
```

Code is based on <a href="https://github.com/singh-hrituraj/PixelCNN-Pytorch" target="_new">this repository</a>.

Changes
- uses command line arguments with argparse instead of config files
- added cifar/celeb as additional datasets to mnist. 
- integrated with tensorboard 
- wrote code for inpainting
- made animation above of the generation process.  
- wrote test case for likelihood computations. 
- changed hyperparameter slightly (increased nlayers and ksize)
- simplified code and moved into a single file (except data loading). 


