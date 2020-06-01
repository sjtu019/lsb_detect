# LSB_DETECT

上海交通大学2017级 信息安全综合实践 大作业

## 隐写术

一张图片由大量像素组成。但人眼对于颜色的细微差异辨识度并不高。通过改变RGB属性的低位，可以实现在人眼无法洞察的前提下写入信息。此即为“低有效位(LSB)隐写”。

此处使用了开源parser-generator: flex&bison，作为提取出内容的检测工具。flex version : 2.6.4

当前实现了对其中的数字、字母（大小写区分）的检测和提取。

---



