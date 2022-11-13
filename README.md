# awesome-chinese-text-correction
中文文本纠错相关的论文、比赛和工具。

****

### Chinese Spell Check（CSC）中文拼写检查

这个任务通常**不涉及添/删字词，只涉及替换**，所以一般输入输出的句子是等长的。

- The Past Mistake is the Future Wisdom: Error-driven Contrastive Probability Optimization for Chinese Spell Checkin
	https://openreview.net/pdf?id=DW8WNS97jP5
	2022

- Sparsity Regularization for Chinese Spelling Check
	https://openreview.net/pdf?id=lMQ2TTkQo51
	2022

- SDCL: Self-Distillation Contrastive Learning for Chinese Spell Checking
	https://arxiv.org/pdf/2210.17168
	2022
- A Chinese Spelling Check Framework Based on Reverse Contrastive Learning
	https://arxiv.org/pdf/2210.13823
	2022
- Improving Chinese Spelling Check by Character Pronunciation Prediction: The Effects of Adaptivity and Granularity
	https://arxiv.org/pdf/2210.10996
	EMNLP 2022
- Learning from the Dictionary: Heterogeneous Knowledge Guided Fine-tuning for Chinese Spell Checking
	https://arxiv.org/pdf/2210.10320
	EMNLP 2022
- uChecker: Masked Pretrained Language Models as Unsupervised Chinese Spelling Checkers
	https://arxiv.org/pdf/2209.07068
	COLING 2022
- Contextual Similarity is More Valuable than Character Similarity: An Empirical Study for Chinese Spell Checking
	https://arxiv.org/pdf/2207.09217
	2022
- General and Domain Adaptive Chinese Spelling Check with Error Consistent Pretraining
	https://arxiv.org/pdf/2203.10929
	2022
- The Past Mistake is the Future Wisdom: Error-driven Contrastive Probability Optimization for Chinese Spell Checking
	https://arxiv.org/pdf/2203.00991
	ACL 2022
- Read, Listen, and See: Leveraging Multimodal Information Helps Chinese Spell Checking
	https://arxiv.org/pdf/2105.12306
	ACL 2021
- DCSpell：A Detector-Corrector Framework for Chinese Spelling Error Correction
	https://dl.acm.org/doi/10.1145/3404835.3463050
	SIGIR 2021
- Correcting Chinese Spelling Errors with Phonetic Pre-training
	https://aclanthology.org/2021.findings-acl.198.pdf
	ACL 2021
- PLOME：Pre-trained with Misspelled Knowledge for Chinese Spelling Correctio
	https://aclanthology.org/2021.acl-long.233/
	ACL 2021
- PHMOSpell：Phonological and Morphological Knowledge Guided Chinese Spelling Check
	https://aclanthology.org/2021.acl-long.464/
	ACL 2021
- Exploration and Exploitation: Two Ways to Improve Chinese Spelling Correction Models
	https://arxiv.org/abs/2105.14813
	ACL 2021
- Dynamic Connected Networks for Chinese Spelling Check
	https://aclanthology.org/2021.findings-acl.216/
	ACL 2021
- Global Attention Decoder for Chinese Spelling Error Correction
	https://aclanthology.org/2021.findings-acl.122/
	ACL 2021
- SpellBERT: A Lightweight Pretrained Model for Chinese Spelling Check
	https://aclanthology.org/2021.emnlp-main.287/
	EMNLP 2021
- Domain-shift Conditioning using Adaptable Filtering via Hierarchical Embeddings for Robust Chinese Spell Check
	https://arxiv.org/pdf/2008.12281
	EEE/ACM TASLP
- SpellGCN: Incorporating Phonological and Visual Similarities into Language Models for Chinese Spelling Check
	https://arxiv.org/pdf/2004.14166
	ACL 2020
- Spelling Error Correction with Soft-Masked BERT
	https://arxiv.org/pdf/2005.07421
	ACL 2020
- Chunk-based Chinese Spelling Check with Global Optimization
	https://aclanthology.org/2020.findings-emnlp.184.pdf
	EMNLP 2020
- Confusionset-guided Pointer Networks for Chinese Spelling Check
	https://aclanthology.org/P19-1578/
	ACL 2019
- FASPell: A Fast, Adaptable, Simple, Powerful Chinese Spell Checker Based On DAE-Decoder Paradigm
	https://aclanthology.org/D19-5522.pdf
	EMNLP 2019
- Context-Sensitive Malicious Spelling Error Correction
	https://arxiv.org/abs/1901.07688
	WWW 2019
- A Hybrid Approach to Automatic Corpus Generation for Chinese Spelling Check
	https://aclanthology.org/D18-1273/
	EMNLP 2018
