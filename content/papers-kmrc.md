# Papers on Knowledge-based Machine Reading Comprehension.

A list of recent papers about **Knowledge-based Machine Reading Comprehension** (**KMRC**).

Contributed by [Luxi Xing](https://github.com/XingLuxi), [Yuqiang Xie](https://github.com/IndexFziQ) and [Wei Peng](https://github.com/a414351664).

Institute of Information Engineering, Chinese Academy of Sciences, Beijing, China. 

Update on **Aug. 12, 2020**.

(We will continuously update this list.)

-------

## [Content](#content)

1. [Cloze Style Tasks](#cloze-style-tasks)
2. [Span Extraction Tasks](#span-extraction-tasks)
3. [Multiple Choice Tasks](#multiple-choice-tasks)
4. [Generation Tasks](#generation-tasks)
5. [Others](#other-paper-list-about-mrc)
    

## [Cloze Style Tasks](#content)

| Title | Publish | Tasks | Links |
| :---- | :---: | :---- | :---:|
| Reasoning with Heterogeneous Knowledge for Commonsense Machine Comprehension | ACL<br>2017 | SCT | [paper](http://aclweb.org/anthology/D17-1216) |
| World Knowledge for Reading Comprehension: Rare Entity Prediction with Hierarchical LSTMs Using External Descriptions | EMNLP<br>2017 | Rare Entity Prediction | [paper](https://www.aclweb.org/anthology/D17-1086) |
| Knowledgeable Reader: Enhancing Cloze-Style Reading Comprehension with External Commonsense Knowledge | ACL<br>2018 | Common Nouns | [paper](http://aclweb.org/anthology/P18-1076) <br> [note](http://xingluxi.github.io/2019/01/09/paper-knreader/) |
| A Multi-Attention based Neural Network with External Knowledge for Story Ending Predicting Task | COLING<br>2018 | SCT | [paper](http://www.aclweb.org/anthology/C18-1149) |
| Incorporating Structured Commonsense Knowledge in Story Completion | AAAI<br>2018 | SCT | [paper](https://arxiv.org/abs/1811.00625) |
| Story Ending Prediction by Transferable BERT | IJCAI<br>2019 | SCT | [paper](https://arxiv.org/abs/1905.07504) |
| Toward Better Storylines with Sentence-Level Language Models | ACL<br>2020 | SCT | [paper](https://www.aclweb.org/anthology/2020.acl-main.666) |


## [Span Extraction Tasks](#content)

| Title | Publish | Tasks | Links |
| :---- | :---: | :---- | :---:|
| Dynamic Integration of Background Knowledge in Neural NLU Systems | 2018 | SQuAD/<br>TriviaQA | [paper](https://arxiv.org/pdf/1706.02596.pdf)<br>[note](http://xingluxi.github.io/2019/03/06/paper-2018-refinewordemb/) |
| Explicit Utilization of General Knowledge in Machine Reading Comprehension | ACL<br>2019 | SQuAD | [paper](https://www.aclweb.org/anthology/P19-1219) <br> [note](http://xingluxi.github.io/2019/07/17/paper-acl2019-kar/) |
| Enhancing Pre-Trained Language Representations with Rich Knowledge for Machine Reading Comprehension | ACL<br>2019 | SQuAD/<br>ReCoRD | [paper](https://www.aclweb.org/anthology/P19-1226/) <br> [note](http://xingluxi.github.io/2019/07/29/paper-acl2019-kt-net/) |
| Machine Reading Comprehension Using Structural Knowledge Graph-aware Network | EMNLP<br>2019<br>short | ReCoRD | [paper](https://www.aclweb.org/anthology/D19-1602) |
| `+` SG-Net: Syntax-Guided Machine Reading Comprehension | AAAI<br>2020 | SQuAD2.0<br>RACE | [paper](http://arxiv.org/abs/1908.05147) | 
| `+` Semantics-aware BERT for Language Understanding | AAAI<br>2020 | SQuAD2.0 | [paper](http://arxiv.org/abs/1909.02209) |
| `+` Entities as Experts: Sparse Memory Access with Entity Supervision | 2020 | TriviaQA | [paper](http://in.arxiv.org/abs/2004.07202) |
| `+` Semantics-Aware Inferential Network for Natural Language Understanding | 2020 | * | [paper](http://arxiv.org/abs/2004.13338) |

* `+` indicates works regarding injecting knowledge to improve performance on the datasets not included in this summary.


## [Multiple Choice Tasks](#content)

| Title | Publish | Tasks | Links |
| :---- | :---: | :---- | :---:|
| Yuanfudao at SemEval-2018 Task 11: Three-way Attention and Relational Knowledge for Commonsense Machine Comprehension | SemEval<br>2018 | SemEval-2018 Task 11 | [paper](https://www.aclweb.org/anthology/S18-1120/) <br> [code](https://github.com/intfloat/commonsense-rc) |
| Improving Question Answering by Commonsense-Based Pre-Training | AAAI<br>2019 | ARC/<br>OpenBookQA/<br>SemEval-2018 Task 11 | [paper](https://arxiv.org/abs/1809.03568) |
| Improving Machine Reading Comprehension with General Reading Strategies | NAACL<br>2019 | ARC/ OpenBookQA/ MCTest/<br>SemEval-2018 Task 11/ SCT/ MultiRC | [paper](https://www.aclweb.org/anthology/N19-1270/) <br> [code](https://github.com/nlpdata/strategy/) |
| Ranking and Selecting Multi-Hop Knowledge Paths to Better Predict Human Needs | NAACL<br>2019 | story commonsense | [paper](https://www.aclweb.org/anthology/papers/N/N19/N19-1368/) <br> [code](https://github.com/debjitpaul/Multi-Hop-Knowledge-Paths-Human-Needs) |
| Incorporating Relation Knowledge into Commonsense Reading Comprehension with Multi-task Learning | CIKM<br>2019 | SemEval-2018 Task 11 / SCT | [paper](https://arxiv.org/abs/1908.04530) |
| Explain Yourself! Leveraging Language Models for Commonsense Reasoning | ACL<br>2019 | CSQA | [paper](https://www.aclweb.org/anthology/P19-1487.pdf) <br> [code](https://github.com/salesforce/cos-e) <br> [note](http://xingluxi.github.io/2019/07/10/paper-acl2019-cos-e/) |
| Careful Selection of Knowledge to solve Open Book Question Answering | ACL<br>2019 | OpenBookQA | [paper](https://arxiv.org/abs/1907.10738) |
| Improving Question Answering with External Knowledge | EMNLP<br>MRQA<br>2019 | ARC/<br>OpenBookQA | [paper](https://arxiv.org/pdf/1902.00993.pdf) <br> [note](http://xingluxi.github.io/2019/08/26/paper-2019-edl-md/) |
| KagNet: Knowledge-Aware Graph Networks for Commonsense Reasoning | EMNLP<br>2019 | CSQA | [paper](https://arxiv.org/abs/1909.02151) <br> [code](https://github.com/INK-USC/KagNet) <br> [note](https://zhuanlan.zhihu.com/p/81917730) |
| What’s Missing: A Knowledge Gap Guided Approach for Multi-hop Question Answering | EMNLP<br>2019 | OpenBookQA | [paper](https://arxiv.org/abs/1909.09253) <br> [note](https://zhuanlan.zhihu.com/p/85852386) |
| BIG MOOD: Relating Transformers to Explicit Commonsense Knowledge | EMNLP<br>COIN<br>2019 | MCScripts v2 | [paper](http://arxiv.org/abs/1910.07713) |
| Align, Mask and Select: A Simple Method for Incorporating Commonsense Knowledge into Language Representation Models | 2019 | CSQA<br>WSC | [paper](https://arxiv.org/abs/1908.06725v1) |
| Abductive Reasoning as Self-Supervision for Common Sense Question Answering | 2019 | Swag<br>HellaSwag | [paper](http://arxiv.org/abs/1909.03099) |
| Exploring ways to incorporate additional knowledge to improve Natural Language Commonsense Question Answering| 2019 | ANLI/<br>SocialIQA | [paper](http://arxiv.org/abs/1909.08855)<br>[note](http://xingluxi.github.io/2019/09/26/paper-kn-mcqa-1909-08855/) |
| Graph-Based Reasoning over Heterogeneous External Knowledge for Commonsense Question Answering | AAAI<br>2020 | CSQA | [paper](http://arxiv.org/abs/1909.05311)<br>[note](http://xingluxi.github.io/2019/09/17/paper-csqa-1909-05311/) | 
| K-ADAPTER: Infusing Knowledge into Pre-Trained Models with Adapters | 2020 | CosmosQA | [paper](http://arxiv.org/abs/2002.01808)<br>[note](https://xingluxi.github.io/2020/02/10/paper-2019-k-adapter/) |
| Unsupervised Commonsense Question Answering with Self-Talk | 2020 | CSQA<br>SIQA | [paper](http://arxiv.org/abs/2004.05483)<br>[note](https://xingluxi.github.io/2020/04/26/paper-2020-2004-05483-self-talk/) |
| L2R2: Leveraging Ranking for Abductive Reasoning | SIGIR<br>2020 | ANLI | [paper](http://arxiv.org/abs/2005.11223) |
| Unsupervised Alignment-based Iterative Evidence Retrieval for Multi-hop Question Answering | ACL<br>2020 | MultiRC<br>QASC | [paper](https://www.aclweb.org/anthology/2020.acl-main.414) |
| Logic-Guided Data Augmentation and Regularization for Consistent Question Answering | ACL<br>2020 | WIQA<br>QuaREL | [paper](https://www.aclweb.org/anthology/2020.acl-main.499) |


## [Generation Tasks](#content)
Also known as **Free-form Answer Tasks**

| Title | Publish | Tasks | Links |
| :---- | :---: | :---- | :---:|
| Commonsense for Generative Multi-Hop Question Answering Tasks | EMNLP<br>2018 | NarrativeQA/<br>WikiHop | [paper](https://www.aclweb.org/anthology/D18-1454/) <br> [code](https://github.com/yicheng-w/CommonSenseMultiHopQA) <br> [note](http://xingluxi.github.io/2019/02/21/paper-emnlp2018-mhpgm/) |
| COMET: Commonsense Transformers for Automatic Knowledge Graph Construction | ACL<br>2019 | Atomic | [paper](https://arxiv.org/abs/1906.05317)<br>[code](https://github.com/atcbosselut/comet-commonsense)<br>[note](https://indexfziq.github.io/2019/07/03/COMET/) |
| Incorporating External Knowledge into Machine Reading for Generative Question Answering | EMNLP<br>2019 | MS MARCO | [paper](http://arxiv.org/abs/1909.02745)<br>[note](http://xingluxi.github.io/2019/10/13/paper-emnlp2019-keag/) |
| Modeling Event Background for If-Then Commonsense Reasoning Using Context-aware Variational Autoencoder | EMNLP<br>2019 | Event2Mind | [paper](http://arxiv.org/abs/1909.08824) |
| Dynamic Knowledge Graph Construction for Zero-shot Commonsense Question Answering | 2019 | SocialIQA<br>StoryCommonsense | [paper](http://arxiv.org/abs/1911.03876) |
| Injecting Numerical Reasoning Skills into Language Models | ACL<br>2020 | DROP | [paper](https://www.aclweb.org/anthology/2020.acl-main.89) |


## [Other Paper List About MRC](#content)

[thunlp/RCPapers](https://github.com/thunlp/RCPapers)

