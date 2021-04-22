# CycleGAN应用
使用CycleGAN网络模型实现无匹配数据的风格迁移，将真实人脸图片转换为漫画头像，主要参考了这篇[博客](https://blog.csdn.net/dqcfkyqdxym3f8rb0/article/details/106030098)。
# 开发环境
|名称| 版本|
| ------|------|
|GPU|GeForce GTX 1080 Ti|
|CUDA	|9.0|
|CUDNN	|7.1.4|
|Python	|3.6.4|
|tensorflow-gpu	|1.9.0|
|torch	|1.1.0|
|torchvision	|0.3.0|
|face-alignment	|1.0.0|
|dlib	|19.17.0|
|numpy	|1.18.4|
|opencv-python	|4.1.0.25|
# 训练方法
train.py进行模型的训练<br>
test.py测试模型的转换效果
# 参考
[junyanz/CycleGAN仓库](https://github.com/junyanz/CycleGAN)<br>
J. Zhu, T. Park, P. Isola and A. A. Efros, "Unpaired Image-to-Image Translation Using Cycle-Consistent Adversarial Networks," 2017 IEEE International Conference on Computer Vision (ICCV), Venice, 2017, pp. 2242-2251, doi: 10.1109/ICCV.2017.244.<br>
https://blog.csdn.net/dqcfkyqdxym3f8rb0/article/details/106030098<br>
https://blog.csdn.net/c9Yv2cf9I06K2A9E/article/details/79557699<br>
https://blog.csdn.net/syysyf99/article/details/100120952<br>
https://blog.csdn.net/liongxiong/article/details/80875885<br>
https://blog.csdn.net/yxpandjay/article/details/90369947<br>
https://blog.csdn.net/m0_37605642/article/details/98854753<br>
https://blog.csdn.net/sunmingyang1987/article/details/102872658<br>

