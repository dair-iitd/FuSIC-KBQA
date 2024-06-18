# FuSIC-KBQA

This repo contains the datasets for the paper Few-shot Transfer Learning for Knowledge Base Question Answering: Fusing Supervised Models with In-Context Learning

The paper can be accessed at [https://arxiv.org/pdf/2311.08894](https://arxiv.org/pdf/2311.08894v3)


The following datasets are included: 
1. In-domain (results in table 4 of the paper)
   - in_domain_5pc: 5% subset of GrailQA train and dev split, along with 500 randomly sampled questions from the GrailQA dev split as the test split.
   - in_domain_10pc: 10% subset of GrailQA train and dev split, along with 500 randomly sampled questions from the GrailQA dev split as the test split.
   - in_domain_100pc: 500 randomly sampled questions from the GrailQA dev split as the test split.
**The 500 randomly sampled questions used as the test split are same for all 3 in-domain datasets.**
**The dev sets used in each in-domain dataset is disjoint with the test set.**
2. Few-Shot-Transfer (results in table 2 of the paper)
   - GrailQA_GraphQA:  100 randomly sampled questions from the train split of the GraphQA dataset, as the target few shots, along with 500 randomly sampled questions from the test split of the GraphQA dataset, as the test split.
   - GrailQA_WebQSP: 100 randomly sampled questions from the train split of the WebQSP dataset, as the target few shots, along with 500 randomly sampled questions from the test split of the WebQSP dataset, as the test split.
   - WebQSP_GrailQATech: 100 randomly sampled questions from the train split of the GrailQA dataset, from technical domains, as the target few shots, along with 500 randomly sampled questions from the test split of the GrailQA dataset, from technical domains, as the test split.
   - WebQSP_GraphQAPop: 100 randomly sampled questions from the train split of the GraphQA dataset, from popular domains, as the target few shots, along with 500 randomly sampled questions from the test split of the GraphQA dataset, from popular domains, as the test split.

3. New KG (results in table 5 of the paper)
   - The file contains 70 questions based on Microsoft Academic KG, annotated with sparql queries. 
