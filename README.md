# Alice-s-Adventures-in-a-differentiable-wonderland-chinese
‌[《Alice’s Adventures in a differentiable wonderland》‌是由Simone Scardapane撰写的一本关于深度神经网络的入门书籍。这本书以爱丽丝漫游仙境的故事为背景，通过爱丽丝的冒险经历来介绍深度神经网络的基本概念和设计技巧。本项目是本书的中文翻译版本。


## 前言

本书是关于（深度）神经网络的入门介绍，它是大语言模型、生成式人工智能以及许多其他应用的核心技术。由于“神经”一词带有大量历史包袱，而且神经网络实际上只是可微基元（differentiable primitives）的组合，因此我觉得称之为“可微分模型”是更容易理解的。

2009年，我几乎是偶然地发现了Yoshua Bengio关于“深度”网络的论文[Ben09]，而此时像Theano[ARAA+16]这样的自动微分库正变得流行。就像爱丽丝一样，我闯入了一个奇怪的编程领域——一个可微分的奇妙仙境，在这里，一些简单的操作，比如选择一个元素，非常复杂，而其他事情，比如识别猫，则异常简单。

我花了十多年时间阅读、实现和教授这些思想。本书是我在这个过程中学到的部分知识的粗略总结，重点介绍它们的设计和最常见的组件。由于这一领域发展迅速，我尝试在理论与代码、历史背景与最新趋势之间找到一个良好的平衡。我假设读者对机器学习和线性代数有一定的了解，但在必要时我会补充相关基础知识。

朋友们聚集吧：
是时候开始我们心爱的
爱丽丝在可微分仙境的冒险了。