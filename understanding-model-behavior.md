
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

~~We divide the works that set up to understand model behavior as following:
- Direct analysis        : directly analyses the characteristics of the model predictions
- Counterfactual analysis: try to understand the behavior change of the model predictions with intervention of the input
- Controllable analysis  : try to repurpose the model prediction towards certain expected ones
