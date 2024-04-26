# 数据挖掘作业
## 一、GitHub注册及上传
### 1、注册GitHub账号
### 2、创建仓库并上传（1）
1.创建一个新的仓库，命名为LiDongyangDataMining，并点击`Add a Readme filee`按钮  
2.在创建好的项目中，点击`Add file` &rarr; `Upload files`  
3.将桌面的PPT文件拖入文件框中，即可上传成功  
### 3、创建仓库并上传（2）
还可以通过本地命令行进行上传文件  
1.创建仓库步骤同上  
2.在新创建的仓库点击`code`&rarr;`copy url to clipboard`，将地址复制到剪切板  
3.在本地新建一个文件夹，打开命令行后输入命令"git clone + 地址"  
4.输入"git add 数据挖掘PPT-李东洋.pptx"，将文件添加到暂存区  
5.输入git commit -m "增加 数据挖掘PPT-李东洋"，提交更改到本地仓库  
6.输入"git push origin main"将更改推送到远程仓库  

## 二、想学习的计算机技能
### 希望学习到图神经网络解决过度平滑问题的方法或者创新方法
过度平滑问题是指在图神经网络（GNN）中，由于多层卷积层的堆叠，导致节点特征过度平滑，使得节点之间的差异性降低，从而影响模型的性能和泛化能力。  
当前已经有很多解决方案，但是仍然没解决，因此希望可以学习到解决方法，下面对目前的一些进展进行说明  
- 跳跃连接：类似于残差网络中的跳跃连接，可以在GNN中引入跳跃连接，使得不同层之间的特征传递更加直接，从而减轻特征过度平滑的问题。
- 图注意力机制：使用图注意力机制来加权不同层的特征，使得对节点邻居的关注程度可以根据节点的重要性动态调整，从而减轻特征过度平滑的问题。
- 自适应聚合函数：一些研究工作提出了使用自适应的聚合函数，如自注意力聚合、自适应邻域聚合等，来动态调整聚合节点邻居特征的权重，以解决过度平滑问题。
- 降维技术： 有些方法通过降维技术来减少特征维度，从而降低信息丢失和过度平滑的风险。
- 结合图结构信息：一些方法结合图的结构信息，如节点的度、路径长度等，来指导特征聚合过程，从而更好地保留节点间的差异性。
### 希望学习到将论文模块与代码对应的方法
上课时刘老师通过已经step by step演示代码，但是对于一些其他代码我仍存有疑虑  
例如当一些代码使用了框架，代码量增加后如何快速定位到有效代码  
另外，对于论文中提出的模块，名字不同，如何精准定位？

