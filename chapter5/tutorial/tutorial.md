因为作业是复现教程内容，教程部分的笔记主要简单介绍一下流程步骤，具体截图看作业部分。
整体的思路是：
1、创建Conda环境，这里面可以使用studio-conda进行批量安装，也可以自己创建Conda环境从头开始安装
2、安装lmdeploy
3、使用lmdeploy可以加快推理速度
4、还可以设定相关参数对模型进行量化，可以使用KV8量化和W4A16量化，有对应的参数设定
5、lmdeploy还可以进行相关的服务部署，可以终端进行对话，也可以使用gradio页面进行对话
6、拓展部分介绍了多模态大模型也可以进行相关部署
7、最后比较了lmdeploy和传统的transfer库的推理速度，大概有6被的速度