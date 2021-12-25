# FCOS_onnx

对FCOS模型导出onnx，导出onnx时需要将后处理部分关闭，模型forward完成后将卷积层的输出结果进行faltten，然后对后处理用python语言，以C语言的风格进行进行了重写，便于不同平台进行移植。

# 所需环境

python
onnx

# 测试结果
![image](https://user-images.githubusercontent.com/22290931/147376714-6d0e9c18-c0ca-48b9-8f2a-d7e5beeedcbe.png)
