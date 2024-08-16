# Asset Management NLP Project: Text Analytics

### Overview
This project employs Natural Language Processing (NLP) techniques to analyze financial news articles from the Dow Jones Newswires Machine Text Feed and Archive. The main objective is to extract significant topics using the Latent Dirichlet Allocation (LDA) approach.

### Data Source
The dataset consists of financial news articles provided by the Dow Jones Newswires. Each entry in the dataset under the column "Article" represents the cleaned text of a news article.

[Download Dataset (DJN_2017-01.pkl)](https://www.dropbox.com/s/uaqtmfq2h61mvpy/DJN_2017-01.pkl?dl=0)


### Methodology
We apply the Latent Dirichlet Allocation (LDA) model to all the articles in the dataset to identify 20 distinct topics. The model's configuration follows the methodology outlined in the paper by Bybee, Kelly, Manela, and Xiu (2022), titled "Business News and Business Cycles." Each topic is characterized by the top 10 keywords, which are selected based on their relevance to the topic as calculated in the referenced study.

### Objective
The goal of this project is to provide a clear view of the prevailing themes in business news that could influence asset management decisions. By understanding these topics, asset managers can better align their strategies with current market sentiments and trends.
