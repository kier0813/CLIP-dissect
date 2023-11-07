
## Installation

1. Install Python (3.10)
1. Install Pytorch (tested with 1.12.0, also works with 2.0) and Torchvision >= 0.13 following instructions from https://pytorch.org/get-started/previous-versions/
3. Install remaining requirements using `pip install -r requirements.txt`
4. Download the Broden dataset (images only) using `bash dlbroden.sh`
5. (Optional) Download ResNet-18 pretrained on Places-365: `bash dlzoo_example.sh`

We do not provide download instructions for ImageNet data, to evaluate using your own copy of ImageNet validation set you must set 
the correct path in `DATASET_ROOTS["imagenet_val"]` variable in `data_utils.py`.

