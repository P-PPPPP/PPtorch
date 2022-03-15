该版本只做了一个框架；  
只支持回归问题的模型定义；  
目前已有：  
  激活函数： Relu  
  损失函数： MSE  
  功能函数：  
    random_division（）：随机打乱输入数据，将数据划分为训练/测试集  
    normalization（）：归一化  
    onehot_label（）：将数字标签转化为one hot标签  
  优化器：BGD：带有batch功能的批梯度下降优化器  
 准备加入：  
  多分类 相关内容；  
