
### What is Model Behavior?

Model behavior is a general concept, that explains certain characteristics of the model's prediction or the inference process that generate the prediction.

### Original Categorization

#### Input Manipulation

- [A Linguistic Evaluation of Rule-Based, Phrase-Based, and Neural MT Engines](https://ufal.mff.cuni.cz/pbml/108/art-burchardt-macketanz-dehdari-heigold-peter-williams.pdf), The Prague Bulletin of Mathematical Linguistics, 2017.
- [A Challenge Set Approach to Evaluating Machine Translation](https://aclanthology.org/D17-1263.pdf), EMNLP 2017.
- [Synthetic and Natural Noise Both Break Neural Machine Translation](https://openreview.net/forum?id=BJ8vJebC-), ICLR 2018.
- [Generating Natural Adversarial Examples](https://arxiv.org/abs/1710.11342), ICLR 2018.
- [Seq2Sick: Evaluating the Robustness of Sequence-to-Sequence Models with Adversarial Examples](https://ojs.aaai.org//index.php/AAAI/article/view/5767), 2020.
- [Towards Understanding Neural Machine Translation with Word Importance](https://aclanthology.org/D19-1088/), EMNLP 2020.
- [When a Good Translation is Wrong in Context: Context-Aware Machine Translation Improves on Deixis, Ellipsis, and Lexical Cohesion](https://aclanthology.org/P19-1116/), EMNLP 2019.
- [The Unreasonable Volatility of Neural Machine Translation Models](https://aclanthology.org/2020.ngt-1.10/), Workshop on Neural Generation and Translation 2020.


#### Controllable And Expected Behavior

- [Evaluating Grammaticality in Seq2seq Models with a Broad Coverage HPSG Grammar: A Case Study on Machine Translation](https://aclanthology.org/W18-5432/), 2018.
- [Controlling Text Complexity in Neural Machine Translation](https://aclanthology.org/D19-1166/), EMNLP 2019.
- [On Long-Tailed Phenomena in Neural Machine Translation](https://www.overleaf.com/project/6132bd0513f6ce27b87dac61), EMNLP 2020.
- [Detecting Non-literal Translations by Fine-tuning Cross-lingual Pre-trained Language Models](https://aclanthology.org/2020.coling-main.522/), COLING 2020.
- [Identifying and Controlling Important Neurons in Neural Machine Translation](https://openreview.net/forum?id=H1z-PsR5KX), ICLR 2019.


#### Impacts of Training Data

- [On the Impact of Various Types of Noise on Neural Machine Translation](https://aclanthology.org/W18-2709/), WMT 2018.
- [Analyzing Uncertainty in Neural Machine Translation](http://proceedings.mlr.press/v80/ott18a.html), ICML 2018.

#### Hallucination Issue

- [Hallucinations in Neural Machine Translation](https://openreview.net/pdf?id=SkxJ-309FQ), 2019.
  - Define a phenomenon called `hallucination`, when NMT model predicts highly pathological translations that are completely untethered from the source material.
  - Describe a method to generate hallucinations and show that common architectures are suscepticible to them.
  - They show data augmentation significantly reduces hallucination frequency.
- [Detecting Hallucinated Content in Conditional Neural Sequence Generation](https://arxiv.org/abs/2011.02593), ICLR 2020.
- [On Exposure Bias, Hallucination and Domain Shift in Neural Machine Translation](https://aclanthology.org/2020.acl-main.326/), ACL 2020.
- [The Curious Case of Hallucinations in Neural Machine Translation](https://arxiv.org/pdf/2104.06683.pdf), NAACL 2021.

### New Categorization

~~We divide the works that set up to understand model behavior as following:~~
~~- Direct analysis        : directly analyses the characteristics of the model predictions~~
~~- Counterfactual analysis: try to understand the behavior change of the model predictions with intervention of the input~~
~~- Controllable analysis  : try to repurpose the model prediction towards certain expected ones~~

- **Static Analysis**: directly analyze the properties of the model's predictions
- **Controlled Analysis**: charaterize the model's reaction to inputs constructed with certain property in concern
- **Dynamic Analysis**: do intervention or manipulation to the inputs or the model so as to reveal the weakness of the model

#### Static Analysis

- Linguistic property: fluency, coverage, word choice
  - [A Multifaceted Evaluation of Neural versus Phrase-Based Machine Translation for 9 Language Directions](https://aclanthology.org/E17-1100.pdf), EACL 2017.
  - [Evaluating Grammaticality in Seq2seq Models with a Broad Coverage HPSG Grammar: A Case Study on Machine Translation](https://aclanthology.org/W18-5432/), 2018.
  - [On Long-Tailed Phenomena in Neural Machine Translation](https://www.overleaf.com/project/6132bd0513f6ce27b87dac61), EMNLP 2020.
  - [Identifying Fluently Inadequate Output in Neural and Statistical Machine Translation](https://aclanthology.org/W19-6623.pdf), WMT 2019.

- Beyond linguistic property
  - [Detecting Non-literal Translations by Fine-tuning Cross-lingual Pre-trained Language Models](https://aclanthology.org/2020.coling-main.522/), COLING 2020.

- Calibration
  - [Calibration of Encoder Decoder Models for Neural Machine Translation](https://arxiv.org/abs/1903.00802), 2019.
  - [On the Inference Calibration of Neural Machine Translation](https://arxiv.org/pdf/2005.00963.pdf), EMNLP 2020.

#### Controlled Analysis

- Input with different linguistic phenomenon
  - [A Linguistic Evaluation of Rule-Based, Phrase-Based, and Neural MT Engines](https://ufal.mff.cuni.cz/pbml/108/art-burchardt-macketanz-dehdari-heigold-peter-williams.pdf), The Prague Bulletin of Mathematical Linguistics, 2017.
  - [A Challenge Set Approach to Evaluating Machine Translation](https://aclanthology.org/D17-1263.pdf), EMNLP 2017.

- Input with compositional structure
  - [On compositionality in neural machine translation](https://arxiv.org/abs/1911.01497), 2019.
  - [On Compositional Generalization of Neural Machine Translation](https://aclanthology.org/2021.acl-long.368/), ACL 2021.
  - [The paradox of the compositionality of natural language: a neural machine translation case study](https://arxiv.org/abs/2108.05885), 2021.

#### Dynamic Analysis





