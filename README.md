# awesome-chinese-text-correction
中文文本纠错相关的论文、比赛和工具。

****
另一个文本纠错论文仓库：<br>
https://github.com/nghuyong/text-correction-papers
****
### Chinese Spell Check（CSC）中文拼写检查

这个任务通常**不涉及添/删字词，只涉及替换**，所以一般输入输出的句子是等长的。
- An Error-Guided Correction Model for Chinese Spelling Error Correction<br>
	https://arxiv.org/pdf/2301.06323.pdf<br>
	https://github.com/ruisun1/Mask-Predict-main<br>
	2023<br>
- MDCSpell: A Multi-task Detector-Corrector Framework for Chinese Spelling Correction<br>
	https://aclanthology.org/2022.findings-acl.98.pdf<br>
	ACL2022
	
- SDCL: Self-Distillation Contrastive Learning for Chinese Spell Checking<br>
	https://arxiv.org/pdf/2210.17168.pdf<br>
	2022<br>

- The Past Mistake is the Future Wisdom: Error-driven Contrastive Probability Optimization for Chinese Spell Checkin<br>
	https://openreview.net/pdf?id=DW8WNS97jP5<br>
	2022

- Sparsity Regularization for Chinese Spelling Check<br>
	https://openreview.net/pdf?id=lMQ2TTkQo51<br>
	2022
- A Chinese Spelling Check Framework Based on Reverse Contrastive Learning<br>
	https://arxiv.org/pdf/2210.13823<br>
	2022
- Improving Chinese Spelling Check by Character Pronunciation Prediction: The Effects of Adaptivity and Granularity<br>
	https://arxiv.org/pdf/2210.10996<br>
	EMNLP 2022
- Learning from the Dictionary: Heterogeneous Knowledge Guided Fine-tuning for Chinese Spell Checking<br>
	https://arxiv.org/pdf/2210.10320<br>
	EMNLP 2022
- uChecker: Masked Pretrained Language Models as Unsupervised Chinese Spelling Checkers<br>
	https://arxiv.org/pdf/2209.07068<br>
	COLING 2022
- Contextual Similarity is More Valuable than Character Similarity: An Empirical Study for Chinese Spell Checking<br>
	https://arxiv.org/pdf/2207.09217<br>
	2022
- General and Domain Adaptive Chinese Spelling Check with Error Consistent Pretraining<br>
	https://arxiv.org/pdf/2203.10929<br>
	2022
- The Past Mistake is the Future Wisdom: Error-driven Contrastive Probability Optimization for Chinese Spell Checking<br>
	https://arxiv.org/pdf/2203.00991<br>
	ACL 2022
- Read, Listen, and See: Leveraging Multimodal Information Helps Chinese Spell Checking<br>
	https://arxiv.org/pdf/2105.12306<br>
	ACL 2021
- DCSpell：A Detector-Corrector Framework for Chinese Spelling Error Correction<br>
	https://dl.acm.org/doi/10.1145/3404835.3463050<br>
	SIGIR 2021
- Correcting Chinese Spelling Errors with Phonetic Pre-training<br>
	https://aclanthology.org/2021.findings-acl.198.pdf<br>
	ACL 2021
- PLOME：Pre-trained with Misspelled Knowledge for Chinese Spelling Correctio<br>
	https://aclanthology.org/2021.acl-long.233/<br>
	ACL 2021
- PHMOSpell：Phonological and Morphological Knowledge Guided Chinese Spelling Check<br>
	https://aclanthology.org/2021.acl-long.464/<br>
	ACL 2021
- Exploration and Exploitation: Two Ways to Improve Chinese Spelling Correction Models<br>
	https://arxiv.org/abs/2105.14813<br>
	ACL 2021
- Think Twice: A Post-Processing Approach for the Chinese Spelling Error Correction<br>
	https://pdfs.semanticscholar.org/1464/b75885f3090335d52d7852375008b6d3b721.pdf?_ga=2.5037562.853549088.1668343765-1085817804.1668343765<br>
	Applied Sciences 2021
- Dynamic Connected Networks for Chinese Spelling Check<br>
	https://aclanthology.org/2021.findings-acl.216/<br>
	ACL 2021
- Global Attention Decoder for Chinese Spelling Error Correction<br>
	https://aclanthology.org/2021.findings-acl.122/<br>
	ACL 2021
- SpellBERT: A Lightweight Pretrained Model for Chinese Spelling Check<br>
	https://aclanthology.org/2021.emnlp-main.287/<br>
	EMNLP 2021
