# Toward Better Than Pseudo-Reference in Underwater Image Enhancement
This repository is the official PyTorch implementation.

## Running Environment  
``` 
1. python 3.8
2. pip install -r requirements.txt
``` 

## PSPL
### Test
1. rename directory **pre-trained** to **checkpoints**
2. rename directory **pre-datasets** to **datasets**
3. run command to infer(test)
    ```
     python test.py --dataroot ./datasets/unsuped --name unsuped --model unsupedmix --epoch PSPL_HRNet
    ```

## PSPL on other UIE methods

### Test
1. rename directory **pre-trained** to **checkpoints**
2. rename directory **pre-datasets** to **datasets**
3. run command to infer(test)
    ``` 
    python test.py --dataroot ./datasets/unsuped --name unsuped --model UWCNN --epoch PSPL_UWCNN
    ```
4. testing NU2Net and SemiUIR ([baidu cloud disk](https://pan.baidu.com/s/1LyffTDrB7_aX7IAanAB3uQ?pwd=gkf2), 提取码: gkf2) can follow the way (need add corresponding files) as UWCNN. 
Or you can put downloaded pre-trained model files to their's original source code projects([NU2Net](https://github.com/RQ-Wu/UnderwaterRanker), [Semi-UIR](https://github.com/Huang-ShiRui/Semi-UIR)) to inference. 


## Citation

```
Y. Liu, Q. Jiang, X. Li, T. Luo and W. Ren, "Toward Better Than Pseudo-Reference in Underwater Image Enhancement," 
in IEEE Transactions on Image Processing, vol. 34, pp. 6168-6179, 2025.

```

## Acknowledgements
- https://github.com/lewis081/CCL-Net
- https://github.com/RQ-Wu/UnderwaterRanker
- https://github.com/justwj/CLUIE-Net
- https://github.com/uf-robopi/UDepth
- https://github.com/Huang-ShiRui/Semi-UIR

- https://github.com/xahidbuffon/FUnIE-GAN
- https://github.com/CXH-Research/Pytorch-UW-IQA

- https://github.com/junyanz/pytorch-CycleGAN-and-pix2pix


