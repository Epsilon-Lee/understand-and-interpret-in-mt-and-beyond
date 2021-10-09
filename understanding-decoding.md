
### Old paper lists

~~- [Beyond Error Propagation in Neural Machine Translation: Characteristics of Language Also Matter](https://aclanthology.org/D18-1396/), `decoding direction modeling` `emnlp2018`~~
- [Six Challenges for Neural Machine Translation](https://aclanthology.org/W17-3204.pdf), `large beam size issue`
- [Correcting Length Bias in Neural Machine Translation](https://aclanthology.org/W18-6322.pdf), `length bias`
- [Empirical Analysis of Beam Search Performance Degradation in Neural Sequence Models](http://proceedings.mlr.press/v97/cohen19a.html), `search discrepancies`
- [On NMT Search Errors and Model Errors: Cat Got Your Tongue?](https://aclanthology.org/D19-1331/), `search error vs model error`
- [Is MAP Decoding All You Need? The Inadequacy of the Mode in Neural Machine Translation](https://aclanthology.org/2020.coling-main.398/), `mode analysis`
- [If beam search is the answer, what was the question?](https://aclanthology.org/2020.emnlp-main.170/), `beyond beam search`
  - xxx
- [Understanding the Properties of Minimum Bayes Risk Decoding in Neural Machine Translation](https://arxiv.org/abs/2105.08504), `acl2021`


### What are those essential questions in or beyond NMT decoding?

~~- What are the impacts of error propagation during decoding?~~
- When to stop decoding?
  - [When to Finish? Optimal Beam Search for Neural Text Generation (modulo beam size)](http://web.engr.oregonstate.edu/~huanlian/papers/optimal_beam_search.pdf), 
  - [Breaking the Beam Search Curse: A Study of (Re-)Scoring Methods and Stopping Criteria for Neural Machine Translation](https://arxiv.org/pdf/1808.09582.pdf?source=post_page---------------------------), `beam search curse`.
  - [The EOS Decision and Length Extrapolation](https://arxiv.org/pdf/2010.07174.pdf).
  - [Consistency of a Recurrent Language Model With Respect to Incomplete Decoding](https://arxiv.org/pdf/2002.02492.pdf).
    - "receiving infinite-length sequences from a recurrent languange model when using common decoding algorithms"
    - define the inconsistency of a decoding algorithm, meaning that the algo can yeild an infinite-length sequence that has zero probability under the model
    - they show that commonly used decoding algorithms are inconsistent, e.g. greedy search, beam search, top-k sampling, and nucleus sampling
- What is the relationship between length bias and large-beam search?
  - [Six Challenges for Neural Machine Translation](https://aclanthology.org/W17-3204.pdf), `large beam size issue`
  - [Correcting Length Bias in Neural Machine Translation](https://aclanthology.org/W18-6322.pdf), `length bias`
  - [On NMT Search Errors and Model Errors: Cat Got Your Tongue?](https://aclanthology.org/D19-1331/), `search error vs model error`
  - [Empirical Analysis of Beam Search Performance Degradation in Neural Sequence Models](http://proceedings.mlr.press/v97/cohen19a.html), `search discrepancies`
  - [Why Neural Machine Translation Prefers Empty Outputs](https://arxiv.org/pdf/2012.13454.pdf), 2021.
    - "investigate why NMT systems assign high probability to empty translatations"
      - label smoothing makes correct translation less confident
      - same, high-frequency EoS word type to end all target sentence create an implicit smoothing that upscore zero-length translations  
- What are the characteristics of the model distribution during decoding?
  - [Is MAP Decoding All You Need? The Inadequacy of the Mode in Neural Machine Translation](https://aclanthology.org/2020.coling-main.398/), `mode analysis`
  - [If beam search is the answer, what was the question?](https://aclanthology.org/2020.emnlp-main.170/), `beyond beam search`
  - [Mode recovery in neural autoregressive sequence modeling](https://arxiv.org/pdf/2106.05459.pdf)
  - [Understanding the Properties of Minimum Bayes Risk Decoding in Neural Machine Translation](https://arxiv.org/abs/2105.08504), `acl2021`
  - [What Do You Get When You Cross Beam Search with Nucleus Sampling?](https://arxiv.org/pdf/2107.09729.pdf), `2021`.
- How to measure label bias?
  - [Investigating Label Bias in Beam Search for Open-ended Text Generation](https://arxiv.org/pdf/2005.11009.pdf).
