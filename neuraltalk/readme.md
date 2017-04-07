
Neuraltalk(4.1k stars) 和 Neuraltalk2 (3.2 stars) 虽然不是一个机器学习的框架，是一个比较不错的机器学习应用。适合机器学习入门，GPU编程的学习，也可以利用它做一些图像识别的应用。


主要开发语言是Python，有简单易读的特点。对于图像的识别也是一个有趣的话题，操作步骤也比较简单，所以适合于初学者对于机器学习的了解。

Neuraltalk中关于机器学习部分是自己实现的，所以调试或者阅读比较容易，但是代码已经很久不维护了，现在已经迁移到Neuraltalk2中。 Neuraltalk2是基于Torch写的，更由于它是使用gpu计算的，所以速度更快。

通过阅读和使用这两个库，可以逐步学习Multimodal Recurrent Neural Networks是如何使用一句或者多句话来解释图像的。

例如：

[图片](http://cs.stanford.edu/people/karpathy/deepimagesent/):

![](http://i2.muimg.com/567571/27c6d8a4574e0058.png)

图片下面的句子是根据Neuraltalk的算法得到的对于图片的一句话描述。

[视频](https://vimeo.com/146492001)

一位开发者拿着运行着neuraltalk2的笔记本穿行在街道中，左上角会实时显示出当前环境的描述。

详情请见repo的readme.md文件。



