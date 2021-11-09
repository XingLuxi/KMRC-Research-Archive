# Papers on Robustness of Machine Reading Comprehension Models.

![](https://img.shields.io/badge/Status-building-brightgreen) ![](https://img.shields.io/badge/-papers-blue) ![](https://img.shields.io/badge/-analysis-critical)


A list of recent papers about **Knowledge-based Machine Reading Comprehension** (**KMRC**).

Contributed by [Luxi Xing](https://github.com/XingLuxi), [Yuqiang Xie](https://github.com/IndexFziQ) and [Wei Peng](https://github.com/a414351664).

Institute of Information Engineering, Chinese Academy of Sciences, Beijing, China. 

Update on **Nov. 7, 2021**.

<!--(We will continuously update this list.)-->

-------

What is the Robustness of MRC models:

1. Existing MRC models are based on word-level information and superficial clues. Thus, they are weak to adversarial QA pairs and are vulnerable when encounter spurious associations. 
2. Most PLM-based MRC models are over-confident of their outputs. The high confident prediction is delightful for True Positive prediction, but devil to False Positive prediction.

For estimating and improving the Robustness of MRC models, there are three(?) branches of research:

1. Dataset with **Unanswerable Questions**. For unanswerable question, there are several challenges, such as 1) Unanswerable question detection, 2) Plausible answer discrimination.
2. **Domain shift**.
3. **Calibration** of MRC models.

(If we miss some important works, welcome to create a pull request or new issues.)

-------

## Unanswerable Questions



1. Know what you don't know: Unanswerable questions for squad. ACL,2018. [[paper]()]

2. Zero-shot relation extraction via reading comprehension. ACL,2017.

3. I know there is no answer: Modeling answer validation for machine reading comprehension. NLPCC,2018.

4. U-net: Machine reading comprehension with unanswerable questions. 2018.

Outer Verification Component:

6. Read+ verify: Machine reading comprehension with unanswerable questions. AAAI,2019.

7. Retrospective Reader for Machine Reading Comprehension. AAAI,2020.

Inner Reasoning Module:

8. Relation Module for Non-Answerable Predictions on Reading Comprehension. CoNLL,2019.

9. NeurQuRI: Neural Question Requirement Inspector for Answerability Prediction in Machine Reading Comprehension. ICLR,2020.


## Domain Shift

1. Selective Question Answering under Domain Shift. ACL,2020.

1. Introspective Distillation for Robust Question Answering. NeruIPS,2021.


## MRC model Calibration


1. Robust Question Answering Through Sub-part Alignment. NAACL,2021.

2. Knowing More About Questions Can Help: Improving Calibration in Question Answering. Findings of ACL,2021.

3. How Can We Know When Language Models Know? On the Calibration of Language Models for Question Answering. TACL,2021.

1. Towards Confident Machine Reading Comprehension. 2021.

6. Surface Form Competition: Why the Highest Probability Answer Isn't Always Right. 2021.

7. Know When To Abstain: Calibrating Question Answering System under Domain Shift. 2021. 