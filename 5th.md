# 实验五：基于 LeNet-5 卷积神经网络的手写数字识别

## 实验目的：
基于卷积神经网络 LeNet-5 和交叉熵损失函数，实现手写数字图像的识别与测试评估，掌握卷积神经网络结构设计、特征提取过程与模型训练评估的基本原理与实现方法，并通过特征图可视化理解卷积层的特征学习过程。

## 实验内容：
### LeNet-5 卷积神经网络的手写数字识别

代码展示：
<img width="1373" height="1061" alt="image" src="https://github.com/user-attachments/assets/45bc4ce4-1948-4af3-b338-70a306d58833" />
<img width="811" height="863" alt="image" src="https://github.com/user-attachments/assets/b540e9e8-5b5f-458e-a14e-2ccaeae0fa2d" />
<img width="1153" height="1080" alt="image" src="https://github.com/user-attachments/assets/a15cc539-d901-451b-ae81-20bf16e529d5" />
<img width="1019" height="747" alt="image" src="https://github.com/user-attachments/assets/f2c8912c-6f41-4261-9b21-7737adbfbd3b" />

结果展示：
<img width="2560" height="1600" alt="image" src="https://github.com/user-attachments/assets/6bc502c9-b343-4d35-8667-17c21d41a72b" />


## 实验小结：
<p style="text-indent: 2em;">本次实验基于 PyTorch 成功搭建了 LeNet-5 卷积神经网络，并使用交叉熵损失函数与 Adam 优化器完成了 MNIST 手写数字数据集的训练与测试评估。通过实验，验证了所设计的网络结构在图像分类任务上的有效性，模型在测试集上取得了理想的识别准确率。同时，通过可视化卷积层输出的特征图，直观地观察到浅层网络提取的边缘与轮廓等细节特征，以及深层网络提取的更加抽象的语义特征，进一步加深了对卷积神经网络“局部感知”与“层级特征提取”机制的理解。本次实验不仅巩固了深度学习中前向传播、反向传播及参数更新的核心原理，也为后续学习更复杂的卷积网络模型与图像识别任务奠定了坚实的实践基础。</p>

