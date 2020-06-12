# Rhetoric Changes in Chinese Economic Reform: Computational Content Analysis on People's Daily 

### Abstract

The repository contains group project for Computational Content Analysis course in Spring 2020. (TBA)

### Authors

- [Linghui Wu](https://github.com/linghui-wu)
- [Tim, Qian Zhang](https://github.com/timqzhang)
- [Minghao Yang](https://github.com/WMhYang)

- Instructor: Professor James Evans

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
- *week6* - apply Word2Vec and Doc2Vec for preliminary data sampling, and use Word2Vec for futher project (TBA)

### References

- Blei, David M, Andrew Y Ng, and Michael I Jordan, “Latent dirichlet allocation,”Journalof machine Learning research, 2003,3(Jan), 993–1022.

- Griffiths, Thomas L, Mark Steyvers, and Joshua B Tenenbaum, “Topics in semanticrepresentation.,”Psychological review, 2007,114(2), 211.

- Hamilton, William L., Jure Leskovec, and Dan Jurafsky, “Diachronic Word EmbeddingsReveal Statistical Laws of Semantic Change,” in “Proc. Assoc. Comput. Ling. (ACL)” 2016.

- Lu, Yongxiang,Science Progress in China, Elsevier Science, 2006.
- Maskin, Eric, Yingyi Qian, and Chenggang Xu, “Incentives, information, and organizationalform,”The review of economic studies, 2000,67(2), 359–378

- Mikolov, Tomas, Kai Chen, Greg Corrado, and Jeffrey Dean, “Efficient estimation of wordrepresentations in vector space,”arXiv preprint arXiv:1301.3781, 2013.

- Montinola, Gabriella, Yingyi Qian, and Barry R Weingast, “Federalism, Chinese style:the political basis for economic success in China,”World politics, 1995,48(1), 50–81.

- Zhang, Junlong and Yu Luo, “Degree Centrality, Betweenness Centrality, and Closeness Cen-trality in Social Network,” 2017,132(Msam), 300–303