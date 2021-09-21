# virtual_try_on_use_deep_learning
使用深度学习算法实现虚拟试衣，结合了人体姿态估计、人体分割、几何匹配和GAN，四种模型。仅仅只依赖opencv库就能运行

这套程序实现起来挺复杂的，因为它里面包含了4种深度学习模型，而且有一个自定义层CorrelationLayer，需要自己编程实现它。
主程序文件是 main.py，模型文件从百度云盘下载，
链接：https://pan.baidu.com/s/13Eic0aiMtCGY7iigjg71DQ 
提取码：xsl5
这套程序只有Python版本的，我在本地编写了C++程序，但是输出结果跟Python版本的输出结果始终不一致，
对于这个bug我还没有找到原因，因此我在github只发布python程序的