- Domain-shift Conditioning using Adaptable Filtering via Hierarchical Embeddings for Robust Chinese Spell Check<br>
	https://arxiv.org/pdf/2008.12281<br>
	EEE/ACM TASLP
- SpellGCN: Incorporating Phonological and Visual Similarities into Language Models for Chinese Spelling Check<br>
	https://arxiv.org/pdf/2004.14166<br>
	ACL 2020
- Spelling Error Correction with Soft-Masked BERT<br>
	https://arxiv.org/pdf/2005.07421<br>
	ACL 2020
- Chunk-based Chinese Spelling Check with Global Optimization<br>
	https://aclanthology.org/2020.findings-emnlp.184.pdf<br>
	EMNLP 2020
- Confusionset-guided Pointer Networks for Chinese Spelling Check<br>
	https://aclanthology.org/P19-1578/<br>
	ACL 2019
- FASPell: A Fast, Adaptable, Simple, Powerful Chinese Spell Checker Based On DAE-Decoder Paradigm<br>
	https://aclanthology.org/D19-5522.pdf<br>
	EMNLP 2019
- Context-Sensitive Malicious Spelling Error Correction<br>
	https://arxiv.org/abs/1901.07688<br>
	WWW 2019
- A Hybrid Approach to Automatic Corpus Generation for Chinese Spelling Check<br>
	https://aclanthology.org/D18-1273/<br>
	EMNLP 2018
- Spelling Correction as a Foreign Language<br>
	https://arxiv.org/pdf/1705.07371.pdf<br>
	2017

#### 数据集：

