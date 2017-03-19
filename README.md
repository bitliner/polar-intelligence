# 📖 polar-intelligence

My reading of academic papers and research notes.

Main topics: **sentiment analysis** and **automatic intelligence**.

## Sentiment Analysis

### Surveys
- **2016** - http://people.few.eur.nl/frasincar/papers/TKDE2016/tkde2016.pdf

`2017`

#### 🔖 Emergence of Grounded Compositional Language in Multi-Agent Populations
- **Topic**: 
  - language understanding via agents that learn words in combination with how they affect the world, rather than spotting patterns in a huge corpus of text. Supporting [Gary Marcus's](https://www.technologyreview.com/s/601551/algorithms-that-learn-with-less-data-could-expand-ais-power/) ideas. 
- **Authors**: Igor Mordatch (OpenAI), Pieter Abbeel (OpenAI)
- **Link**: [Paper](https://arxiv.org/abs/1703.04908) - [Blog Article](https://www.openai.com/blog/learning-to-communicate/)


#### 🔖 A Roadmap for Natural Language Processing Research in Information 
- **Topic**: 
  - Analysis of NLP research in 2004/2015, in order to identify state of NLP research, trends and define a roadmap
- **Link**: https://scholarspace.manoa.hawaii.edu/bitstream/10125/41285/1/paper0136.pdf

`Feb 2016`

#### Exploiting New Sentiment-Based Meta-level Features for Effective Sentiment Analysis

- **Topic**: 
  - Sentiment-based meta-level features for sentiment analysis on short text. 
  - Meta-level means: e.g. derived from bag-of-words representation. 
  - Example: sentiment distribution of the k-nearest neighbor of a document; document polarity of neighbors given by unsupervised lexical-based methods
- **Performance**: 
  - Tested on 19 datasets. 
  - **Superior by 16% to bag-of-word representation; largely superior to the best lexicon-based method.**
- **Benefits**: 
  - Transform original feature space into a smaller and more informed one 
- **Link**: http://homepages.dcc.ufmg.br/~fabricio/download/wsdm377-canutoA1.pdf

`Oct 2015`

#### Sentiment Embeddings with Applications to Sentiment Analysis
- **Topic**: 
  - Sentiment Embeddings - Encode text not only with context, but also with sentiment - 
- **Performance**: 
  - Outperforms on multiple datasets the context-based embeddings
- **Benefits**:
  - Inspire same encoding in other specific tasks
  - Apply encoding to improve sentiment
- **Link**: http://ieeexplore.ieee.org/abstract/document/7296633/

`Oct 2013`

#### 👍 Rule-based Information Extraction is Dead! Long Live Rule-based Information Extraction Systems!
- **Topics**:
  - Gap on IE techniques between market and research community, and a roadmap to fill the gap. Gap caused by different perception of usefuless of rule-based systems by the research community 
- **Link**: https://aclweb.org/anthology/D/D13/D13-1079.pdf or [Link](https://github.com/bitliner/polar-intelligence/blob/master/D13-1079.pdf)



# TODO
- [ ] Find papers from intersection of language acquisition, semi-supervised learning, and sentiment analysis
