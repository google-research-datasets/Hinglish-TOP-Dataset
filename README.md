# Hinglish-TOP Dataset

Hinglish-TOP consists of the largest (10K) human annotated code-switched semantic parsing dataset & 170K generated utterance using the CST5 augmentation technique introduced in our [paper](https://arxiv.org/pdf/2211.07514.pdf). Queries are derived from TOPv2, a multi-domain task oriented semantic parsing dataset. Experiments suggest that with CST5, up to 20x less labeled data can achieve the same semantic parsing performance.

# Dataset Structure and File Format
The dataset is itself divided into two subfolders, namely human annotated data and synthetically generated data. Under the human annotated data you can find the train, test and validation split whereas the synthetically generated data contains a single file with all the synthetically generated data.

The files themselves are in .tsv format. There are 5 coloumns which contain the English query, code-switched query, English parse, code-swaitched parse and the domain for each entry in that particular order.  
