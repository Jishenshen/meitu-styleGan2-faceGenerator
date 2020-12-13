# meitu-styleGan2-faceGenerator
## — 基于StyleGAN2的人脸生成

这是基于styleGan2算法的人脸生成简单应用，由于时间的限制，styleGan2在两天内较难重新训练（如图所示，Training curves for FFHQ config F (StyleGAN2) compared to original StyleGAN using 8 GPUs）![image](https://github.com/NVlabs/stylegan2/blob/master/docs/stylegan2-training-curves.png?raw=true)

因此在参考[论文karras2019style](https://arxiv.org/abs/1812.04948)与[开源模型styleGan](https://github.com/NVlabs/stylegan2)后，在coLab中运行了[pre-trained模型](https://colab.research.google.com/drive/1NxHzGXg1D-Y9zWkiZgs_e-y2nBA1jJ-s?usp=sharing)



### 依赖说明
```
python=3.6
tensorflow==1.14 
tensorflow-gpu==1.14 
cudatoolkit==9.0 
cudnn 
```

