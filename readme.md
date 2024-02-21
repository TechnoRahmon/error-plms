## open-domain question answering system

In this notebook, we'll configure the initial segment of our open-domain question answering system, focusing on setting up the database component using Elasticsearch. We'll utilize pypdf2 to import the "Error Analysis of Pretrained Language Models (PLMs) in English‑to‑Arabic Machine Translation" PDF file. Then, we'll employ a BM25 retriever with the `deepset/bert-base-cased-squad2` PLM model to generate queries related to the content of the PDF.

### Steps 
**Elasticsearch Setup**

For this project, we will be building an open-domain question answering system. There are three major components to such a system:

- Database

- Retriever

- Reader

In this notebook we will setup the first part, the database - where we will be using Elasticsearch.

**Haystack pipeline**
here will build the haystack pipeline that will employ a BM25 retriever with the `deepset/bert-base-cased-squad2` PLM model to generate queries related to the content of the PDF.

check the article : [Building an Elasticsearch-Powered Question Answering System: Setup and Pipeline Construction](https://technor.dev/posts/Open-Domain-Question-Answering-System)