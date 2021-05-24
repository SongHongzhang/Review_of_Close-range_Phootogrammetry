# Review_of_Close-range_Photogrammetry

&emsp;&emsp;冲刺近景摄影测量期末考试时写的提纲和例题。

&emsp;&emsp;学艺不精、例题的解答是自己写的，非标答，可能有错误。各位可以批判性地看看，也不准备进行任何修改或者更新。（毕竟考一门丢一门）

&emsp;&emsp;放两个复习时候查到的资料：[近景摄影测量试题](https://wenku.baidu.com/view/eae27330760bf78a6529647d27284b73f34236c0.html)，根据去年学长的答卷，勉强推断出最后两道题应该是大差不差的，可能改一下模型或者数字。

&emsp;&emsp;[复习提纲](https://wenku.baidu.com/view/6e45c81b10661ed9ad51f39c)，不知道是哪位学长学姐写的复习提纲，内容和我们讲的基本差不多。

&emsp;&emsp;邮箱 2019359999@qq.com，欢迎来陪我聊天。

# 一个 LaTeX 小技巧

&emsp;&emsp;LaTeX 对于矩阵的维数给了限制，默认的维数不能超过 10

&emsp;&emsp;解决方法是，在导言区调用 amsmath 宏包，`\usepackage{amsmath}`，然后使用命令 `\setcounter{MaxMatrixCols}{20}`，看意思就知道是把矩阵的最大维数设置为 20 了，搞定

&emsp;&emsp;如果导言区没有调用 amsmath 宏包，可以正常地输入一些小矩阵，但是无法使用 `\setcounter{MaxMatrixCols}{20}`，似乎是在宏包里才设置了这个可变的参数