- SIGHAN Bake-off 2013: http://ir.itc.ntnu.edu.tw/lre/sighan7csc.html
- SIGHAN Bake-off 2014: http://ir.itc.ntnu.edu.tw/lre/clp14csc.html
- SIGHAN Bake-off 2015: http://ir.itc.ntnu.edu.tw/lre/sighan8csc.html
- [Wang271K](https://github.com/sunnyqiny/Confusionset-guided-Pointer-Networks-for-Chinese-Spelling-Check/tree/master/data)

****

### Chinese Grammatical Error Correction（CGEC）中文语法纠错

CGEC可以**增添/删除字词**。
- Grammatical Error Correction: A Survey of the State of the Art<br>
2023<br>
https://arxiv.org/pdf/2211.05166v3.pdf<br>
- An Analysis of GPT-3’s Performance in Grammatical Error Correction<br>
2023<br>
https://arxiv.org/pdf/2303.14342v1.pdf<br>
- Pretraining Chinese BERT for Detecting Word Insertion and Deletion Errors<br>
https://arxiv.org/pdf/2204.12052.pdf<br>
2022<br>
- Linguistic Rules-Based Corpus Generation for Native Chinese Grammatical Error Correction<br>
	https://arxiv.org/pdf/2210.10442.pdf<br>
	EMNLP 2022<br>
	https://github.com/masr2000/CLG-CGEC<br>
- Grammatical Error Correction: A Survey of the State of the Art<br>
	https://arxiv.org/pdf/2211.05166<br>
	2022

- From Spelling to Grammar: A New Framework for Chinese Grammatical Error Correction<br>
	https://arxiv.org/pdf/2211.01625<br>
	2022

- Focus Is What You Need For Chinese Grammatical Error Correction<br>
	https://arxiv.org/pdf/2210.12692<br>
	2022

- SynGEC: Syntax-Enhanced Grammatical Error Correction with a Tailored GEC-Oriented Parser<br>
	https://arxiv.org/pdf/2210.12484<br>

	EMNLP 2022

- FCGEC: Fine-Grained Corpus for Chinese Grammatical Error Correction<br>
	https://arxiv.org/pdf/2210.12364<br>
	EMNLP 2022

- Linguistic Rules-Based Corpus Generation for Native Chinese Grammatical Error Correction<br>
	https://arxiv.org/pdf/2210.10442<br>
	EMNLP 2022

- Chinese grammatical error correction based on knowledge distillation<br>
	https://arxiv.org/pdf/2208.00351<br>
	2022

- Mining Error Templates for Grammatical Error Correction<br>
	https://arxiv.org/pdf/2206.11569<br>
	2022

- Sequence-to-Action: Grammatical Error Correction with Action Guided Sequence Generation<br>
	https://arxiv.org/pdf/2205.10884<br>
	AAAI 2022

- A New Evaluation Method: Evaluation Data and Metrics for Chinese Grammar Error Correction<br>
	https://arxiv.org/pdf/2205.00217<br>
	2022

- Pretraining Chinese BERT for Detecting Word Insertion and Deletion Errors<br>
	https://arxiv.org/pdf/2204.12052<br>
	2022

- MuCGEC: a Multi-Reference Multi-Source Evaluation Dataset for Chinese Grammatical Error Correction<br>
	https://arxiv.org/pdf/2204.10994<br>
	NAACL 2022

- "Is Whole Word Masking Always Better for Chinese BERT?": Probing on Chinese Grammatical Error Correction<br>
	https://arxiv.org/pdf/2203.00286<br>
	ACL 2022

- Instantaneous Grammatical Error Correction with Shallow Aggressive Decoding<br>
	https://arxiv.org/pdf/2106.04970<br>
	ACL 2021

- Tail-to-Tail Non-Autoregressive Sequence Prediction for Chinese Grammatical Error Correction<br>
	https://arxiv.org/pdf/2106.01609<br>
	ACL 2021

- Chinese Grammatical Correction Using BERT-based Pre-trained Model<br>
	https://arxiv.org/pdf/2011.02093<br>
	AACL-IJCNLP 2020

- Improving the Efficiency of Grammatical Error Correction with Erroneous Span Detection and Correction<br>
	https://arxiv.org/pdf/2010.03260<br>
	EMNLP 2020

#### 数据集：

- [NLPCC18-Task2](https://github.com/zhaoyyoo/NLPCC2018_GEC)
- [北语的CGED](https://github.com/blcuicall/cged_datasets)

****

### Chinese Semantic Error（CSE）中文语义错误
- CSED: A Chinese Semantic Error Diagnosis Corpus<br>
2023<br>
https://arxiv.org/pdf/2305.05183v1.pdf<br>
- Pre-Training with Syntactic Structure Prediction for Chinese Semantic Error Recognition<br>
	https://openreview.net/pdf?id=Qm_Z1UNDPN<br>
	2022
- BART based semantic correction for Mandarin(普通话) automatic speech recognition system<br>
https://arxiv.org/pdf/2104.05507.pdf<br>
2021
- Improving Pre-trained Language Models with Syntactic Dependency Prediction Task for Chinese Semantic Error Recognition<br>
https://arxiv.org/pdf/2204.07464.pdf<br>
2022
****

### 比赛

- [2021CAAI创新创业大赛](https://2021aichina.caai.cn/track?id=5)
- [CTC2021](https://github.com/destwang/CTC2021)
- [CCL2022 中文语法纠错评测](https://github.com/blcuicall/CCL2022-CGEC)
- [文本智能校对大赛 - 飞桨AI Studio (baidu.com)](https://aistudio.baidu.com/aistudio/competition/detail/404/0/introduction)
- CGED历年的比赛
- [CCL 2022 汉语学习者文本纠错评测](http://cuge.baai.ac.cn/#/ccl_yaclc) [解决方案](https://zhuanlan.zhihu.com/p/592101127)

### 补充：

- GECToR -- Grammatical Error Correction: Tag, Not Rewrite<br>
	https://arxiv.org/pdf/2005.12592v2.pdf<br>
	ACL 2020<br>
	虽然这篇论文是针对于英文的，但是在很多中文的比赛中都有用到它。
- 当然还有seq2seq的文本纠错。
- 还有一些仓库的也很全：
	- https://github.com/destwang/CTCResources

### 工具

- [pycorrector](https://github.com/shibing624/pycorrector)
- [correction](https://github.com/ccheng16/correction)
- [Cn_Speck_Checker](https://github.com/PengheLiu/Cn_Speck_Checker)
- [chinese_correct_wsd](https://github.com/taozhijiang/chinese_correct_wsd)
- [Autochecker4Chinese](https://github.com/beyondacm/Autochecker4Chinese)
- [proofreadv1](https://github.com/apanly/proofreadv1)
- [xmnlp](https://github.com/SeanLee97/xmnlp)

### 参考

- [中文拼写检测（Chinese Spelling Checking）相关方法、评测任务、榜单](https://blog.csdn.net/qq_36426650/article/details/122807019)
- [目前NLP中文文本纠错（错别字检索，修改）有什么研究？](https://www.zhihu.com/question/534495035#:~:text=中文文本纠错是针对中文文本拼写错误进行检测与纠正的一项工作，中文的文本纠错，应用场景很多，诸如输入法纠错、输入预测、ASR,后纠错等等，例如：)
- [中文文本纠错算法--错别字纠正的二三事 ](https://links.jianshu.com/go?to=https%3A%2F%2Fzhuanlan.zhihu.com%2Fp%2F40806718)
