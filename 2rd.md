# 实验二：图像增强

## 实验目的：
 学会OpenCV的基本使⽤⽅法，利⽤OpenCV等计算机库对图像进⾏平滑、滤波等操作，实现图像增强。
 </div>

## 实验内容：
### 1 导⼊图像滤波相关的依赖包：

<div align="center"> <img width="568" height="180" alt="image" src="https://github.com/user-attachments/assets/a3c3fa1e-5fad-425d-86f1-828aba779791" />
 </div>



### 2 读取原始图像并进⾏⾊彩空间转换
###代码及结果

<img width="732" height="728" alt="1" src="https://github.com/user-attachments/assets/04bc7b29-10d6-4b87-9e01-f11da56c24a9" />
<img width="856" height="519" alt="image" src="https://github.com/user-attachments/assets/c311e57b-11fc-4578-af94-2c4782a286b0" />
 </div>

###测试⼀下cv2中颜⾊空间变换

###代码及结果

<div align="center"> <img width="821" height="227" alt="image" src="https://github.com/user-attachments/assets/92f515f0-a0cf-42f6-8bfa-e54239c8bb6b" />
<div align="center"> <img width="1124" height="957" alt="image" src="https://github.com/user-attachments/assets/e46728de-0f03-4378-9740-ab2f9a57d774" />
 </div>


### 将原始图像的RBG格式转换为灰度图
<div align="center"><img width="873" height="261" alt="image" src="https://github.com/user-attachments/assets/9c12fe65-ac5a-4258-8ce6-a37ff9d9575a" />
<div align="center"><img width="1124" height="957" alt="image" src="https://github.com/user-attachments/assets/b304372f-52e6-42f5-9bec-ad2b0c3d9b76" />
 </div>



### 3 添加噪声
<div align="center"><img width="1054" height="719" alt="image" src="https://github.com/user-attachments/assets/e2f980f1-4f63-49db-a102-e530f2e56bb2" />
<div align="center"> <img width="1124" height="957" alt="image" src="https://github.com/user-attachments/assets/4af36ea3-8e75-48d8-a9a1-b39fc5d57ace" />
 </div>


### 4 图像滤波
<div align="center"><img width="1216" height="1195" alt="image" src="https://github.com/user-attachments/assets/3e291b58-6015-48f7-bdca-6d06d810e218" />
<div align="center"><img width="2560" height="1516" alt="image" src="https://github.com/user-attachments/assets/0a02d5f9-eb5c-43d3-8e4e-ef50d4905e16" />
 </div>


## 实验小结：

<p style="text-indent: 2em;">本实验完成了彩⾊图像的读取、BGR→RGB 转换以及灰度图显⽰，并在此基础上为图像添加了椒盐噪声与⾼斯噪声。

通过分别采⽤均值滤波、中值滤波以及⼿动实现的中值滤波对噪声图像进⾏去噪处理，对⽐分析了不同滤波⽅法的效果。

实验结果表明：

中值滤波对椒盐噪声的去除效果最为显著，能够有效保留图像边缘和细节； 

均值滤波更适⽤于⾼斯噪声的平滑去除；

通过本次实验，进⼀步加深了对图像噪声类型与滤波原理的理解。
实现彩⾊图像中值滤波的基本⽅法，为后续图像去噪与滤波算法的改进与优化
奠定了基础。


