# Legal_Seach_Engine-ElasticSearch_TFIDF_BM25
In this project, I have implemented a legal precedent search engine using elastic search checking similarity based on TF-IDF and BM25. The pre-processed verbose query is checked against a corpus of legal precedents and user is provided with most relevant judgements to the query.

## Dataset
The dataset consists of following: (FIRE-2017-IR-LeD - https://sites.google.com/view/fire2017irled)

Prior Cases: This is a set of 2000 prior cases, which is our corpus. Documents from this corpus are extracted and provide to the user as per his/her query.

Current cases: This is a set 200 current cases, which are queries for our search engine. We take one of the document from this query corpus and retrieve relevant results for the same.

q_rel file: This file has been used for evaluation purposes. It contains five relevant prior cases  for each current case

## Design and Architecture
![image](https://user-images.githubusercontent.com/102705658/230916881-deb6064a-a3a4-4bce-9ed1-d4f2bbeedc69.png)

## Approach
![image](https://user-images.githubusercontent.com/102705658/230917106-9898e5c7-22f3-4862-bcfe-d30ba74a00ce.png)
