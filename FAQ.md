# **FAQ**

*为解决在使用过程中出现问题在此设立FAQ*:atom:

## Q：如何安装

[请查看INSTALL.md进行安装](https://github.com/Bistu-OSSDT-2024/31-Docx_AI_Assistant/blob/main/INSTALL.md)
## Q：本软件适用于什么文档，是否支持doc？

很抱歉，本程序只支持.docx文档使用😗，因为本产品使用了第三方库*python-docx*
# 请查看您安装的版本
## **独立版本**：
### Q：目前有哪些主要功能，如何使用?👓

目前可以使用的功能有：AI文档纠错，AI文档总结，AI文档修改建议
<br>
 - 1.选择文件：

打开main.exe之后选择您要*纠错/总结/修改*的文件和ai进行*纠错/总结/修改*后的文件
 - 2.文档纠错/总结

点击底下纠错/总结按钮，点击开始处理，等待UI界面按钮可以点击时，处理完成
<br>
处理完成的文件您已经选择好了😌
 - 文档修改建议

你可以选择是否输出.docx文件，如果不想输出，则输出的路径不进行选择即可
<br>
处理完成后，将弹出其的修改建议。
### Q：打开.exe文件时无反应，想要使用源码？

我们使用的是*pyinstaller*进行封装的程序，运行速度较慢请耐心你等待😳
<br>
或者可以可以使用源码**arc/main.py**进行使用🎶
<br>
使用时注意安装第三方库：
```cmd
pip install zhipuai
pip install docx
pip install tkinter
pip install ttkthemes
```
### Q：你们如何使用大模型，是否能保证数据安全

我们使用了清华大学计算机系出品的[智谱清言API](https://bigmodel.ai/)：ChatGLM4.0可以保证数据安全
<br>
我们对其模型进行了简单训练，能保证AI大模型流畅、快速的进行输出
## MSOffice插件版本

我们使用了Visual Basic .NET实现了MSOffice插件化
### Q：插件安装后如何启用？

 - 如果出现此问题请打开MSWord
 - 右击选择卡，选择**自定义功能区**
 - 把**开发工具**勾选，点击**确定**
 - 重启MSWord
 - 点击选择卡中新出现的**加载项**
 - 点击选择卡左上角的纠错与总结按钮即可使用

### Q：如何卸载加载项？

 - 请打开MSWord
 - 右击选择卡，选择**自定义功能区**
 - 选择左侧选择卡中**加载项**
 - 在下面**管理**右侧选择**COM加载项**，点击**转到**
 - 删除WordAddIn
 - 重启MSWord
<br>
