# ST-XAD

The official pytorch implementation of ST-XAD.

The codes and dataset will be released when the paper is published.

## Environment setting：
* Python 3.6 or higher
* Pytorch 1.10 or higher

## Dataset
Download the datasets and then extract it in the file of `Data`

To download the nu-XS dataset, please refers to: http://
To download the HDD-XS dataset, please refers to: http://


To download the nuScenes raw data, you may refer to the offical site of nuScenes, then resize the image resolution or refer to the site: http: //

## Pretrained weights：
* Download the pretrained weights and then extract it in the file of `weight`
* The link for pretrained weights is: https: //

## Usage
* Clone this repo.
```
git clone 
```

* Download the dataset and put into the file of `Data`;
```
nuScenes raw data for the pre-training of Spatial-Temporal Feature Module
nu-XS for the training of whole model
```
* Download the pretrained weight and put into the file of `weight` (optional);

* To train the network, select the appropriate .py in the folder of `train`
```
