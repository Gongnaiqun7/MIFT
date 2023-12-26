# MIFT
A cross-view image geo-localization method based on multi-scale information and dual-channel attention mechanism
## requirement
1. Download the [University-1652](https://github.com/layumi/University1652-Baseline) dataset
2. Configuring the environment
   * First you need to configure the torch and torchision from the [pytorch](https://pytorch.org/) website
   * ```shell
     pip install -r requirement.txt
     ```
## Download pre-training weights
You can download the pre-training weight from the following link and put them in the **pretrain_model** folder

[Baidu Driver](https://pan.baidu.com/s/1PLMog6KkIgSceE6JT03AcQ?pwd=d2ds)  code: d2ds

## Train and Test
We provide scripts to complete FSRA training and testing
* Change the **data_dir** and **test_dir** paths in **train_test_local.sh** and then run:
```shell
bash train_test_local.sh
```
## Other
* You can check the accuracy results in **Checkpoints/test/result.txt**
* You can invoke **Checkpoints/test/heatmap.py** to visualize the heatmap
