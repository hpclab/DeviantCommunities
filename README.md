# On the behaviour of deviant communities in Online Social Networks

## Abstract

On-line social networks are complex ensembles of inter-linked communities that interact on different topics.
Some communities are characterized by what are usually referred to as deviant behaviors, conducts that are commonly considered inappropriate with respect to the society’s norms or moral standards. Eating disorders, drug use, and adult content consumption are just a few examples. We refer to such communities as deviant networks. It is commonly believed that such deviant networks are niche, isolated social groups, whose activity is well separated from the mainstream social-media life. According to this assumption, research studies have mostly considered them in isolation. In this work we focused on adult content consumption networks, which are common in most of the on-line social media networks and in the Web in general. We found that only a small group of densely connected nodes are responsible for most of the content production and that they have a clear internal structure. Differently from previous works, we also studied how such community interacts with the whole social network. We found that the produced content flows to the rest of the network mostly directly or through bridge-communities, reaching at least 450 times more users.We also show that a large fraction of the users can be inadvertently exposed to such content through indirect links. We discuss a demographic analysis of the producers and consumers networks. 
Finally, we show that it is easily possible to identify a few core users to radically uproot the diffusion process. We aim at setting the basis to study deviant communities in context.

## Authors

Luca Aiello
Mauro Coletto
Claudio Lucchese

## Data

We provide a list of adult keywords used in the paper to filter adult incoming queries which land to Tumblr blogs.

We preliminary created a keyword set as the union of the search keywords from professional adult websites along with the list of adult performers published by movie production companies. 
To extend the coverage also to blogs that are reached predominantly by Spanish queries (the second most used language in US), we also translated to Spanish the initial set of keywords.
From this initial set we manually extracted two dictionaries of respectively 5;152 (#file1) and 5;283 (#file2) search keywords (mono-grams, bi-grams, multi-grams), which were used to filter queries in the query log following two strategies: 
1) exact match, selecting those queries in the query log which match exactly one search keywords in the first dictionary, 
2) containment, selecting those queries subsuming any search keywords term in the second dictionary. For instance, we removed the word porn from the second dictionary (and not from the first) because queries like food porn should not to be detected as adult. 
The union of the queries detected by the two strategies hits on a set of blogs, whose most frequent incoming queries were manually inspected in order to detect further 351 search keywords (#file3).
The union of these terms with the exact match dictionary leads to a set of 5.5 K deviant queries which is used as the seed set to bootstrap the deviant graph extraction procedure as it is described in the paper. The final dictonary of adult keywords (6765 terms: monogram, bigrams, n-grams) obtained after the automatic expansion is provided here (#file4).

Format: One term for line (text file): n-grams composed by alphabetically ordered monograms separated by " " (space).

## Contact: 
Mauro Coletto, CNR Pisa - IMT Lucca
mauro.coletto@isti.cnr.it
mauro.coletto@imtlucca.it


## Acknowledgement

We encourage free and open use of the provided dictionaries. In return, we kindly require to cite us:

```
@inproceedings{tang2015line,
  title={On the behaviour of deviant communities in online social networks.},
  author={Coletto, Mauro and Aiello, Luca and Lucchese, Claudio and Silvestri, Fabrizio},
  booktitle={ICWSM},
  year={2016},
  organization={AAAI}
}
```
