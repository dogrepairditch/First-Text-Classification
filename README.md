项目描述： 
  1-训练一个基于新闻内容或标题进行文本分类的模型 
  2-训练样本1440条，验证集360条，做18分类，如家居、房产、财经，各类样本分布基本均衡  
  
关键步骤： 
  1-同时使用多种模型的多种参数进行训练，目标筛选出最佳模型及参数 
  2-模型涵盖传统方法及神经网络，包括FastText，RNN、LSTM、GRU、CNN、Gated CNN、BERT、Bert+LSTM等。调整参数包括：学习率，hidden_size，batch_size，优化器选择等 
  3-经过多轮实验即调试，最终在360条样本的验证集上，Bert模型的分类准确率达到了87%。
