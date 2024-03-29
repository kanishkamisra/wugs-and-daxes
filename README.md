# wugs-and-daxes
Collection of academic works in natural language processing, computational linguistics, and computational cognitive science that study models/agents on their abilities to perform tasks involving novel concepts/words.

Maintainers: [Kanishka Misra](https://github.com/kanishkamisra) and [Najoung Kim](https://github.com/najoungkim)

## Background

The integration and acquisition of words (and their representations) that a model/agent has never seen has been a challenge in natural language processing and cognitive science. In many cases, novel words have even offered a way to add experimental controls in model evaluation. Here, we attempt to gather academic publications and preprints that aim to diagnose, evaluate, or include novel words and their integration within their methods and analyses. We hope that this list helps folks like us who are interested in this topic!

This is a growing resource, and we hope to start organizing it in a meaningful way soon. Suggestions and contributions are welcome (through PRs)!

## Papers

***NOTE:*** *We currently have a bunch of different papers -- we will organize them properly (into various categories or chronologically, perhaps) once we reach sufficient mass.*

### Papers that exclusively focus on how novel words can be/are intregrated and used by computational models

- [Testing for Grammatical Category Abstraction in Neural Language Models](https://aclanthology.org/2021.scil-1.59) Najoung Kim and Paul Smolensky. 2021. *SCiL 2021*.
- [NYTWIT: A Dataset of Novel Words in the New York Times](https://aclanthology.org/2020.coling-main.572) Yuval Pinter, Cassandra L. Jacobs, Max Bittker. 2020. _COLING 2020_.
- [Investigating Novel Verb Learning in BERT: Selectional Preference Classes and Alternation-Based Syntactic Generalization](https://aclanthology.org/2020.blackboxnlp-1.25) Tristan Thrush, Ethan Wilcox, and Roger Levy. 2020. _BlackboxNLP 2020_.
- [Learning semantic representations for novel words: Leveraging both form and context](https://arxiv.org/abs/1811.03866) Timo Schick and Hinrich Schütze. 2019. _AAAI 2019_.
- [A La Carte Embedding: Cheap but Effective Induction of Semantic Feature Vectors](https://aclanthology.org/P18-1002) Mikhail Khodak, Nikunj Saunshi, Yingyu Liang, Tengyu Ma, Brandon Stewart, and Sanjeev Arora. 2018. _ACL 2018_.
- [One-shot and few-shot learning of word embeddings](https://arxiv.org/abs/1710.10280). Andrew Lampinen and James McClelland. 2018. _arXiv_.
- [High-risk learning: acquiring new word vectors from tiny data](https://aclanthology.org/D17-1030) Aurelie Herbelot and Marco Baroni. 2017. *EMNLP 2017*.
- [Multimodal word meaning induction from minimal exposure to natural text](https://onlinelibrary.wiley.com/doi/full/10.1111/cogs.12481) Angeliki Lazaridou, Marco Marelli, Marco Baroni. 2017. *Cognitive Science*.
- [A Computational Cognitive Model of Novel Word Generalization](https://aclanthology.org/D15-1207) Aida Nematzadeh, Erin Grant, Suzanne Stevenson. 2015. _EMNLP 2015_.
- [WinoDict: Probing language models for in-context word acquisition](http://arxiv.org/abs/2209.12153) Julian Martin Eisenschlos, Jeremy R. Cole, Fangyu Liu, William W. Cohen. 2022 _arXiv_.
- [COMPS: Conceptual Minimal Pair Sentences for testing Robust Property Knowledge and its Inheritance in Pre-trained Language Models](https://arxiv.org/abs/2210.01963) Kanishka Misra, Julia Taylor Rayz, Allyson Ettinger. 2023. _EACL 2023_.


### Papers that involve the use of novel words/words in specific scenarios

### Morphology
- [This is a BERT. Now there are several of them. Can they generalize to novel words?](https://aclanthology.org/2020.blackboxnlp-1.31) Coleman Haley. 2020. _BlackboxNLP 2020_.
- [Counting the Bugs in ChatGPT's Wugs: A Multilingual Investigation into the Morphological Capabilities of a Large Language Model](https://arxiv.org/abs/2310.15113). Leonie Weissweiler, Valentin Hofmann, Anjali Kantharuban, Anna Cai, Ritam Dutt, Amey Hengle, Anubha Kabra, Atharva Kulkarni, Abhishek Vijayakumar, Haofei Yu, Hinrich Schütze, Kemal Oflazer, David R. Mortensen. _EMNLP 2023_

### Compositional Generalization

- [COGS: A Compositional Generalization Challenge Based on Semantic Interpretation](https://aclanthology.org/2020.emnlp-main.731) Najoung Kim and Tal Linzen. 2020. *EMNLP 2020*.
- [Generalization without systematicity: On the compositional skills of sequence-to-sequence recurrent networks](http://proceedings.mlr.press/v80/lake18a/lake18a.pdf) Brenden Lake and Marco Baroni. 2018. _ICML 2018_.
- [Uncontrolled Lexical Exposure Leads to Overestimation of Compositional Generalization in Pretrained Models](https://najoungkim.github.io/assets/files/Kim_Linzen_Smolensky_uncontrolled_lexical_exposure.pdf) Najoung Kim, Tal Linzen, and Paul Smolensky. 2022.

### Syntax Probing/Acquisition
- [Do Syntactic Probes Probe Syntax? Experiments with Jabberwocky Probing](https://aclanthology.org/2021.naacl-main.11) Rowan Hall Maudslay and Ryan Cotterell. 2021. _NAACL 2021_.

### Parsing
- [Jabberwocky Parsing: Dependency Parsing with Lexical Noise](https://scholarworks.umass.edu/scil/vol2/iss1/13/) Jungo Kasai and Robert Frank. 2019. _SCiL 2019_.

### Mutual Exclusivity
- [Mutual exclusivity as a challenge for deep neural networks](https://proceedings.neurips.cc/paper/2020/file/a378383b89e6719e15cd1aa45478627c-Paper.pdf) Kanishk Gandhi and Brenden Lake. 2020. _NeurIPS 2020_.

### Category-based or Property Induction
- [A Property Induction Framework for Neural Language Models](https://arxiv.org/abs/2205.06910) Kanishka Misra, Julia Taylor Rayz, and Allyson Ettinger. 2022. *CogSci 2022*.
- [Do language models learn typicality judgments from text?](https://escholarship.org/uc/item/9n77r9mr#main) Kanishka Misra, Allyson Ettinger, and Julia Taylor Rayz. 2021. *CogSci 2021*.
- [Inductive reasoning about chimeric creatures](https://proceedings.neurips.cc/paper/2011/file/705f2172834666788607efbfca35afb3-Paper.pdf) Charles Kemp. 2011. _NeurIPS 2011_.


### Others (to be organized)
- [When More Data Hurts: A Troubling Quirk in Developing Broad-Coverage Natural Language Understanding Systems](https://arxiv.org/abs/2205.12228) Elias Stengel-Eskin, Emmanouil Antonios Platanios, Adam Pauls, Sam Thomson, Hao Fang, Benjamin Van Durme, Jason Eisner, and Yu Su. 2022. _arXiv_.
- [The driving forces of polarity-sensitivity: Experiments with multilingual pre-trained neural language models](https://lingbuzz.net/lingbuzz/006641) Lisa Bylinina and Alexey Tikhonov. 2022. _CogSci 2022_.
- [Old BERT, New Tricks: Artificial Language Learning for Pre-Trained Language Models](https://arxiv.org/abs/2109.06333). Lisa Bylinina, Alexey Tikhonov, and Ekaterina Garmash. 2021. _arXiv_.
- [Do Language Models Learn Position-Role Mappings?](https://arxiv.org/abs/2202.03611) Jackson Petty, Michael Wilson, and Robert Frank. 2022. _BUCLD 46_.
- [Deep daxes: Mutual exclusivity arises through both learning biases and pragmatic strategies in neural networks](https://arxiv.org/abs/2004.03902) Kristina Gulordava, Thomas Brochhagen, and Gemma Boleda. 2020. _CogSci 2020_.
- [Towards Understanding How Machines Can Learn Causal Overhypotheses](https://arxiv.org/abs/2206.08353) Eliza Kosoy, David M. Chan, Adrian Liu, Jasmine Collins, Bryanna Kaufmann, Sandy Han Huang, Jessica B. Hamrick, John Canny, Nan Rosemary Ke, Alison Gopnik. _CogSci 2023_ (forthcoming).
- [Investigating grammatical abstraction in language models using few-shot learning of novel noun gender](https://aclanthology.org/2024.findings-eacl.50/) Priyanka Sukumaran, Conor Houghton, Nina Kazanina. _Findings of EACL 2024_.
