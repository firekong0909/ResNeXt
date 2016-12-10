# ResNeXt
Reproduce ResNet-v3(Aggregated Residual Transformations for Deep Neural Network)


### Results

0. 1-crop validation error on ImageNet (center 224x224 crop from resized image with shorter side=256):

	model|top-1|top-5
	:---:|:---:|:---:
	[VGG-16](http://www.vlfeat.org/matconvnet/pretrained/)|[28.5%](http://www.vlfeat.org/matconvnet/pretrained/)|[9.9%](http://www.vlfeat.org/matconvnet/pretrained/)
	ResNet-50|24.7%|7.8%
	ResNet-101|23.6%|7.1%
	ResNet-152|23.0%|6.7%
        **ResNeXt-101**|**22.1**%|**5.8**%

| Network    |crop-size | top-1 |  top-5 |
| :------:   | :---: | :---: |:---: |
|ResNet-101-v1  | 224x224 |23.6|7.1|
|ResNet-101-v2  | 224x224 |24.6|7.5|
|ResNet-152-v1  | 320x320 |21.3|5.5|
|ResNet-152-v2  | 320x320 |21.1|5.5|
|ResNeXt-101    | 320x320 |20.2|4.9|

  
1. Model files:
	OneDrive download: [link](https://1drv.ms/u/s!Aqd-q_R495LrjgyQx2cKLOXKEQgN)
