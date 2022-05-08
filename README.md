# Data Augmentations for CIFAR100

Run the train files. For example, to run the baseline experiment of ResNet18:

```
python train.py --model resnet
```

Run the mixup experiment of ResNet18:

```
python train_mixup.py --model resnet
```

Models should be chosen from below:

```
model_options = ['lenet', 'vgg', 'resnet', 'resnext', 'wideresnet', 'regnet', 
                 'densenet', 'mobilenet', 'efficientnet', 'simpleDLA', 'shufflenet']
```
