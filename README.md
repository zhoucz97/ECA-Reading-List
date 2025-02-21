
# Emotion-Cause-Analysis Reading List
This is a reading list on the task of Emotion Cause Analysis. The initial version forked from [NUSTM/ECA-Reading-List](https://github.com/NUSTM/ECA-Reading-List)


### Contents


- [1. Emotion-Cause Pair Extraction (ECPE)](#1-emotion-cause-pair-extraction-ecpe)
- [2. Emotion Cause Extraction (ECE)](#2-emotion-cause-extraction-ece)
  - [2.1 Span-level ECE](#21-span-level-ece)
  - [2.2 Clause-level ECE](#22-clause-level-ece)
  - [2.3 Multi-level ECE](#23-multi-level-ece)
- [3. Emotion Cause in Conversations](#3-emotion-cause-in-conversations)

  - [3.1 RECCON](#31-reccon)
  - [3.2 ECPEC](#32-ecpec)

- [4. Other Tasks](#4-other-tasks)
- [5. Datasets](#5-datasets)

## 1. Emotion-Cause Pair Extraction (ECPE)
1. [Pair-Based Joint Encoding with Relational Graph Convolutional Networks for Emotion-Cause Pair Extraction](https://aclanthology.org/2022.emnlp-main.358/), EMNLP 2022
2. [UECA-Prompt: Universal Prompt for Emotion Cause Analysis](https://aclanthology.org/2022.coling-1.613/), COLING 2022
   - Prompt做ECA任务，包括ECPE和ECE任务。
3. [A Multi-turn Machine Reading Comprehension Framework with Rethink Mechanism for Emotion-Cause Pair Extraction](https://aclanthology.org/2022.coling-1.584/), COLING 2022
   - 多跳MRC将ECPE任务分解。
4. Shunjie Chen, Xiaochuan Shi, Jingye Li, Shengqiong Wu, Hao Fei, Fei Li, Donghong Ji. [Joint Alignment of Multi-Task Feature and Label Spaces for Emotion Cause Pair Extraction](https://arxiv.org/abs/2209.04112). COLING2022. [[code](https://github.com/csj199813/A2Net_ECPE)]
   - 核心思想是把EE，CE和ECPE三个任务结合，使得三个任务的抽取结果不会互相冲突。
5. Weichun Huang, Yixue Yang, Xiaohui Huang, Zhiying Peng & Liyan Xiong. **[Emotion-cause pair extraction based on interactive attention](https://link.springer.com/article/10.1007/s10489-022-03873-x)**. Applied Intelligence 2022. 
6. Yinan Bao, Qianwen Ma, Lingwei Wei, Wei Zhou, Songlin Hu. **[Multi-Granularity Semantic Aware Graph Model for Reducing Position Bias in Emotion-Cause Pair Extraction](https://arxiv.org/abs/2205.02132)**. ACL findings 2022. 
7. Ting Wei Chang, Yao-Chung Fan & Arbee L.P. Chen. **[Emotion-cause pair extraction based on machine reading comprehension model](https://link.springer.com/article/10.1007/s11042-022-13110-9)**. Multimedia Tools and Applications 2022. 
8. Chenbing Li, Jie Hu, Tianrui Li, Shengdong Du & Fei Teng. **[An effective multi-task learning model for end-to-end emotion-cause pair extraction](https://link.springer.com/article/10.1007/s10489-022-03637-7)**. Applied Intelligence 2022. 
9. Shunxiang Zhang, Houyue Wu, Xin Xu, Guangli Zhu &Meng-Yen Hsieh. **[CL-ECPE: contrastive learning with adversarial samples for emotion-cause pair extraction](https://www.tandfonline.com/doi/full/10.1080/09540091.2022.2082383)**. Connection Science 2022. 
10. Chunxiao Fan; Dazhi Li; Yuexin Wu. **[Combining BERT with Bi-LSTM for Emotion-Cause Pair Extraction](https://ieeexplore.ieee.org/abstract/document/9850274/authors#authors)**. IEEE International Conference on Computer Communication and the Internet (ICCCI) 2022. 
11. Fang Chen, Ziwei Shi, Zhongliang Yang, Yongfeng Huang. **[Recurrent synchronization network for emotion-cause pair extraction](https://www.sciencedirect.com/science/article/pii/S0950705121010923)**. KBS 2022. 
12. Weichun Huang,Yixue Yang, Zhiying Peng, Liyan Xiong and Xiaohui Huang. **[Deep Neural Networks Based on Span Association Prediction for Emotion-Cause Pair Extraction](https://www.mdpi.com/1424-8220/22/10/3637/htm)**. Sensors 2022. 
13. Hang Chen, Xinyu Yang, Xiang Li. **Learning a General Clause-to-Clause Relationships for Enhancing Emotion-Cause Pair Extraction**. Arxiv 2022 [[paper](https://arxiv.org/abs/2208.13549)] 
14. Zifeng Cheng, Zhiwei Jiang, Yafeng Yin, Cong Wang, Shiping Ge, Qing Gu. **A Consistent Dual-MRC Framework for Emotion-Cause Pair Extraction**. ACM Transactions on Information Systems 2022. [[paper](https://dl.acm.org/doi/abs/10.1145/3558548)] [[code](https://github.com/zifengcheng/CD-MRC)]
15. Haolin Song, Dawei Song. **[We Know An Emotion There, But What Type Is It and What Triggers It? Towards Emotion-Cause Triplet Extraction](https://dl.acm.org/doi/abs/10.1145/3508546.3508637)**. ACAI 2021. 
16. Aaditya Singh, Shreeshail Hingane, Saim Wani, and Ashutosh Modi. **An End-to-End Network for Emotion-Cause Pair Extraction**. EACL 2021. [[paper](https://aclanthology.org/2021.wassa-1.9/)] [[code](https://github.com/Aaditya-Singh/E2E-ECPE)]
17. Chuang Fan, Chaofa Yuan, Lin Gui, Yue Zhang, Ruifeng Xu. **Multi-task Sequence Tagging for Emotion-Cause Pair Extraction via Tag Distribution Refinement**. TASLP 2021. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9457144)]
18. Zifeng Cheng, Zhiwei Jiang, Yafeng Yin, Na Li, Qing Gu. **A Unified Target-Oriented Sequence-to-Sequence Model for Emotion-Cause Pair Extraction**. TASLP 2021. [[paper](https://ieeexplore.ieee.org/document/9511845)]
19. Jiaxin Yu, Wenyuan Liu, Yongjun He, Chunyue Zhang. **A Mutually Auxiliary Multitask Model With Self-Distillation for Emotion-Cause Pair Extraction**. IEEE Access 2021.[[paper](https://doi.org/10.1109/ACCESS.2021.3057880)]
20. Wei Fan, Yuexuan Zhu, Ziyun Wei, Tianyu Yang, W. H. Ip, Yuxiang Zhang. **Order-guided deep neural network for emotion-cause pair prediction**. Applied Soft Computing 2021.[[paper](https://www.sciencedirect.com/science/article/pii/S1568494621007390?via%3Dihub)]
21. Qixuan Sun, Yaqi Yin, Hong Yu. **A Dual-Questioning Attention Network for Emotion-Cause Pair Extraction with Context Awareness**. IJCNN 2021.[[paper](https://ieeexplore.ieee.org/document/9533767)]
22. Zhuojin Liu, Zhongxin Jin, Chaodi Wei, Xiangju Li, Shi Feng. **CoEmoCause: A Chinese Fine-Grained Emotional Cause Extraction Dataset**. WISA 2021.[[paper](https://link.springer.com/chapter/10.1007%2F978-3-030-87571-8_45)]
23. Zixiang Ding, Rui Xia, and Jianfei Yu. **ECPE-2D: Emotion-Cause Pair Extraction based on Joint Two-Dimensional Representation, Interaction and Prediction**. ACL 2020. [[paper](https://www.aclweb.org/anthology/2020.acl-main.288.pdf)] [[code](https://github.com/NUSTM/ECPE-2D)]
24. Penghui Wei, Jiahao Zhao, and Wenji Mao. **Effective Inter-Clause Modeling for End-to-End Emotion-Cause Pair Extraction**. ACL 2020. [[paper](https://www.aclweb.org/anthology/2020.acl-main.289.pdf)] [[code](https://github.com/Determined22/Rank-Emotion-Cause)]
25. Chuang Fan, Chaofa Yuan, Jiachen Du, Lin Gui, Min Yang, and Ruifeng Xu. **Transition-based Directed Graph Construction for Emotion-Cause Pair Extraction**. ACL 2020. [[paper](https://www.aclweb.org/anthology/2020.acl-main.342.pdf)] [[code](https://github.com/HLT-HITSZ/TransECPE)]
26. Chaofa Yuan, Chuang Fan, Jianzhu Bao, and Ruifeng Xu. **Emotion-Cause Pair Extraction as Sequence Labeling Based on A Novel Tagging Scheme**. EMNLP 2020. [[paper](https://www.aclweb.org/anthology/2020.emnlp-main.289.pdf)]
27. Zixiang Ding, Rui Xia, and Jianfei Yu. **End-to-End Emotion-Cause Pair Extraction Based on Sliding Window Multi-Label Learning**. EMNLP 2020. [[paper](https://www.aclweb.org/anthology/2020.emnlp-main.290.pdf)] [[code](https://github.com/NUSTM/ECPE-MLL)]
28. Zifeng Cheng, Zhiwei Jiang, Yafeng Yin, Hua Yu, and Qing Gu. **A Symmetric Local Search Network for Emotion-Cause Pair Extraction**. COLING 2020. [[paper](https://www.aclweb.org/anthology/2020.coling-main.12.pdf)]
29. Xinhong Chen, Qing Li, and Jianping Wang. **A Unified Sequence Labeling Model for Emotion Cause Pair Extraction**. COLING 2020. [[paper](https://www.aclweb.org/anthology/2020.coling-main.18.pdf)]
30. Ying Chen, Wenjun Hou, Shoushan Li, Caicong Wu, and Xiaoqiang Zhang. **End-to-End Emotion-Cause Pair Extraction with Graph Convolutional Network**. COLING 2020. [[paper](https://www.aclweb.org/anthology/2020.coling-main.17.pdf)]
31. Sixing Wu, Fang Chen, Fangzhao Wu, Yongfeng Huang, and Xing Li. **A Multi-Task Learning Neural Network for Emotion-Cause Pair Extraction**. ECAI 2020. [[paper](http://ecai2020.eu/papers/583_paper.pdf)]
32. Hao Tang, Donghong Ji, and Qiji Zhou. **Joint Multi-level Attentional Model for Emotion Detection and Emotion-cause Pair Extraction**. Neurocomputing 2020. [[paper](https://www.sciencedirect.com/science/article/pii/S092523122030566X)]
33. Rui Fan, Yufan Wang, Tingting He. **An End-to-End Multi-task Learning Network with Scope Controller for Emotion-Cause Pair Extraction**. NLPCC 2020. [[paper](https://doi.org/10.1007/978-3-030-60450-9_60)]
34. Haolin Song, Chen Zhang, Qiuchi Li, and Dawei Song. **End-to-end Emotion-Cause Pair Extraction via Learning to Link**. ArXiv 2020. [[paper](https://arxiv.org/pdf/2002.10710)]
35. Rui Xia and Zixiang Ding. **Emotion-Cause Pair Extraction: A New Task to Emotion Analysis in Texts**. ACL 2019. [[paper](https://arxiv.org/abs/1906.01267)] [[code](https://github.com/NUSTM/ECPE)]


&nbsp;
## 2. Emotion Cause Extraction (ECE)

### 2.1 Span-level ECE
1. Xiangju Li, Wei Gao, Shi Feng, Yifei Zhang, Daling Wang. **Boundary Detection with BERT for Span-level Emotion Cause Analysis**. ACL (Findings) 2021. [[paper](https://aclanthology.org/2021.findings-acl.60.pdf)] 
1. Elsbeth Turcan, Shuai Wang, Rishita Anubhai, Kasturi Bhattacharjee, Yaser Al-Onaizan, Smaranda Muresan. **Multi-Task Learning and Adapted Knowledge Models for Emotion-Cause Extraction**. ACL (Findings) 2021. [[paper](https://aclanthology.org/2021.findings-acl.348.pdf)] 
1. Xiangju Li, Wei Gao, Shi Feng, Wang Daling, and Shafiq Joty. **Span-Level Emotion Cause Analysis by BERT-based Graph Attention Network**. CIKM 2021.[[paper](https://doi.org/10.1145/3459637.3482185)] 
1. Xiangju Li, Wei Gao, Shi Feng, Wang Daling, and Shafiq Joty. **Span-level Emotion Cause Analysis with Neural Sequence Tagging**. CIKM 2021.[[paper](https://dl.acm.org/doi/10.1145/3459637.3482186)] 
1. Haoda Qian, Qiudan Li, Zaichuan Tang. **A Multi-Task MRC Framework for Chinese Emotion Cause and Experiencer Extraction**. ICANN 2021. [[paper](https://link.springer.com/chapter/10.1007%2F978-3-030-86380-7_9)] 
1. Min Li, Hui Zhao, Hao Su, YuRong Qian and Ping Li. **Emotion-cause span extraction: a new task to emotion cause identification in texts**. Applied Intelligence 2021. [[paper](https://link.springer.com/article/10.1007/s10489-021-02188-7)]
1. Shuntaro Yada, Kazushi Ikeda, Keiichiro Hoashi, and Kyo Kageura. **A bootstrap method for automatic rule acquisition on emotion cause extraction**. ICDMW 2017. [[paper](https://sentic.net/sentire2017yada.pdf)]
1. Shuangyong Song and Yao Meng. **Detecting concept-level emotion cause in microblogging**. WWW 2015. [[paper](https://arxiv.org/pdf/1504.08050)]
1. Diman Ghazi, Diana Inkpen, and Stan Szpakowicz. **Detecting emotion stimuli in emotion-bearing sentences**. CICLing 2015. [[paper](http://www.site.uottawa.ca/~diana/publications/90420152.pdf)] 
1. Kai Gao, Hua Xu, and Jiushuo Wang. **Emotion cause detection for chinese micro-blogs based on ecocc model**. PAKDD 2015. [[paper](https://link.springer.com/chapter/10.1007/978-3-319-18032-8_1)]
1. Kai Gao, Hua Xu, and Jiushuo Wang. **A rule-based approach to emotion cause detection for chinese micro-blogs**. Expert Systems with Applications 2015. [[paper](https://www.sciencedirect.com/science/article/pii/S0957417415000871)]
1. Weiyuan Li and Hua Xu. **Text-based emotion classification using emotion cause extraction**. Expert Systems with Applications 2014. [[paper](https://www.sciencedirect.com/science/article/pii/S0957417413006945)]
1. Alena Neviarouskaya and Masaki Aono. **Extracting causes of emotions from text**. IJCNLP 2013. [[paper](https://www.aclweb.org/anthology/I13-1121)]
1. Sophia Yat Mei Lee, Ying Chen, Chu-Ren Huang, and Shoushan Li. **Detecting emotion causes with a linguistic rule-based approach**. Computational Intelligence 2013. [[paper](http://www.academia.edu/download/39679985/DETECTING_EMOTION_CAUSES_WITH_A_LINGUIST20151104-12559-z8qt0h.pdf)]
1. Sophia Yat Mei Lee, Ying Chen, and Chu-Ren Huang. **A text-driven rule-based system for emotion cause detection**. NAACL-HLT 2010. [[paper](https://www.aclweb.org/anthology/W/W10/W10-0206.pdf)]

### 2.2 Clause-level ECE

1. Hanqi Yan, Lin Gui, Gabriele Pergola, Yulan He. **Position Bias Mitigation: A Knowledge-Aware Graph Model for Emotion Cause Extraction**. ACL 2021. [[paper](https://aclanthology.org/2021.acl-long.261.pdf)]
1. Guimin Hu, Guangming Lu, Yi Zhao. **Bidirectional Hierarchical Attention Networks based on Document-level Context for Emotion Cause Extraction**. EMNLP (Findings) 2021. [[paper](https://aclanthology.org/2021.findings-emnlp.51/)] 
1. Wenhui Yu, Chongyang Shi. **Emotion Cause Extraction by Combining Intra-clause Sentiment-enhanced Attention and Inter-clause Consistency Interaction**. ICCCS 2021. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9449281)] 
1. Guimin Hu, Guangming Lu and Yi Zhao. **FSS-GCN: A graph convolutional networks with fusion of semantic and structure for emotion cause analysis**. Knowledge-Based Systems 2021. [[paper](https://www.sciencedirect.com/science/article/pii/S0950705120307139)] [[code](https://github.com/LeMei/FSS-GCN)]
1. Bo Xu, Hongfei Lin, Yuan Lin, Kan Xu. **Two-stage supervised ranking for emotion cause extraction**. Knowledge-Based Systems 2021.[[paper](https://www.sciencedirect.com/science/article/pii/S0950705121004871?via%3Dihub)]
1. Yufeng Diao, Hongfei Lin, Liang Yang, Xiaochao Fan, Yonghe Chu, Di Wu, Kan Xu. **Emotion cause detection with enhanced-representation attention convolutional-context network**. Soft Comput 2021. [[paper](https://doi.org/10.1007/s00500-020-05223-w)]
1. Jing Wan, Han Ren. **Emotion Cause Detection with a Hierarchical Network**. ICICT 2021.[[paper](https://link.springer.com/chapter/10.1007%2F978-981-16-2380-6_53)]
1. Peiqin Lin, Meng Yang, Yu Gu. **A Hierarchical Inter-Clause Interaction Network for Emotion Cause Extraction**. IJCNN 2021.[[paper](https://ieeexplore.ieee.org/document/9534291)]
1. Guimin Hu, Guangming Lu, Yi Zhao. **Emotion-Cause Joint Detection: A Unified Network with Dual Interaction for Emotion Cause Analysis**. NLPCC 2020. [[paper](https://doi.org/10.1007/978-3-030-60450-9_45)]
1. Xinglin Xiao, Lei Wang, Qingchao Kong, Wenji Mao. **Social Emotion Cause Extraction from Online Texts**. ISI 2020.[[paper](https://doi.org/10.1109/ISI49825.2020.9280532)]
1. Yufeng Diao, Hongfei Lin, Liang Yang, Xiaochao Fan, Yonghe Chu, Di Wu, Kan Xu, Bo Xu. **Multi-granularity bidirectional attention stream machine comprehension method for emotion cause extraction**. Neural Comput 2020. [[paper](https://doi.org/10.1007/s00521-019-04308-4)]
1. Jiayuan Ding, Mayank Kejriwal. **An Experimental Study of The Effects of Position Bias on Emotion Cause Extraction**. Arxiv 2020. [[paper](https://arxiv.org/abs/2007.15066)]
1. Rui Xia, Mengran Zhang, and Zixiang Ding. **RTHN: A RNN-Transformer Hierarchical Network for Emotion Cause Extraction**. IJCAI 2019. [[paper](https://arxiv.org/abs/1906.01236)] [[code](https://github.com/NUSTM/RTHN)]
1. Zixiang Ding, Huihui He, Mengran Zhang, and Rui Xia. **From Independent Prediction to Reordered Prediction: Integrating Relative Position and Global Label Information to Emotion Cause Identification**. AAAI 2019. [[paper](https://aaai.org/ojs/index.php/AAAI/article/view/4596/4474)] [[code](https://github.com/NUSTM/PAEDGL)]
1. Chuang Fan, Hongyu Yan, Jiachen Du, Lin Gui, Lidong Bing, Min Yang, Ruifeng Xu, and Ruibin Mao. **A Knowledge Regularized Hierarchical Approach for Emotion Cause Analysis**. EMNLP-IJCNLP 2019. [[paper](https://www.aclweb.org/anthology/D19-1563.pdf)]
1. Xiangju Li, Shi Feng, Daling Wang, and Yifei Zhang. **Context-aware emotion cause analysis with multi-attention-based neural network**. Knowledge-Based Systems 2019. [[paper](https://www.sciencedirect.com/science/article/pii/S0950705119301273)]
1. Xinglin Xiao, Penghui Wei, Wenji Mao, and Lei Wang. **Context-Aware Multi-View Attention Networks for Emotion Cause Extraction**. ISI 2019. [[paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8823225)]
1. Xinyi Yu, Wenge Rong, Zhuo Zhang, Yuanxin Ouyang, and Zhang Xiong. **Multiple level hierarchical network-based clause selection for emotion cause extraction**. IEEE Access 2019. [[paper](https://ieeexplore.ieee.org/iel7/6287639/6514899/08598785.pdf)] [[code](https://github.com/deardelia/ECextraction)]
1. Bo Xu, Hongfei Lin, Yuan Lin, Yufeng Diao, Liang Yang, and Kan Xu. **Extracting emotion causes using learning to rank methods from an information retrieval perspective**. IEEE Access 2019. [[paper](https://ieeexplore.ieee.org/iel7/6287639/6514899/08625499.pdf)]
1. Jiaxing Hu, Shumin Shi, and Heyan Huang. **Combining External Sentiment Knowledge for Emotion Cause Detection**. NLPCC 2019. [[paper](http://tcci.ccf.org.cn/conference/2019/papers/345.pdf)]
1. Xiangju Li, Kaisong Song, Shi Feng, DalingWang, and Yifei Zhang. **A co-attention neural network model for emotion cause analysis with emotional context awareness**. EMNLP 2018. [[paper](https://www.aclweb.org/anthology/D18-1506)]
1. Ying Chen, Wenjun Hou, Xiyao Cheng, and Shoushan Li. **Joint learning for emotion classification and emotion cause detection**. EMNLP 2018. [[paper](https://www.aclweb.org/anthology/D18-1066)]
1. Ying Chen, Wenjun Hou, and Xiyao Cheng. **Hierarchical convolution neural network for emotion cause detection on microblogs**. ICANN 2018. [[paper](https://link.springer.com/chapter/10.1007/978-3-030-01418-6_12)]
1. 慕永利, 李旸, 王素格. **基于 E-CNN 的情绪原因识别方法**. 中文信息学报 2018. [[paper](http://jcip.cipsc.org.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=2523)]
1. 张晨, 钱涛, 姬东鸿. **基于神经网络的微博情绪识别与诱因抽取联合模型**. 计算机应用 2018. [[paper](http://www.joca.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=21853)]
1. Lin Gui, Jiannan Hu, Yulan He, Ruifeng Xu, Qin Lu, and Jiachen Du. **A question answering approach to emotion cause extraction**. EMNLP 2017. [[paper](https://arxiv.org/pdf/1708.05482)]
1. Ruifeng Xu, Jiannan Hu, Qin Lu, Dongyin Wu, and Lin Gui. **An ensemble approach for emotion cause detection with event extraction and multikernel svms**. Tsinghua Science and Technology 2017. [[paper](https://ieeexplore.ieee.org/iel7/5971803/8195337/08195347.pdf)]
1. Xiyao Cheng, Ying Chen, and Bixiao Cheng. **An Emotion Cause Corpus for Chinese Microblogs with Multiple-User Structures**. TALLIP 2017. [[paper](http://ir.nsfc.gov.cn/paperDownload/ZD4360642.pdf)]
1. Qinghong Gao, Jiannan Hu, Ruifeng Xu, Lin Gui, Yulan He, Qin Lu, and Kam-Fai Wong. **Overview of NTCIR-13 ECA task**. NTCIR-13 2017. [[paper](https://research.nii.ac.jp/ntcir/workshop/OnlineProceedings13/pdf/ntcir/01-NTCIR13-OV-ECA-GaoQ.pdf)]
1. Xiangju Li, Shi Feng, Daling Wang, and Yifei Zhang. **Decision Tree Method for the NTCIR-13 ECA Task**. NTCIR-13 2017. [[paper](https://research.nii.ac.jp/ntcir/workshop/OnlineProceedings13/pdf/ntcir/03-NTCIR13-ECA-LiX.pdf)]
1. Han Ren, Yafeng Ren, and Jing Wan. **The GDUFS System in NTCIR-13 ECA Task**. NTCIR-13 2017. [[paper](http://research.nii.ac.jp/ntcir/workshop/OnlineProceedings13/pdf/ntcir/04-NTCIR13-ECA-RenH.pdf)]
1. Maofu Liu, Linxu Xia, Zhenlian Zhang, and Yang Fu. **WUST CRF-Based System at NTCIR-13 ECA Task**. NTCIR-13 2017. [[paper](http://research.nii.ac.jp/ntcir/workshop/OnlineProceedings13/pdf/ntcir/02-NTCIR13-ECA-LiuM.pdf)]
1. Lin Gui, Dongyin Wu, Ruifeng Xu, Qin Lu, and Yu Zhou. **Event-driven emotion cause extraction with corpus construction**. EMNLP 2016. [[paper](https://www.aclweb.org/anthology/D16-1170.pdf)]
1. Lin Gui, Ruifeng Xu, Qin Lu, Dongyin Wu, and Yu Zhou. **Emotion cause extraction, a challenging task with corpus construction**. In Chinese National Conference on Social Media Processing, 2016. [[paper](https://link.springer.com/chapter/10.1007/978-981-10-2993-6_8)]
1. Lin Gui, Li Yuan, Ruifeng Xu, Bin Liu, Qin Lu, and Yu Zhou. **Emotion cause detection with linguistic construction in chinese weibo text**. NLPCC 2014. [[paper](https://pdfs.semanticscholar.org/2da2/0f0afa18bf2dd2e89978f612e22cd1359fdb.pdf)]
1. 李逸薇, 李寿山, 黄居仁, 高伟. **基于序列标注模型的情绪原因识别方法**. 中文信息学报 2013. [[paper](https://core.ac.uk/download/pdf/78761760.pdf)]
1. Irene Russo, Tommaso Caselli, Francesco Rubino, Ester Boldrini, and Patricio Mart´ınez-Barco. **Emocause: an easy-adaptable approach to emotion cause contexts**. WASSA 2011. [[paper](https://rua.ua.es/dspace/bitstream/10045/22495/1/2011_Russo_HLT.pdf)]
1. Ying Chen, Sophia Yat Mei Lee, Shoushan Li, and Chu-Ren Huang. **Emotion cause detection with linguistic constructions**. COLING 2010. [[paper](https://www.aclweb.org/anthology/C10-1021)]

### 2.3 Multi-level ECE
1. Xiangju Li, Shi Feng, Yifei Zhang, Daling Wang. **Multi-level Emotion Cause Analysis by Multi-head Attention Based Multi-task Learning**. CCL 2021. [[paper](https://link.springer.com/chapter/10.1007%2F978-3-030-84186-7_6)] 

## 3. Emotion Cause in Conversations

### 3.1 RECCON

1. Recognizing Emotion Cause in Conversations. **Cognitive Computation 2021**. [[paper](https://arxiv.org/pdf/2012.11820.pdf)] [[code](https://github.com/declare-lab/conv-emotion/tree/master/emotion-cause-extraction)].
2. Neutral Utterances are Also Causes: Enhancing Conversational Causal Emotion Entailment with Social Commonsense Knowledge. **IJCAI 2022**  [[paper](https://www.ijcai.org/proceedings/2022/584)] [[code](https://github.com/LeqsNaN/KEC)]
3. [TSAM: A Two-Stream Attention Model for Causal Emotion Entailment](https://aclanthology.org/2022.coling-1.588/), **COLING 2022**. [[code](https://github.com/BladeDancer957/TSAM)]
4. Knowledge-Bridged Causal Interaction Network for Causal Emotion Entailment. **AAAI 2023**. [[paper](https://arxiv.org/pdf/2212.02995.pdf)]

### 3.2 ECPEC

1. ECPEC: Emotion-Cause Pair Extraction in Conversations. **Affective Computing 2022**. 提出了对话场景中的ECPE任务，并标注了IEMOCAP数据集。
2. Discourse-Aware Emotion Cause Extraction in Conversations. **Arxiv 2022**. 使用RECCON数据集做ECPE。
3. 【多模态】Multimodal Emotion-Cause Pair Extraction in Conversations. **Affective Computing 2022**. 提出了基于对话场景的多模态ECPE任务，标注了老友记数据集。





## 4. Other Tasks

1. Hyunwoo Kim, Byeongchang Kim, Gunhee Kim. **Perspective-taking and Pragmatics for Generating Empathetic Responses Focused on Emotion Causes**. EMNLP 2021.  [[paper](https://arxiv.org/abs/2109.08828)] [[code](https://github.com/skywalker023/focused-empathy)]
1. Jun Gao, Yuhan Liu, Haolin Deng, Wei Wang, Yu Cao, Jiachen Du, Ruifeng Xu. **[Improving Empathetic Response Generation by Recognizing Emotion Cause in Conversations](https://aclanthology.org/2021.findings-emnlp.70.pdf)**. EMNLP-findings 2021.  
1. Yanran Li, Ke Li, Hongke Ning, Xiaoqiang Xia, Yalong Guo, Chen Wei, Jianwei Cui, Bin Wang. **[Towards an Online Empathetic Chatbot with Emotion Causes](https://dl.acm.org/doi/abs/10.1145/3404835.3463042)**. SIGIR 2021. 

1. Fanfan Wang, Zixiang Ding, Rui Xia, Zhaoyu Li, Jianfei Yu. **Multimodal Emotion-Cause Pair Extraction in Conversations**. CoRR 2021. [[paper](https://arxiv.org/abs/2110.08020)] 
1. Hongliang Bi and Pengyuan Liu. **ECSP: A New Task for Emotion-Cause Span-Pair Extraction and Classification**. ArXiv 2020. [[paper](https://arxiv.org/pdf/2003.03507)]
1. Xinhong Chen, Qing Li and JianpingWang. **Conditional Causal Relationships between Emotions and Causes in Texts**. EMNLP 2020. [[paper](https://www.aclweb.org/anthology/2020.emnlp-main.252.pdf)] [[code](https://github.com/mark-xhchen/Conditional-ECPE)]



## 5. Datasets
| Dataset | Emotion Categories | Annotated Roles | Size | Description |
| ----- | ----- | ----- | ----- | ----- | 
| Chinese EC Corpus <br />Lee et al., 2010b <br />[[paper](https://www.researchgate.net/profile/Chu-Ren_Huang/publication/220746716_Emotion_Cause_Events_Corpus_Construction_and_Analysis/links/0912f508ff080541ac000000/Emotion-Cause-Events-Corpus-Construction-and-Analysis.pdf)] | 5 <br />Turner: {happiness, sadness, fear, anger, surprise} | emotion cue, cause | 5,964 instances | Each **Chinese** instance contains 3 sentences extracted from the Sinica Corpus and 3,460 instances are annotated with emotion cause. | 
| It-EmoContext <br /> Russo et al., 2011 <br />[[paper](https://rua.ua.es/dspace/bitstream/10045/22495/1/2011_Russo_HLT.pdf)] | 7<br />Ekman: {happiness, sadness, fear, anger, surprise, disgust} + {underspecified} | emotion cue, cause | 6,000 instances | Each instance contains 3 sentences which are extracted from the La Repubblica Corpus based on the **Italian** emotion keywords. |
| Corpus of Emotion Causes <br />Neviarouskaya and Aono, 2013 <br />[[paper](https://www.aclweb.org/anthology/I13-1121)] | 22 | emotion cue, experiencer, cause, polarity of cause events, linguistic relation between EC | 532 instances | The dataset contains 22 sentences from (Ortony et al., 1988) for 22 emotion type and 510 sentences with emotion tokens and explicitly mentioned causes from online ABBYY Lingvo dictionary. |
| Weibo EC Corpus 1 <br />Gui et al., 2014<br />[[paper](https://pdfs.semanticscholar.org/2da2/0f0afa18bf2dd2e89978f612e22cd1359fdb.pdf)]| 7<br />Ekman + {like} | emotion cue, cause | 1,333 posts | This is the first corpus for ECE from **Chinese** Weibo text based on NLPCC13 dataset. | 
| Weibo EC Corpus 2 <br />Li and Xu, 2014 <br />[[paper](https://www.sciencedirect.com/science/article/pii/S0957417413006945)]| 6<br />Ekman | emotion cue, cause | 16,485 posts | The dataset contains 16,485 **Chinese** Weibo posts, only 1,305 of which are labeled with emotion causes. | 
| Electoral-Tweets <br />Mohammad et al., 2014 <br />[[paper](https://www.aclweb.org/anthology/W14-2607.pdf)] [[data](http://www.purl.org/net/PoliticalTweets2012)]| 8<br />Plutchik: {happiness, sadness, fear, anger, surprise, disgust, trust, anticipation} | emotion stimulus, experiencer | 4,058 tweets | This dataset consists of annotated tweets pertaining to the 2012 US presidential elections. |
| Emotion-Stimulus <br />Ghazi et al., 2015<br />[[paper](http://www.site.uottawa.ca/~diana/publications/90420152.pdf)] [[data](http://www.site.uottawa.ca/~diana/resources/emotion_stimulus_data/)]| 7<br />Ekman + {shame} | emotion cause | 2,414 sentences | This dataset consists of 820 sentences which are annotated with emotions and causes, and 1,594 sentences which are marked only with emotion. | 
| SINA-City-News<br />(EC benchmark corpus) <br />Gui et al., 2016a<br />[[paper](https://www.aclweb.org/anthology/D16-1170.pdf)] [[data](http://119.23.18.63/?page%20id=694)] | 6<br />Ekman | emotion cue, cause | 2,105 instances | The dataset consists of **Chinese** city news from SINA NEWS website. Each instance contains only one emotion keyword and at least one emotion cause. | 
| Weibo EC Corpus 3 <br />Cheng et al., 2017<br />[[paper](http://ir.nsfc.gov.cn/paperDownload/ZD4360642.pdf)] [[data](https://github.com/Wenjun-Hou/Weibo-Emotion-Corpus)]| 4<br />{joy, angry, sad, fearful} | emotion cue, cause, experiencer | 4,000 posts | This dataset contains 7,000 tweets sampled from **Chinese** Sina microblog and their 10,700 subtweets, many of which have the multiple-user structure. | 
| Japanese EC Corpora <br />Yada et al., 2017<br />[[paper](https://sentic.net/sentire2017yada.pdf)]| / | emotion word, cause, cue phrase between emotion and cause | 1,000 * 3 sentences | Three datasets containing 1,000 sentences with emotion words were sampled from **Japanese** newspaper articles, web news articles and Q&A site texts. | 
| NTCIR-13_ECA Corpora<br />(Chines city news /<br />English novel) <br />Gao et al., 2017<br />[[paper](https://research.nii.ac.jp/ntcir/workshop/OnlineProceedings13/pdf/ntcir/01-NTCIR13-OV-ECA-GaoQ.pdf)] [[data](http://119.23.18.63/ECA.html)]| 6<br />Ekman | emotion cue, cause | 2,619/<br />2,403 instances | The two corpora are constructed from **Chinese** SINA news and English novel text respectively, in which each instance contains multiple clauses. | 
| Weibo EC Corpus 4 <br />张晨 et al., 2018<br />[[paper](http://www.joca.cn/CN/article/downloadArticleFile.do?attachType=PDF&id=21853)]| 6<br />Ekman | emotion cause | 6,771 posts | The **Chinese** posts all contain emojis which are labeled with emotions and corresponding clause-level emotion causes are also annotated. | 
| REMAN <br />Kim and Klinger, 2018<br />[[paper](https://www.aclweb.org/anthology/C18-1114.pdf)] [[data](http://www.ims.uni-stuttgart.de/data/reman)]| 9<br />Plutchik + {other} | emotion cue, cause, experiencer, target | 1,720 instances | Each instance contains consecutive triples of sentences which are sampled from literature (200 books from Project Gutenberg). | 
| GoodNewsEveryone <br />Bostan et al., 2019[[paper](http://www.lrec-conf.org/proceedings/lrec2020/pdf/2020.lrec-1.194.pdf)] [[data](http://www.romanklinger.de/data-sets/GoodNewsEveryone.zip)]| 15<br />extended Plutchik: {anger, annoyance, disgust, fear, guilt, joy, love, pessimism, negative surprise, optimism, positive surprise, pride, sadness, shame, trust} | emotion cue, cause, experiencer, target, intensity, reader emotion | 5,000 headlines | The dataset consists of annotated English news headlines. | 
|CoEmoCause <br />Liu et al., 2021[[paper](https://link.springer.com/chapter/10.1007%2F978-3-030-87571-8_45)] [[data](https://github.com/neuChatbotDS/CoEmoCause-Dataset)]| 9<br />Ekman + {respect, support, and anticipation} | topic category, emotion clause, cause clause | 5,195 posts | The dataset contains 5,195 COVID-19 pandemic-related discussion posts collected from Sina Weibo. | 
