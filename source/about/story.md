# XEdu的故事

## 1.从MMEdu到XEdu

XEdu的缘起有很多版本。



版本一



上海人工智能实验室成立初期，智能中心负责人戴娟找上海交大谈国智班的相关事宜。

……

版本二



2020年，清华大学出版社的义务教育阶段信息技术教材开始修订，其中九年级分册要涉及人工智能。经过一番调研，几位主编发现小学教材可以用Mind+，高中教材绝大多数使用了Keras，那么初中呢？似乎只能选择Keras。

……



## 2.为什么要开发XEdu 

中小学的AI教育需要低门槛的框架或者工具。最常用是keras，存在如下问题： 

1）代码过于底层，如搭建神经网络 


2）离应用太遥远，解决不了真实问题 

3）有些直接可用的，又封装过度，如OpenCV； 

4）更换多个工具，门槛太高。如物体检测的Yolov3，因为基于PyTorch，采用项目式，基本上教师无法使用，再如图片风格化（学习迁移，对抗网络） 

## 3.对XEdu的期望 

1）用最好的、最先进的AI工具 


专注于计算机视觉识别，将OpenMMLab这一高校研究工具降维到中小学课堂。 

2）开箱即用的AI工具


既支持底层的网络搭建，又引入最新的SOTA模型，代码简洁，便于理解。一套工具，完成神经网络和视觉学习。 


3）真正的AI开发工具


基于PyTorch，能训练出近工业级的模型，能够解决真实问题。