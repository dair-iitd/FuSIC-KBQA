# FuSIC-KBQA

This repo contains the datasets for the paper Few-shot Transfer Learning for Knowledge Base Question Answering: Fusing Supervised Models with In-Context Learning

The paper can be accessed at https://arxiv.org/pdf/2311.08894


The following datasets are included: 
1. In-domain (results in table 4 of the paper)
   - in_domain_5pc: 5% subset of GrailQA train and dev split, along with 500 randomly sampled questions from the GrailQA dev split as the test split.
   - in_domain_10pc: 10% subset of GrailQA train and dev split, along with 500 randomly sampled questions from the GrailQA dev split as the test split.
   - in_domain_100pc: 500 randomly sampled questions from the GrailQA dev split as the test split.
3. Few-Shot-Transfer (results in table 2 of the paper)
   - GrailQA_GraphQA:  100 randomly sampled questions from the train split of the GraphQA dataset, as the target few shots, along with 500 randomly sampled questions from the test split of the GraphQA dataset, as the test split.
   - GrailQA_WebQSP: 100 randomly sampled questions from the train split of the WebQSP dataset, as the target few shots, along with 500 randomly sampled questions from the test split of the WebQSP dataset, as the test split.
   - WebQSP_GrailQATech: 100 randomly sampled questions from the dev split of the GrailQA dataset, from technical domains, as the target few shots, along with 500 randomly sampled questions from the dev splitof the GrailQA dataset, from technical domains, as the test split.
   - WebQSP_GraphQAPop: 100 randomly sampled questions from the train split of the GraphQA dataset, from popular domains, as the target few shots, along with 500 randomly sampled questions from the test split of the GraphQA dataset, from popular domains, as the test split.
