# convolutional-neural-network-GUI
MNIST数据集卷积神经网络实现手写数字识别应用（GUI）

### 环境信息
* tensorflow版本为2.0.0，2.0.0以后的应该都可以运行
* 我的python版本为3.7（兼容tensorflow2.0及以上版本的Python版本应该都可以）
* Operation System:Windows10
* IDE:Pycharm
* 图片是MOOC上《人工智能实践：Tensorflow笔记》北大曹健老师https://www.icourse163.org/course/PKU-1002536002?tid=1452937471 课程中演示的那10张图片。
### 项目说明
* CNN-Model.py为卷积神经网络的训练文件。
* gui.py为图像化界面的启动文件
* checkpoin和weights.txt均为卷积神经网络的训练参数。
* recongnition.py和icon.ico不要修改。
### 执行步骤
* 训练好的checkpoint和weights.txt文件已经在仓库里面了，如果想自己训练可以直接run CNN-Model.py即可，run完也会生成checkpoint和weights.txt文件。
* 直接执行tk_gui.py文件，出现gui窗口，选择图片识别即可。