- Spelling Correction as a Foreign Language
	https://arxiv.org/pdf/1705.07371.pdf
	2017

#### 数据集：

- SIGHAN Bake-off 2013: http://ir.itc.ntnu.edu.tw/lre/sighan7csc.html
- SIGHAN Bake-off 2014: http://ir.itc.ntnu.edu.tw/lre/clp14csc.html
- SIGHAN Bake-off 2015: http://ir.itc.ntnu.edu.tw/lre/sighan8csc.html
- [Wang271K](https://github.com/sunnyqiny/Confusionset-guided-Pointer-Networks-for-Chinese-Spelling-Check/tree/master/data)

#### Chinese Grammatical Error Correction（CGEC）中文语法纠错

CGEC可以**增添/删除字词**。

- Grammatical Error Correction: A Survey of the State of the Art
	https://arxiv.org/pdf/2211.05166
	2022

- From Spelling to Grammar: A New Framework for Chinese Grammatical Error Correction
	https://arxiv.org/pdf/2211.01625
	2022

- Focus Is What You Need For Chinese Grammatical Error Correction
	https://arxiv.org/pdf/2210.12692
	2022

- SynGEC: Syntax-Enhanced Grammatical Error Correction with a Tailored GEC-Oriented Parser
	https://arxiv.org/pdf/2210.12484

	EMNLP 2022

- FCGEC: Fine-Grained Corpus for Chinese Grammatical Error Correction
	https://arxiv.org/pdf/2210.12364
	EMNLP 2022

- Linguistic Rules-Based Corpus Generation for Native Chinese Grammatical Error Correction
	https://arxiv.org/pdf/2210.10442
	EMNLP 2022

- Chinese grammatical error correction based on knowledge distillation
	https://arxiv.org/pdf/2208.00351
	2022

- Mining Error Templates for Grammatical Error Correction
	https://arxiv.org/pdf/2206.11569
	2022

- Sequence-to-Action: Grammatical Error Correction with Action Guided Sequence Generation
	https://arxiv.org/pdf/2205.10884
	AAAI 2022

- A New Evaluation Method: Evaluation Data and Metrics for Chinese Grammar Error Correction
	https://arxiv.org/pdf/2205.00217
	2022

- Pretraining Chinese BERT for Detecting Word Insertion and Deletion Errors
	https://arxiv.org/pdf/2204.12052
	2022

- MuCGEC: a Multi-Reference Multi-Source Evaluation Dataset for Chinese Grammatical Error Correction
	https://arxiv.org/pdf/2204.10994
	NAACL 2022

- "Is Whole Word Masking Always Better for Chinese BERT?": Probing on Chinese Grammatical Error Correction
	https://arxiv.org/pdf/2203.00286
	ACL 2022

- Instantaneous Grammatical Error Correction with Shallow Aggressive Decoding
	https://arxiv.org/pdf/2106.04970
	ACL 2021

- Tail-to-Tail Non-Autoregressive Sequence Prediction for Chinese Grammatical Error Correction
	https://arxiv.org/pdf/2106.01609
	ACL 2021

- Chinese Grammatical Correction Using BERT-based Pre-trained Model
	https://arxiv.org/pdf/2011.02093
	AACL-IJCNLP 2020

- Improving the Efficiency of Grammatical Error Correction with Erroneous Span Detection and Correction
	https://arxiv.org/pdf/2010.03260
	EMNLP 2020

#### 数据集：

- [NLPCC18-Task2](https://github.com/zhaoyyoo/NLPCC2018_GEC)
- [北语的CGED](https://github.com/blcuicall/cged_datasets)

### Chinese Semantic Error（CSE）中文语义错误

- Pre-Training with Syntactic Structure Prediction for Chinese Semantic Error Recognition
	https://openreview.net/pdf?id=Qm_Z1UNDPN_
	2022

### 比赛

- [2021CAAI创新创业大赛](https://2021aichina.caai.cn/track?id=5)
- [CTC2021](https://github.com/destwang/CTC2021)
- [CCL2022 中文语法纠错评测](https://github.com/blcuicall/CCL2022-CGEC)
- [文本智能校对大赛 - 飞桨AI Studio (baidu.com)](https://aistudio.baidu.com/aistudio/competition/detail/404/0/introduction)
- CGED历年的比赛

### 补充：

- GECToR -- Grammatical Error Correction: Tag, Not Rewrite
	https://arxiv.org/pdf/2005.12592v2.pdf
	ACL 2020
	虽然这篇论文是针对于英文的，但是在很多中文的比赛中都有用到它。
- 当然还有seq2seq的文本纠错。

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
