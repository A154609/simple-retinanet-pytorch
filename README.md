# simple retinanet pytorch version

[中文](./README_cn.md) | [English](./README.md)

## What's simple?


## Useage
```
# train
nohup python train.py --project-path confgs/xxx.yml --batch-size 16 --backbone resnet101 --train-vision --plt-env mouse_detect --checkpoints checkpoints/ --epochs 100
# predict
python predict.py --input intput-images --output output-images --checkpoint checkpoints/xxx/retinanet_99.pth --project-file confgs/xxx.yml
```
## References
https://github.com/chenyuntc/simple-faster-rcnn-pytorch  
https://github.com/yhenon/pytorch-retinanet  
