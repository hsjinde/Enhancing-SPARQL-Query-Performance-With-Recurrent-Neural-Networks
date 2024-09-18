# ABSTRACT

DBpedia is one of the most resourceful linked databases today, and users need to use query syntax (e.g., SPARQL) to access information in DBpedia databases. However, not all users are familiar with SPARQL, so a natural language query system can be used to translate the user’s query into the corresponding syntax. Generating query syntax through such a system is both time-consuming and expensive. To improve the efficiency of query syntax generation from user questions, the multi-label template approach, specifically Light-QAwizard, is utilized.

Light-QAwizard transforms the problem into one or more single-label classifications using multi-label learning template approaches. By implementing Light-QAwizard, query costs can be reduced by 50%, but it introduces a new label during the transformation process, leading to sample imbalance, compromised accuracy, and limited scalability.

To overcome these limitations, this paper employs two multi-label learning methods: Binary Relevance (BR) and Classifier Chains (CC) for question transformation. By using Recurrent Neural Networks (RNNs) as a multi-label classifier for generating RDF (Resource Description Framework) triples, all labels are predicted to align with the query intentions. To better account for the relationship between RDF triples, BR is integrated into an ensemble learning approach, resulting in Ensemble BR.

Experimental results demonstrate that the proposed method outperforms previous research in terms of query accuracy. Favorable experimental results substantiate that the Ensemble BR or CC model demonstrates competitiveness by integrating label relationships into the trained model.

# Soource

- [IEEE Xplore](https://ieeexplore.ieee.org/document/10230082)
- [國立中興大學圖書館](https://nchu.primo.exlibrisgroup.com/discovery/fulldisplay?docid=alma990073689890107976&context=L&vid=886NCHU_INST:886NCHU_INST&lang=zh-tw&search_scope=MyInst_and_CI&adaptor=Local%20Search%20Engine&tab=Everything&query=any,contains,%E6%9E%97%E6%99%89%E5%BE%B7)
