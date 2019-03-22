# waifu_recognition

[English](https://github.com/Soptq/waifu_recognition/blob/master/README.md) 
[中文版](https://github.com/Soptq/waifu_recognition/blob/master/README_ZH.md) 
[Demo](https://soptq.me/waifu_recognition_demo/)

检测动漫人物的脸和脸部关键点 

训练数据是从 [These Waifus Do Not Exist](https://www.obormot.net/demos/these-waifus-do-not-exist-alt) 上获取的, 模型在 GTX 1080TI 上训练了 12 个小时，最后达到了 96% 的准确率。 

因为 [These Waifus Do Not Exist](https://www.obormot.net/demos/these-waifus-do-not-exist-alt) 
 上的动漫图像都是头像图，所以这个模型在识别全身动漫图像上准确率会比较低。但是我同时也上传了 checkpoint ，所以如果你想要达到你想要的效果的话可以在我的 checkpoint 基础上继续训练。
 
### 测试结果 
#### 原始图像
![](https://github.com/Soptq/waifu_recognition/blob/master/test_images/image1.jpg)
![](https://github.com/Soptq/waifu_recognition/blob/master/test_images/image2.jpg)
![](https://github.com/Soptq/waifu_recognition/blob/master/test_images/image3.jpg)
![](https://github.com/Soptq/waifu_recognition/blob/master/test_images/image4.jpg)
#### 预测图像
![](https://github.com/Soptq/waifu_recognition/blob/master/test_images/0.jpg)
![](https://github.com/Soptq/waifu_recognition/blob/master/test_images/1.jpg)
![](https://github.com/Soptq/waifu_recognition/blob/master/test_images/2.jpg)
![](https://github.com/Soptq/waifu_recognition/blob/master/test_images/3.jpg)


