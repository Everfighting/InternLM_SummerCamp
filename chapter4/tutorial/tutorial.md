安装xtuner对应微调工具的环境

![1](./src/1.png)

将相关模型通过软链接移动到对应的文件夹下

![2](./src/2.png)

pip安装环境剩余的包 

![3](./src/3.png)

下载微调模型对应的配置文件，编辑具体的配置和参数

![4](./src/4.png)

生成相关的数据，开始xtuner训练

![5](./src/5.png)

训练过程

![6](./src/6.png)

将训练的结果 与 原始的模型参数 进行合并 使用convert方法

![7](./src/7.png)

测试合并后的结果，指定prompt模版

![8](./src/8.png)

比较一下原始模型的结果：
![11](./src/11.png)

启动gradio界面UI的测试
![12](./src/12.png)
