# Rhetoric Changes in Chinese Economic Reform: Computational Content Analysis on People's Daily 

### Abstract

The mechanisms behind the huge success of the Chinese economy after the 1990s are of substantial interest in social sciences, yet rarely studied using NLP. The paper intends to use computational content analysis to figure out how the Chinese economic reform in the last century initiated, and particularly, how the transition from planned to market economy took place and what characteristics the Chinese socialist market economy possesses. We find that the transition period lasts about 15 years with a smooth process and distinctive changes. We also extract three typical features in the Chinese market economy, namely the government's selective control on industries and firms, development as the major theme of the Chinese market economy, and the two-layer structure of people in decision making. The validity and robustness of our methods are further scrutinized in the conclusions.

### Authors

- [Linghui Wu](https://github.com/linghui-wu)
- [Tim, Qian Zhang](https://github.com/timqzhang)
- [Minghao Yang](https://github.com/WMhYang)

### Acknowledgement

We want to express our sincere gratitude to Professor James Evans who provides us with continuous support and helpful comments. We also thank our two teaching assistants, Bhargav Srinivasa Desikan and Hyunku Kwon, for continuous technical support. We want to further thank Shilin Jia, PhD student of sociology at University of Chicago, who gives us useful suggestions on processing Chinese text.

### Repository Structure

- `/codes` folder contains eight jupyter notebooks:

  - Corpus construction

  - Corpus sampling

  - Exploratory Data Analysis

  - Network Analysis

  - Topic Modeling

  - Word2Vec Notebooks

    - Projection
    - Aligned Dynamic Word2Vec

    - Time Path

- `/data` folder includes People's Daily corpus for the project

  - The People's Daily corpus from 1946 to 2003 is obtained from ["rmrb" repository](https://github.com/fangj/rmrb)
  - `output_datetitle_filtered.txt`  contains the data and title of selected news pieces extracted by Word2Vec and Doc2Vec
  - `/filtered_corpus_by_year` contains filtered news articles from 1965 to 2002
  - `/full_corpus_by_year` contains full news articles from 1965 to 2002

- `/models` folder stores trained LDA  and Word2Vec models

- `/picture` folder holds the visualizations generated from content analysis.

  - EDA
  - Network Analysis
  - Word2Vec
    - Projection
    - Dynamic Word2Vec
  - Topic Modeling
    - [Dynamic Intertopic Distance Map](https://htmlpreview.github.io/?https://github.com/WMhYang/EconContent/blob/master/pictures/topic_modeling/rmrb_lda.html)

### Notes for Computational Content Analysis Course

Techniques used in the projects come from:

- *week1* - count word frequency, and plot lexical dispersion and word cloud
- *week4* - perform network analysis to calculate centrality and explore key figures via Networkx. 
- *week5* - implement LDA to capture topic dynamics in People's Daily
- *week6* - apply Word2Vec and Doc2Vec for preliminary data sampling, and use Word2Vec to project words of interet to *planned* vs. *market* dimension, and to investigate the dynamic linguistic changes

### References

- Blei, David M, Andrew Y Ng, and Michael I Jordan, “Latent dirichlet allocation,”Journalof machine Learning research, 2003,3(Jan), 993–1022.

- Griffiths, Thomas L, Mark Steyvers, and Joshua B Tenenbaum, “Topics in semanticrepresentation.,”Psychological review, 2007,114(2), 211.

- Hamilton, William L., Jure Leskovec, and Dan Jurafsky, “Diachronic Word EmbeddingsReveal Statistical Laws of Semantic Change,” in “Proc. Assoc. Comput. Ling. (ACL)” 2016.

- Lu, Yongxiang,Science Progress in China, Elsevier Science, 2006.
- Maskin, Eric, Yingyi Qian, and Chenggang Xu, “Incentives, information, and organizationalform,”The review of economic studies, 2000,67(2), 359–378

- Mikolov, Tomas, Kai Chen, Greg Corrado, and Jeffrey Dean, “Efficient estimation of wordrepresentations in vector space,”arXiv preprint arXiv:1301.3781, 2013.

- Montinola, Gabriella, Yingyi Qian, and Barry R Weingast, “Federalism, Chinese style:the political basis for economic success in China,”World politics, 1995,48(1), 50–81.

- Zhang, Junlong and Yu Luo, “Degree Centrality, Betweenness Centrality, and Closeness Cen-trality in Social Network,” 2017,132(Msam), 300–303