## 预测新抗原的一般流程介绍

### 新抗原的含义
首先,简单介绍一下新抗原(neoantigen)的含义,它是肿瘤细胞特异性表达而正常细胞(除了睾丸之外)的一种抗原性多肽, 它能被免疫系统的T细胞识别,从而到达特异性杀死肿瘤的效果,这也就是肿瘤的免疫治疗机理.

### 使用计算机预测新抗原的一般流程

使用计算机预测neoantigen,首先需要mutation信息,这可以从外显子WESdata中获得,其次需要对每个病人进行HLA分型,再利用抗原-MHC binding score 进行预测和筛选,最终可以用转录组水平data进一步筛选出表达的neoantigen.

其中,HLA(MHC)的分型软件可采用Polysolver, 它利用临近正常样本的WES进行HLA I型等位基因(主要是HLA-A,B,C这三类)分型;此外还有 HLAminer(基于全基因组WGS数据)和 Athlates(基于WES数据).

### in silico 计算机 预测的软件

计算机 neoantigen预测软件一般有netMHC, netMHCpan, pVAC-Seq等.


## 新抗原算法相关文献




