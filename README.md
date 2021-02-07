# mosaic_repo
# 人物视频打码

## 核心功能：

导入拍摄的视频

->处理并识别视频中的人、物

->选择需要打码的物体

->打码

->导出

## 应用场景：

短视频拍摄者在处理短视频时

安卓手机端实现

## 工作计划：

2.7 完成设计文档的编写

确定设计模块、APP功能

1.完成核心模块： 工期：2.8-2.17日（后端）

其中2.8-2.9 完成demo的运行，并且熟悉如何编写。

子模块1:识别视频并提取识别的物体

子模块2:针对识别的物体进行打码处理并导出视频

2.编写前端布局，即编写完善安卓端程序（前端）

需要：画出APP设计图，并以此设计APP程序

3.补充附加模块：

模块1:摄像功能

模块2:图片批量打码功能

模块3:视频批量打码功能

模块2-3需要对识别的物体完成记忆功能

### 子模块1 ：识别视频并提取识别的物体

需要预训练一个模型，也可以在网上找到可以用的，需要来识别不同的人。

物体可以使用TFL自带的模型

在使用过程中，把出现的物体和人分成两大类。其中每个大类中对象的排序由出现的帧的个数从大到小进行排序。每一个都要。

同时，还可以通过选取视频的片段，再度根据该片段中对象出现的帧的个数从大到小进行排序。

## 参考资料：

https://www.runoob.com/android/android-studio-install.html

https://tensorflow.google.cn/lite/?hl=zh_cn

https://www.jianshu.com/p/834bf90036c3

https://blog.csdn.net/u012328159/article/details/81101074

https://github.com/tensorflow/examples/blob/master/lite/examples/object_detection/android/README.md
