# Topic model for semantic search
Topic model on Legal text: Judgements

Topic modeling is a machine learning model that leverages unsupervised learning to analyze and automatically identify the clusters of similar words within the corpus. This approach is frequently used to discover hidden semantic patterns portrayed by a text corpus.
[Image](https://d2908q01vomqb2.cloudfront.net/f1f836cb4ea6efb2a0b1b99f41ad8b103eff4b59/2018/05/22/sagemaker-ntm-1.gif)


[David Blei](http://www.cs.columbia.edu/~blei/index.html), the author of Topic Modeling has also written a well-explained article titled [Probabilistic Topic Models](http://www.cs.columbia.edu/~blei/papers/Blei2012.pdf). Even in the age of ChatGPT, these topic models are quite practical for EDA or gaining insights from the data.

Common applications of topic model:
- Real-time analysis on unstructured textual data
- Automate the review of business documents (unstructured data) and segment them based on the underlying topic. e.g. determine whether the contents of a document are an invoice, complaint, or contract.
- Extract topics (understanding of data) from documents containing various formats.


In this repo, I am open-sourcing some of the work done for creating a semantic search engine, driven by topic models trained on judgement text. An example of visualization of topic models (using LDAvis) for a differnet corpus is shown here [Download for graphics](https://github.com/pkrouth/topic-model-poc/blob/6001e09c1237680f8563586fd69eed658244108a/EDA_10_topics.html)
