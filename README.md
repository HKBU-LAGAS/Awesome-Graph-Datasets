<h1 align="center">🌟 Awesome Graph Datasets 🌟</h1>
<div align="center">

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
[![License: MIT](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE)

📌 We are actively collecting openly available graph datasets of diverse types for research purposes. This repository will be updated regularly.

</div>

## Contents

- [Contents](#contents)
- [📑 Dataset List](#-dataset-list)
  - [Plain Graphs](#plain-graphs)
  - [Temporal Graphs](#temporal-graphs)
  - [Signed Graphs](#signed-graphs)
  - [Attributed Graphs](#attributed-graphs)
  - [Bipartite Graphs](#bipartite-graphs)
  - [Bipartite Graphs](#bipartite-graphs)
  - [Text-Attributed Graphs](#text-attributed-graphs)
  - [Multimodal Graphs](#multimodal-graphs)
  - [Graph-level Datasets](#graph-level-datasets)
- [Dataset Repositories](#dataset-repositories)

## 📑 Dataset List

### Plain Graphs

| Name    | #nodes    | #edges    | #labels | Type        | URL       | 
|-------  |---------  |---------  |---------|-----------  |---------  |
| PPI |  3,890  |   76,584 | 50  | undirected  | [[raw]](https://github.com/xptree/LightNE) [[raw]](http://snap.stanford.edu/node2vec/) [[preprocessed]]() | 
| Blogcatalog3 |  10,312  |  333,983   | 39  | undirected  | [[raw]](https://github.com/xptree/LightNE) [[raw]](http://leitang.net/code/social-dimension/data/blogcatalog.mat) [[preprocessed]]() | 
| Flickr |  80,513 |  5,899,882  |   195    | undirected  | [[raw]](https://github.com/xptree/LightNE) [[raw]](http://leitang.net/code/social-dimension/data/flickr.mat) [[preprocessed]]() | 
| Amazon |  334863 |  925872  |   100    | undirected  | [[raw]](https://snap.stanford.edu/data/com-Amazon.html) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) | 
| DBLP | 425957  |  1049866  |   100    | undirected  | [[raw]](https://snap.stanford.edu/data/com-DBLP.html) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) | 
| Youtube | 1,138,499   | 2,990,443   | 47      | undirected  | [[raw]](http://socialcomputing.asu.edu/datasets/YouTube2) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) | 
| TWeibo  | 2,320,895   | 50,655,143  | 100     | directed    | [[raw]](https://www.kaggle.com/c/kddcup2012-track1) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) |
| Orkut   | 3,072,441   | 117,185,084 | 100     | undirected  | [[raw]](http://snap.stanford.edu/data/com-Orkut.html) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) |
|LiveJournal  | 3997962 | 34681189 |  100   |  undirected  |  [[raw]](https://snap.stanford.edu/data/com-LiveJournal.html) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)         | 
|In-2004  | 1,382,908 | 16,539,643|    -    |   directed  |  [[raw]](http://law.di.unimi.it/webdata/in-2004/)  [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) | 
|DBLP     | 5,425,963 | 17,298,032|    -    |   undirected|  [[raw]](http://konect.uni-koblenz.de/networks/dblp-author)  [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)        | 
|Pokec    | 1,632,803 | 30,622,564|    -    |   directed  |  [[raw]](http://snap.stanford.edu/data/soc-Pokec.html)  [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)        | 
|LiveJournal  | 4,847,571 | 68,475,391 |  -    |  directed  |  [[raw]](http://snap.stanford.edu/data/soc-LiveJournal1.html) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)         | 
|IT-2004  | 41,291,594  | 1,135,718,909  |   -      |  directed  |  [[raw]](http://law.di.unimi.it/webdata/it-2004/) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)| 
|Twitter  | 41,652,230  | 1,468,365,182|    -    | directed    | [[raw]](http://law.di.unimi.it/webdata/twitter-2010/) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)|
|Friendster-small | 7,944,949  | 447,219,610 |  100  |  undirected  | [[raw]](https://snap.stanford.edu/data/com-Friendster.html) [[raw]](https://graphvite.io/docs/latest/api/dataset.html) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) |
|Friendster | 65,608,366  | 1,806,067,135 |   100  |  undirected  | [[raw]](https://snap.stanford.edu/data/com-Friendster.html) [[raw]](https://graphvite.io/docs/latest/api/dataset.html) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) |
|OAG | 67,768,244  | 895,368,962 |   19  |  undirected  | [[raw]](https://github.com/xptree/LightNE) [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing) |
|UK-2007 | 105,896,555 | 3,738,733,648|    -    |   directed  |  [[raw]](http://law.di.unimi.it/webdata/uk-2007-05/)[[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)       | 
|UK-union | 133,633,040 | 5,475,109,924|    -    |   directed  |  [[raw]](http://law.di.unimi.it/webdata/uk-union-2006-06-2007-05/)  [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)        | 
|ClueWeb12| 978,408,098 | 42,574,107,469 | - | directed | [[raw]](http://law.di.unimi.it/webdata/clueweb12/) |
|ClueWeb09| 1,684,868,322| 7,939,635,651|    -    |  directed  |   [[raw]](http://www.lemurproject.org/clueweb09.php/)    [[preprocessed]](https://drive.google.com/drive/folders/14kUsAk46ZHD0l1amZBoWm4duUf2IwYwC?usp=sharing)     | 

Welcome to cite our paper if you publish results based on our preprocessed datasets.
```bib
@article{yang13homogeneous,
  title={Homogeneous Network Embedding for Massive Graphs via Reweighted Personalized PageRank},
  author={Yang, Renchi and Shi, Jieming and Xiao, Xiaokui and Yang, Yin and Bhowmick, Sourav S},
  journal={Proceedings of the VLDB Endowment},
  volume={13},
  number={5},
  pages={670--683},
  year={2020},
  publisher={VLDB Endowment}
}

@article{shi13realtime,
  title={Realtime Index-Free Single Source SimRank Processing on Web-Scale Graphs},
  author={Shi, Jieming and Jin, Tianyuan and Yang, Renchi and Xiao, Xiaokui and Yang, Yin},
  journal={Proceedings of the VLDB Endowment},
  volume={13},
  number={7},
  pages={966--980},
  year={2020},
  publisher={VLDB Endowment}
}
```

### Temporal Graphs

### Signed Graphs

| Name    | #nodes    | #positive-edges    | #negative-edges | #attributes | #labels  | bipartite  |   Source       | 
|-------  |---------  |---------  |---------|-----------|-----------|----------- |----------- |
|  Epinions  |      |       |       |       |        |        |   [link](https://snap.stanford.edu/data/soc-sign-epinions.html) [link](https://www.cs.uoi.gr/~apappas/projects/SocialNetworks/)   |
|  Wikipedia   |      |       |       |       |        |        |   [link](https://snap.stanford.edu/data/wiki-Elec.html)  [link](https://www.cs.uoi.gr/~apappas/projects/SocialNetworks/)  |
|  Slashdot   |      |       |       |       |        |        |   [link](https://snap.stanford.edu/data/soc-sign-Slashdot090221.html) [link](https://www.cs.uoi.gr/~apappas/projects/SocialNetworks/)   |
|  Bitcoin   |      |       |       |       |        |        |   [link](https://snap.stanford.edu/data/soc-sign-bitcoin-otc.html)    |
|   WikiSigned  |      |       |       |       |        |        |   [link](http://konect.cc/networks/wikisigned-k2/)    |
|  Reddit   |      |       |       |       |        |        |   [link](https://snap.stanford.edu/data/soc-RedditHyperlinks.html) [link](https://www.kaggle.com/datasets/josephleake/huge-collection-of-reddit-votes) [link](https://courses.cs.washington.edu/courses/cse547/19sp/data.html) [link](https://www.cs.uoi.gr/~apappas/projects/SocialNetworks/)   |
|  ADJNet   |      |       |       |       |        |        |   [link](https://arxiv.org/pdf/1702.06819.pdf)    |
|  SCOTUS   |      |       |       |       |        |        |   [link](https://arxiv.org/pdf/1702.06819.pdf)    |
|  Bonanza   |      |       |       |       |        |    Yes    |   [link](https://github.com/tylersnetwork/signed_bipartite_networks) [link](https://github.com/huangjunjie-cs/SBGNN)   |
|   U.S. Senate  |      |       |       |       |        |    Yes    |   [link](https://github.com/tylersnetwork/signed_bipartite_networks) [link](https://github.com/huangjunjie-cs/SBGNN)   |
|  U.S. House   |      |       |       |       |        |    Yes    |   [link](https://github.com/tylersnetwork/signed_bipartite_networks) [link](https://github.com/huangjunjie-cs/SBGNN)   |
|   Review  |     |       |       |       |        |    Yes    |   [link](https://github.com/Alex-Zeyu/SBGCL) [link](https://github.com/huangjunjie-cs/SBGNN)    |
|  MovieLens-1M   |      |       |       |       |        |    Yes    |   [link](https://github.com/Alex-Zeyu/SBGCL)    |
|   Amazon-Book  |      |       |       |       |        |    Yes    |   [link](https://github.com/Alex-Zeyu/SBGCL)    |
|  Amazon-CDs   |      |       |       |       |        |    Yes    |   [link](https://github.com/StupidThree/SIGformer)    |
|  Amazon-Music   |      |       |       |       |        |    Yes    |   [link](https://github.com/StupidThree/SIGformer)    |
|  KuaiRec   |      |       |       |       |        |    Yes    |   [link](https://github.com/StupidThree/SIGformer)    |
|  KuaiRand   |      |       |       |       |        |    Yes    |   [link](https://github.com/StupidThree/SIGformer)    |




### Attributed Graphs

| Name  | Type      | #nodes    | #edges | #attributes  | #labels | URL       | 
|-------  |---------  |---------  |---------|-----------  |---------  |---------  |
|Wiki |directed|2405|17981|4973| 19| [[raw]](https://github.com/thunlp/TADW/tree/master/wiki) [[preprocessed]](https://drive.google.com/file/d/1EPhlbziZTQv19OsTrKrAJwsElbVPEbiV/view?usp=sharing)|
|Cora | directed|2708|5429|1433| 7| [[raw]](https://linqs.soe.ucsc.edu/data) [[preprocessed]](https://drive.google.com/file/d/1FyVnpdsTT-lhkVPotUW8OVeuCi1vi3Ey/view?usp=sharing)|
|Citeseer| directed|3312|4660|3703| 6| [[raw]](https://linqs.soe.ucsc.edu/data) [[preprocessed]](https://drive.google.com/file/d/1d3uQIpHiemWJPgLgTafi70RFYye7hoCp/view?usp=sharing)|
|Pubmed| directed|19717|44338|500| 3| [[raw]](https://linqs.soe.ucsc.edu/data) [[preprocessed]](https://drive.google.com/file/d/1DOK3FfslyJoGXUSCSrK5lzdyLfIwOz6k/view?usp=sharing)|
|BlogCatalog| undirected|5196|343486| 8189| 6| [[raw]](https://github.com/mengzaiqiao/CAN/tree/master/data) [[preprocessed]](https://drive.google.com/file/d/178PqGqh67RUYMMP6-SoRHDoIBh8ku5FS/view?usp=sharing)|
|PPI| undirected|56944|818716|50| 121| [[raw]](http://snap.stanford.edu/graphsage/) [[preprocessed]](https://drive.google.com/file/d/1dvwRpPT4gGtOcNP_Q-G1TKl9NezYhtez/view?usp=sharing)|
|Flickr| undirected|7575|479476|12047| 9| [[raw]](https://github.com/mengzaiqiao/CAN/tree/master/data) [[preprocessed]](https://drive.google.com/file/d/1tZp3EB20fAC27SYWwa-x66_8uGsuU62X/view?usp=sharing)|
|Facebook| undirected|4039|88234|1283| 193| [[raw]](https://snap.stanford.edu/data/ego-Facebook.html) [[preprocessed]](https://drive.google.com/file/d/12aJWAGCM4IvdGI2fiydDNyWzViEOLZH8/view?usp=sharing)|
|ArXiv| undirected| 169343 | 1157799 | 128 | 40 | [[raw]](https://drive.google.com/drive/folders/1zycmmDES39zVlbVCYs88JTJ1Wm5FbfLz) [[preprocessed]](https://drive.google.com/drive/folders/14h9JrgR1TAVZVXhhl5rZQVcfmyQTR5kL)|
|Reddit| undirected|  232,965 |  11,606,919 | 602 | 41 | [[raw]](https://drive.google.com/drive/folders/1zycmmDES39zVlbVCYs88JTJ1Wm5FbfLz) [[preprocessed]](https://drive.google.com/drive/folders/14h9JrgR1TAVZVXhhl5rZQVcfmyQTR5kL)|
|Yelp| undirected|  716847 | 6,977,410 | 300 | 100 | [[raw]](https://drive.google.com/drive/folders/1zycmmDES39zVlbVCYs88JTJ1Wm5FbfLz) [[preprocessed]](https://drive.google.com/drive/folders/14h9JrgR1TAVZVXhhl5rZQVcfmyQTR5kL)|
|Twitter| directed|81306|1768149|216839| 4065| [[raw]](https://snap.stanford.edu/data/ego-Twitter.html) [[preprocessed]](https://drive.google.com/file/d/1fUYggzZlDrt9JsLsSdRUHiEzQRW1kSA4/view?usp=sharing)|
|Amazon2M| undirected| 2449029 | 61859140 | 100 | 47 | [[raw]](https://github.com/google-research/google-research/tree/master/cluster_gcn) [[raw]](https://ogb.stanford.edu/docs/nodeprop/#ogbn-products) [[preprocessed]](https://drive.google.com/drive/folders/14h9JrgR1TAVZVXhhl5rZQVcfmyQTR5kL)|
|Google+| directed|107614|13673453|15907| 468| [[raw]](https://snap.stanford.edu/data/ego-Gplus.html) [[preprocessed]](https://drive.google.com/drive/folders/14h9JrgR1TAVZVXhhl5rZQVcfmyQTR5kL)|
|TWeibo| directed| 2320895| 50655143| 1657| 8| [[raw]](https://www.kaggle.com/c/kddcup2012-track1) [[preprocessed]](https://drive.google.com/file/d/1-2xHDPFCsuBuFdQN_7GLleWa8R_t50qU/view?usp=sharing)|
|MAG| directed| 59249719| 978147253| 2000| 100| [[raw]](http://ma-graph.org/rdf-dumps/) [[preprocessed]](https://drive.google.com/file/d/1ggraUMrQgdUyA3DjSRzzqMv0jFkU65V5/view?usp=sharing)|
|MAG-SC| directed|10541560| 265219994 |2784240 | 8 | [[raw]](https://figshare.com/articles/dataset/mag_scholar/12696653) [[preprocessed]](https://drive.google.com/drive/folders/14h9JrgR1TAVZVXhhl5rZQVcfmyQTR5kL)|

Our datasets are also available in [Pytorch-Geometric](https://pytorch-geometric.readthedocs.io/en/latest/modules/datasets.html#torch_geometric.datasets.AttributedGraphDataset). Node attributes can be loaded as a sparse matrix using the following code
```python
from scipy import sparse
features = sparse.load_npz("attrs.npz")
```
Welcome to cite our paper if you publish results based on our preprocessed datasets.
```bib
@article{yang2020scaling,
  title={Scaling Attributed Network Embedding to Massive Graphs},
  author={Yang, Renchi and Shi, Jieming and Xiao, Xiaokui and Yang, Yin and Liu, Juncheng and Bhowmick, Sourav S},
  journal={Proceedings of the VLDB Endowment},
  volume={14},
  number={1},
  pages={37--49},
  year={2021},
  publisher={VLDB Endowment}
}
```

### Bipartite Graphs

| Name    |     \|U\|   |    \|V\|    |   \|E\|   | URL       | 
|-------  |---------  |---------  |---------|---------  |
|  Avito  |  27736    |  16589    | 67029   |[[raw]](https://www.kaggle.com/c/avito-context-ad-clicks/data)  [[preprocessed]](https://drive.google.com/drive/folders/11fm6L0lBDPLUKA9CToL0zqxkwhst0rEE)|
|  AOL    |   4811647 |  1632788  | 10741954|[[raw]](http://www.ccc.ipt.pt/~ricardo/experiments/AOL_DS.html)  [[preprocessed]](https://drive.google.com/drive/folders/11fm6L0lBDPLUKA9CToL0zqxkwhst0rEE)|
|  DBLP   |  6001     |  1524     |  29257  |[[raw]](https://github.com/clhchtcjj/BiNE/tree/master/data/dblp)  [[preprocessed]](https://drive.google.com/drive/folders/11fm6L0lBDPLUKA9CToL0zqxkwhst0rEE)|
|  Movielens-1M  |   6040        |   3706        |  1000210 |[[raw]](https://grouplens.org/datasets/movielens/)  [[preprocessed]](https://drive.google.com/drive/folders/11fm6L0lBDPLUKA9CToL0zqxkwhst0rEE)|
|  KDDCup2012  |  255170  | 1848114  | 2766394 |[[raw]](https://www.kaggle.com/c/kddcup2012-track2)  [[preprocessed]](https://drive.google.com/drive/folders/11fm6L0lBDPLUKA9CToL0zqxkwhst0rEE)|
|  Last.fm     | 359349  |  160168  | 17559531 |[[raw]](http://ocelma.net/MusicRecommendationDataset/lastfm-360K.html)  [[preprocessed]](https://drive.google.com/drive/folders/11fm6L0lBDPLUKA9CToL0zqxkwhst0rEE)|
|  Amazon-games | 826767  |  50210 | 1324754 |[[raw]](http://deepyeti.ucsd.edu/jianmo/amazon/)  [[preprocessed]](https://drive.google.com/drive/folders/11fm6L0lBDPLUKA9CToL0zqxkwhst0rEE)|
|  DBLP    | 6,001  | 1,308 | 29,256  | [[raw]](https://github.com/clhchtcjj/BiNE/tree/master/data/dblp) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
| Wikipedia     | 15,000  |  3,214 | 64,095  | [[raw]](https://github.com/clhchtcjj/BiNE/tree/master/data/wiki) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
|   Pinterest   | 55,187  | 9,916  | 1,500,809  | [[raw]](https://github.com/hexiangnan/neural_collaborative_filtering/tree/master/Data) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
|   Yelp   |  31,668 | 38,048  | 1,561,406  | [[raw]](https://github.com/kuandeng/LightGCN/tree/master/Data/yelp2018) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
|  MovieLens-10M    |  69,878 | 10,677  |  10,000,054 | [[raw]](https://grouplens.org/datasets/movielens/) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
|  Last.fm    | 359,349  | 160,168  | 17,559,530 | [[raw]](http://ocelma.net/MusicRecommendationDataset/lastfm-360K.html) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
|   MIND   | 876,956  | 97,509  | 18,149,915  | [[raw]](https://msnews.github.io/) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
|  Netflix    | 480,189  | 17,770  | 100,480,507  | [[raw]](https://academictorrents.com/details/9b13183dc4d60676b773c9e2cd6de5e5542cee9a) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
|   Orkut   | 2,783,196  | 8,730,857  | 327,037,487  | [[raw]](https://networkrepository.com/aff-orkut-user2groups.php) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |
|  MAG    | 10,541,560  | 2,784,240  |  1,095,315,106 | [[raw]](https://figshare.com/articles/dataset/mag_scholar/12696653) [[preprocessed]](https://drive.google.com/drive/folders/1-l3OuAoiR1rcbk10zVhNLgHVgY8M_hwu?usp=sharing) |

Welcome to cite our paper if you publish results based on our preprocessed datasets.
```bib
@inproceedings{yang2022efficient,
  title={Efficient and Effective Similarity Search over Bipartite Graphs},
  author={Yang, Renchi},
  booktitle={Proceedings of the ACM Web Conference 2022},
  pages={308--318},
  year={2022}
}

@inproceedings{yang2022scalable,
  title={Scalable and Effective Bipartite Network Embedding},
  author={Yang, Renchi and Shi, Jieming and Huang, Keke and Xiao, Xiaokui},
  booktitle={Proceedings of the 2022 International Conference on Management of Data},
  pages={1977--1991},
  year={2022}
}
```

### Text-Attributed Graphs
| Name | #nodes | #edges | #labels / relations | Domain | Text location / features | Task | Notes | Source |
|---|---:|---:|---|---|---|---|---|---|
| Cora | 2,708 | 21,112 | 7 | Co-citation | Node & Edge | Node Classification; Link Prediction | Suggested fill for root README row | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| PubMed | 19,717 | 44,338 | 3 | Co-citation | Node & Edge | Node Classification; Link Prediction | Suggested fill for root README row | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| ArXiv | 169,343 | 1,166,243 | 40 | Citation | Node & Edge | Node Classification | Suggested fill for root README row | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| WikiCS | 11,701 | 216,123 | 10 | Wikipedia page | Node & Edge | Node Classification | Suggested fill for root README row | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| Product-subset | 54,025 | 144,638 | 44 used / 47 original | Co-purchase | Node & Edge | Node Classification | Suggested fill for root README row | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| FB15K237 | 14,541 | 310,116 | 237 relations | Knowledge graph | Node & Edge | Link Prediction | Suggested fill for root README row | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| WN18RR | 40,943 | 93,003 | 11 relations | Knowledge graph | Node & Edge | Link Prediction | Suggested fill for root README row | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| MovieLens-1M | 9,923 | 2,000,418 | 5 ratings | Movie rating | Node & Edge | Link Regression / Classification | Suggested fill for root README row | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| Cornell | 195 | 304 | 5 | Web page | Raw text + PLM features | Node Classification | HeTGB; edge homophily 0.13 | [HeTGB](https://arxiv.org/abs/2503.04822) |
| Texas | 187 | 328 | 5 | Web page | Raw text + PLM features | Node Classification | HeTGB; edge homophily 0.12 | [HeTGB](https://arxiv.org/abs/2503.04822) |
| Wisconsin | 265 | 530 | 5 | Web page | Raw text + PLM features | Node Classification | HeTGB; edge homophily 0.20 | [HeTGB](https://arxiv.org/abs/2503.04822) |
| Actor | 4,416 | 12,172 | 5 | Social | Raw text + PLM features | Node Classification | HeTGB; edge homophily 0.56 | [HeTGB](https://arxiv.org/abs/2503.04822) |
| Amazon | 24,492 | 93,050 | 5 | E-commerce | Raw text + PLM features | Node Classification | HeTGB; edge homophily 0.38 | [HeTGB](https://arxiv.org/abs/2503.04822) |
| ogb-products | 2,449,029 | 61,859,140 | - | E-commerce | Node | Node Classification | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| ogb-papers110M | 111,059,956 | 1,615,685,872 | - | Academic | Node | Node Classification | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| ogb-citation2 | 2,927,963 | 30,561,187 | - | Academic | Node | Link Prediction | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| DBLP | 5,259,858 | 36,630,661 | - | Academic | Node | Node Classification; Link Prediction | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| MAG | ~10M | ~50M | - | Academic | Node | Node Classification; Link Prediction; Recommendation; Regression | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| Goodreads-books | ~2M | ~20M | - | Books | Node | Node Classification; Link Prediction | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| Amazon-items | ~15.5M | ~100M | - | E-commerce | Node | Node Classification; Link Prediction; Recommendation | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| Wikidata5M | ~4M | ~20M | - | Wikipedia | Node | Link Prediction | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| Twitter | 176,279 | 2,373,956 | - | Social | Node | Node Classification; Link Prediction | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |

More in [paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10697304#page=7.78), [paper](https://arxiv.org/pdf/2405.16800), [paper](https://arxiv.org/abs/2503.04822)

### Textual-Edge Graphs

| Name | #nodes | #edges | #labels / relations | Domain | Text location | Task | Notes | Source |
|---|---:|---:|---|---|---|---|---|---|
| Goodreads-History | 540,807 | 2,368,539 | 11 | Book Recommendation | Node & Edge | Node Classification; Link Prediction | TEG-DB; large scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Goodreads-Crime | 422,653 | 2,068,223 | 11 | Book Recommendation | Node & Edge | Node Classification; Link Prediction | TEG-DB; large scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Goodreads-Children | 216,624 | 858,586 | 11 | Book Recommendation | Node & Edge | Node Classification; Link Prediction | TEG-DB; large scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Goodreads-Comics | 148,669 | 631,649 | 11 | Book Recommendation | Node & Edge | Node Classification; Link Prediction | TEG-DB; medium scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Amazon-Movie | 137,411 | 2,724,028 | 399 | E-commerce | Node & Edge | Node Classification; Link Prediction | TEG-DB; medium scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Amazon-Apps | 31,949 | 62,036 | 62 | E-commerce | Node & Edge | Node Classification; Link Prediction | TEG-DB; small scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Reddit | 478,022 | 676,684 | 3 | Social Networks | Node & Edge | Node Classification; Link Prediction | TEG-DB; large scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Twitter | 18,761 | 23,764 | 505 | Social Networks | Node & Edge | Node Classification; Link Prediction | TEG-DB; small scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Citation | 169,343 | 1,166,243 | 40 | Academic | Node & Edge | Node Classification; Link Prediction | TEG-DB; large scale | [TEG-DB](https://arxiv.org/pdf/2406.10310) |
| Amazon-Movie | 173,986 | 1,697,533 | - | E-commerce | Edge-focused textual network | Edge Classification; Link Prediction; Node Classification | Edgeformers preprocessing; differs from TEG-DB | [Edgeformers](https://arxiv.org/pdf/2302.11050) |
| Amazon-Apps | 100,468 | 752,937 | - | E-commerce | Edge-focused textual network | Edge Classification; Link Prediction; Node Classification | Edgeformers preprocessing; differs from TEG-DB | [Edgeformers](https://arxiv.org/pdf/2302.11050) |
| Goodreads-Crime | 385,203 | 1,849,236 | - | Book Recommendation | Edge-focused textual network | Edge Classification; Link Prediction | Edgeformers preprocessing; also used by Link2Doc | [Edgeformers](https://arxiv.org/pdf/2302.11050), [Link2Doc](https://arxiv.org/abs/2405.16606) |
| Goodreads-Children | 192,036 | 734,640 | - | Book Recommendation | Edge-focused textual network | Edge Classification; Link Prediction | Edgeformers preprocessing; also used by Link2Doc | [Edgeformers](https://arxiv.org/pdf/2302.11050), [Link2Doc](https://arxiv.org/abs/2405.16606) |
| StackOverflow | 129,322 | 281,657 | - | Social | Edge-focused textual network | Edge Classification; Link Prediction | Edgeformers row; same count also appears in LLMs-on-Graphs survey | [Edgeformers](https://arxiv.org/pdf/2302.11050), [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| Goodreads-reviews | ~3M | ~100M | - | Books | Edge | Edge Classification; Link Prediction | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |
| Amazon-reviews | ~15.5M | ~200M | - | E-commerce | Edge | Edge Classification; Link Prediction | Survey-collected row | [LLMs on Graphs Survey](https://arxiv.org/abs/2312.02783) |

### Bipartite Textual-Edge Graphs

| Name | #source nodes | #destination nodes | #interactions / edges | #classes | Domain | Text location | Task | Notes | Source |
|---|---:|---:|---:|---:|---|---|---|---|---|
| Goodreads-Children | 10,521 users | 1,479 items | 40,762 | 6 | Book reviews | Interactions / edges | Textual Interaction Classification | TIN benchmark | [SAFT](https://arxiv.org/abs/2504.04861) |
| Amazon-Apps | 4,390 users | 5,610 items | 51,073 | 5 | E-commerce reviews | Interactions / edges | Textual Interaction Classification | TIN benchmark | [SAFT](https://arxiv.org/abs/2504.04861) |
| Amazon-Movie | 4,431 users | 1,819 items | 61,216 | 5 | E-commerce reviews | Interactions / edges | Textual Interaction Classification | TIN benchmark | [SAFT](https://arxiv.org/abs/2504.04861) |
| Goodreads-Crime | 7,009 users | 1,241 items | 62,774 | 6 | Book reviews | Interactions / edges | Textual Interaction Classification | TIN benchmark | [SAFT](https://arxiv.org/abs/2504.04861) |
| Goodreads-Poetry | 47,400 users | 36,412 items | 154,555 | 6 | Book reviews | Interactions / edges | Textual Interaction Classification | TIN benchmark | [SAFT](https://arxiv.org/abs/2504.04861) |
| Google-Vermont | 12,655 users | 5,040 items | 178,168 | 5 | Local business reviews | Interactions / edges | Textual Interaction Classification | TIN benchmark | [SAFT](https://arxiv.org/abs/2504.04861) |
| Google-Hawaii | 39,215 users | 10,170 items | 710,948 | 5 | Local business reviews | Interactions / edges | Textual Interaction Classification | TIN benchmark | [SAFT](https://arxiv.org/abs/2504.04861) |
| Amazon-Products | 101,498 users | 27,965 items | 800,144 | 5 | E-commerce reviews | Interactions / edges | Textual Interaction Classification | TIN benchmark | [SAFT](https://arxiv.org/abs/2504.04861) |


### Heterogeneous Text-Attributed Graphs

| Name | #nodes | #edges | #classes | Domain | Node types / text-rich types | Edge types | Task | Notes | Source |
|---|---:|---:|---|---|---|---|---|---|---|
| DBLP | 6,343,626 | 50,633,439 | - | Academic | paper text-rich; venue; author | paper-paper; venue-paper; author-paper | Link Prediction; Node Classification; Clustering | Heterformer dataset | [Heterformer](https://arxiv.org/abs/2205.10282) |
| Twitter | 489,373 | 721,319 | - | Social media | tweet and POI text-rich; hashtag; user; mention | tweet-POI; user-tweet; hashtag-tweet; mention-tweet | Link Prediction; Node Classification; Clustering | Heterformer dataset | [Heterformer](https://arxiv.org/abs/2205.10282) |
| Goodreads | 1,373,802 | 42,099,586 | - | Books | book text-rich; shelves; author; format; publisher; language code | book-book; shelves-book; author-book; format-book; publisher-book; language-book | Link Prediction; Node Classification; Clustering | Heterformer dataset | [Heterformer](https://arxiv.org/abs/2205.10282) |
| TMDB | 24,412 | 104,858 | 4 | Movie | Movie; Actor; Director | Movie-Actor; Movie-Director | Node Classification | HTAG; time split | [HTAG](https://arxiv.org/pdf/2412.08937) |
| CroVal | 44,386 | 164,981 | 6 | Community QA | Question; User; Tag | Question-Question; Question-User; Question-Tag | Node Classification | HTAG; time split | [HTAG](https://arxiv.org/pdf/2412.08937) |
| ArXiv | 231,111 | 2,075,692 | 40 | Academic | Paper; Author; Field of Study | Paper-Paper; Paper-Author; Paper-FoS | Node Classification | HTAG; time split | [HTAG](https://arxiv.org/pdf/2412.08937) |
| Book | 786,257 | 9,035,291 | 8 | Literature | Book; Author; Publisher | Book-Book; Book-Author; Book-Publisher | Node Classification | HTAG; time split | [HTAG](https://arxiv.org/pdf/2412.08937) |
| DBLP | 1,989,010 | 29,830,033 | 9 | Academic | Paper; Author; Field of Study | Paper-Paper; Paper-Author; Paper-FoS | Node Classification | HTAG; time split; different from Heterformer DBLP | [HTAG](https://arxiv.org/pdf/2412.08937) |
| Patent | 5,646,139 | 8,833,738 | 120 | Patent | Patent; Inventor; Examiner | Patent-Inventor; Patent-Examiner | Node Classification | HTAG; time split | [HTAG](https://arxiv.org/pdf/2412.08937) |
| CITE | 438,304 | 1,220,373 | 85 | Catalytic materials | Paper; Author; Keywords; Journal | Paper-Paper; Paper-Author; Paper-Keywords; Paper-Journal | Node Classification | Catalyst-materials citation graph | [CITE](https://arxiv.org/pdf/2508.15392) |

### Multiplex Text-Attributed Graphs

| Name | #nodes | Relation edge counts | Domain | Task | Notes | Source |
|---|---:|---|---|---|---|---|
| Geology | 431,834 | cb: 1,000,000; sa: 1,000,000; sv: 1,000,000; cr: 1,000,000; ccb: 1,000,000 | Academic | Multiplex representation learning | METAG benchmark | [METAG](https://arxiv.org/abs/2310.06684) |
| Mathematics | 490,551 | cb: 1,000,000; sa: 1,000,000; sv: 1,000,000; cr: 1,000,000; ccb: 1,000,000 | Academic | Multiplex representation learning | METAG benchmark | [METAG](https://arxiv.org/abs/2310.06684) |
| Clothes | 208,318 | cop: 100,000; cov: 100,000; bt: 100,000; cob: 50,000 | E-commerce | Multiplex representation learning | METAG benchmark | [METAG](https://arxiv.org/abs/2310.06684) |
| Home | 192,150 | cop: 100,000; cov: 100,000; bt: 50,000; cob: 100,000 | E-commerce | Multiplex representation learning | METAG benchmark | [METAG](https://arxiv.org/abs/2310.06684) |
| Sports | 189,526 | cop: 100,000; cov: 100,000; bt: 50,000; cob: 100,000 | E-commerce | Multiplex representation learning | METAG benchmark | [METAG](https://arxiv.org/abs/2310.06684) |

### Text-Attributed Hypergraphs

| Name | #nodes | #hyperedges | #classes | Domain | Hyperedge construction / avg size | Avg. tokens | Task | Notes | Source |
|---|---:|---:|---:|---|---|---:|---|---|---|
| Cora | 1,434 | 1,579 | 7 | Academic | Co-citation | - | Node Classification | HyperBERT preprocessing | [HyperBERT](https://arxiv.org/abs/2402.07309) |
| PubMed | 3,840 | 7,963 | 3 | Academic | Co-citation | - | Node Classification | HyperBERT preprocessing | [HyperBERT](https://arxiv.org/abs/2402.07309) |
| DBLP-A | 2,591 | 2,690 | 6 | Academic | Co-authorship | - | Node Classification | HyperBERT preprocessing | [HyperBERT](https://arxiv.org/abs/2402.07309) |
| Cora-CA | 2,388 | 1,072 | 7 | Academic | Co-authorship | - | Node Classification | HyperBERT preprocessing | [HyperBERT](https://arxiv.org/abs/2402.07309) |
| IMDB | 3,939 | 2,015 | 3 | Movie | Movie-actor | - | Node Classification | HyperBERT preprocessing | [HyperBERT](https://arxiv.org/abs/2402.07309) |
| Citeseer | 1,778 | 2,118 | 6 | Academic | Avg. size 2 | 198 | Node Classification | HiTeC preprocessing | [HiTeC](https://arxiv.org/pdf/2508.03104) |
| Cora | 2,708 | 1,579 | 7 | Academic | Avg. size 3 | 189 | Node Classification | HiTeC preprocessing; different from HyperBERT Cora | [HiTeC](https://arxiv.org/pdf/2508.03104) |
| History | 41,551 | 169,454 | 12 | E-commerce | Avg. size 9 | 300 | Node Classification | HiTeC preprocessing | [HiTeC](https://arxiv.org/pdf/2508.03104) |
| Photo | 48,362 | 212,247 | 12 | E-commerce | Avg. size 11 | 189 | Node Classification | HiTeC preprocessing | [HiTeC](https://arxiv.org/pdf/2508.03104) |
| Computers | 87,229 | 277,539 | 10 | E-commerce | Avg. size 9 | 115 | Node Classification | HiTeC preprocessing | [HiTeC](https://arxiv.org/pdf/2508.03104) |
| Fitness | 173,055 | 1,468,229 | 13 | E-commerce | Avg. size 11 | 28 | Node Classification | HiTeC preprocessing | [HiTeC](https://arxiv.org/pdf/2508.03104) |

### Dynamic Text-Attributed Graphs

For bipartite GDGB rows, `#nodes` is reported as source/destination node counts.

| Name | #nodes | #edges | Edge labels / categories | Timestamps | Domain | Text attributes | Bipartite | Task / benchmark | Source |
|---|---:|---:|---:|---:|---|---|---|---|---|
| Enron | 42,711 | 797,907 | 10 | 1,006 | E-mail | Node & Edge | No | DTGB discriminative DyTAG benchmark | [DTGB](https://arxiv.org/pdf/2406.12072) |
| GDELT | 6,786 | 1,339,245 | 237 | 2,591 | Knowledge graph | Node & Edge | No | DTGB discriminative DyTAG benchmark | [DTGB](https://arxiv.org/pdf/2406.12072) |
| ICEWS1819 | 31,796 | 1,100,071 | 266 | 730 | Knowledge graph | Node & Edge | No | DTGB discriminative DyTAG benchmark | [DTGB](https://arxiv.org/pdf/2406.12072) |
| Stack elec | 397,702 | 1,262,225 | 2 | 5,224 | Multi-round dialogue | Node & Edge | Yes | DTGB discriminative DyTAG benchmark | [DTGB](https://arxiv.org/pdf/2406.12072) |
| Stack ubuntu | 674,248 | 1,497,006 | 2 | 4,972 | Multi-round dialogue | Node & Edge | Yes | DTGB discriminative DyTAG benchmark | [DTGB](https://arxiv.org/pdf/2406.12072) |
| Googlemap CT | 111,168 | 1,380,623 | 5 | 55,521 | E-commerce | Node & Edge | Yes | DTGB discriminative DyTAG benchmark | [DTGB](https://arxiv.org/pdf/2406.12072) |
| Amazon movies | 293,566 | 3,217,324 | 5 | 7,287 | E-commerce | Node & Edge | Yes | DTGB discriminative DyTAG benchmark | [DTGB](https://arxiv.org/pdf/2406.12072) |
| Yelp | 2,138,242 | 6,990,189 | 5 | 6,036 | E-commerce | Node & Edge | Yes | DTGB discriminative DyTAG benchmark | [DTGB](https://arxiv.org/pdf/2406.12072) |
| Sephora | 210,357 / 2,274 | 801,234 | 5 | 5,314 | E-commerce | Node & Edge | Yes | GDGB generative DyTAG benchmark | [GDGB](https://arxiv.org/pdf/2507.03267) |
| Dianping | 158,541 / 88,118 | 1,990,409 | 5 | 745,151 | E-commerce | Node & Edge | Yes | GDGB generative DyTAG benchmark | [GDGB](https://arxiv.org/pdf/2507.03267) |
| WikiRevision | 75,622 / 3,204 | 2,778,732 | 2 | 2,766,153 | Web Interaction | Node & Edge | Yes | GDGB generative DyTAG benchmark | [GDGB](https://arxiv.org/pdf/2507.03267) |
| WikiLife | 406,148 / 54,513 | 1,996,520 | 24 | 1,810 | Celebrity Biography | Node & Edge | Yes | GDGB generative DyTAG benchmark | [GDGB](https://arxiv.org/pdf/2507.03267) |
| IMDB | 125,714 | 1,534,162 | 20 | 122 | Movie Collaboration | Node & Edge | No | GDGB generative DyTAG benchmark | [GDGB](https://arxiv.org/pdf/2507.03267) |
| WeiboTech | 20,767 | 109,345 | 2 | 79,925 | Social Network | Node & Edge | No | GDGB generative DyTAG benchmark | [GDGB](https://arxiv.org/pdf/2507.03267) |
| WeiboDaily | 66,500 | 354,098 | 2 | 293,662 | Social Network | Node & Edge | No | GDGB generative DyTAG benchmark | [GDGB](https://arxiv.org/pdf/2507.03267) |
| Cora | 48,797 | 110,788 | 5 | 8,274 | Citation | Node & Edge | No | GDGB generative DyTAG benchmark | [GDGB](https://arxiv.org/pdf/2507.03267) |

### Multi-Modal Graphs

| Name | Graph size / scale | #nodes / entities / subjects | #edges / interactions / triples | #labels / relations | Modality | Domain | Task | Notes | Source |
|---|---|---|---|---|---|---|---|---|---|
| MM-CoDEx-s | 14,298 train+; 784 valid+; 802 test+ triples | 1,383 entities | 15,884 positive triples | 39 relations | Text, Vision | Multi-modal KGs | Knowledge Graph Completion | Missing KGC row from root MM-Graph table | [MM-Graph](https://arxiv.org/pdf/2406.16321) |
| MM-CoDEx-m | 47,617 train+; 2,628 valid+; 2,595 test+ triples | 7,697 entities | 52,840 positive triples | 51 relations | Text, Vision | Multi-modal KGs | Knowledge Graph Completion | Missing KGC row from root MM-Graph table | [MM-Graph](https://arxiv.org/pdf/2406.16321) |
| Tiktok | 726,065 interactions | 76,085 items; 36,656 users | 726,065 interactions | - | Visual 128; Acoustic 128; Text 128 | Micro-video recommendation | Recommendation | MMGCN evaluation dataset | [MMGCN](https://weiyinwei.github.io/papers/mmgcn.pdf) |
| Kwai | 1,664,305 interactions | 329,510 items; 22,611 users | 1,664,305 interactions | - | Visual 2,048; Text 128 | Micro-video recommendation | Recommendation | MMGCN evaluation dataset | [MMGCN](https://weiyinwei.github.io/papers/mmgcn.pdf) |
| MovieLens | 1,239,508 interactions | 5,986 items; 55,485 users | 1,239,508 interactions | - | Visual 2,048; Acoustic 128; Text 100 | Movie recommendation | Recommendation | MMGCN evaluation dataset | [MMGCN](https://weiyinwei.github.io/papers/mmgcn.pdf) |
| ADNI | 417 subjects; 17 non-image features | 417 subjects | - | 3 classes | 3D medical images + tabular features | Brain / Alzheimer | Medical classification | HetMed dataset | [HetMed](https://arxiv.org/pdf/2211.15158) |
| OASIS-3 | 979 subjects; 19 non-image features | 979 subjects | - | 4 classes | 3D medical images + tabular features | Brain / Alzheimer | Medical classification | HetMed dataset | [HetMed](https://arxiv.org/pdf/2211.15158) |
| ABIDE | 977 subjects; 14 non-image features | 977 subjects | - | 2 classes | 3D medical images + tabular features | Brain / Autism | Medical classification | HetMed dataset | [HetMed](https://arxiv.org/pdf/2211.15158) |
| Duke-Breast | 614 subjects; 25 non-image features | 614 subjects | - | 3 classes | Medical images + tabular features | Breast / Tumor | Medical classification | HetMed dataset | [HetMed](https://arxiv.org/pdf/2211.15158) |
| CMMD | 1,774 subjects; 4 non-image features | 1,774 subjects | - | 2 classes | Medical images + tabular features | Breast / Tumor | Medical classification | HetMed dataset | [HetMed](https://arxiv.org/pdf/2211.15158) |
| G2MF-Urban | 100K nodes; 2M edges | 100K nodes | 2M edges | - | Text + Vision | Urban planning | Node Classification | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| Pan-Cancer Atlas | 11K samples from 33 cancer types | 11K samples | - | 33 cancer types | Multi-omics | Biomedical repository | Node Classification | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| TCGA-BRCA | 1,084 breast tumor samples | 1,084 samples | - | - | Multi-omics | Biomedical repository | Node Classification | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| OMG-NAS Tencent | 8K nodes; 60K edges | 8K nodes | 60K edges | - | Text + Vision | Website articles | Node Classification | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| OMG-NAS Amazon | 100K nodes; 300K edges | 100K nodes | 300K edges | - | Text + Vision | E-commerce products | Node Classification | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| VTKG-I&C | 130 entities; 842 triples | 130 entities | 842 triples | - | Text + Vision | Multi-modal KGs | Link Prediction | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| TIVA-KG | 50K entities; 200K triples | 50K entities | 200K triples | - | Text + Vision + Audio | Multi-modal KGs | Link Prediction | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| OMG-NAS Recipe | 20K nodes; 160K edges | 20K nodes | 160K edges | - | Text + Vision | Food recipes | Graph Classification | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| Large-RG | 500K nodes | 500K nodes | - | - | Text + Vision | Food recipes | Graph Classification | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| GQA | 113K images; 23M questions | 113K images | - | - | Text + Vision | Scene graphs | Graph Question Answering | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| CLEVR | 100K images; 1M questions | 100K images | - | - | Text + Vision | Scene graphs | Graph Question Answering | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| SceneGraph-VQA | 50K images | 50K images | - | - | Text + Vision | Scene graphs | Graph Question Answering | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| MARS & MarKG | 34K triples; 13K questions | - | 34K triples | - | Text + Vision | Multi-modal KGs | Graph Reasoning | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| Richpedia | 3M entities | 3M entities | - | - | Text + Vision | Multi-modal KGs | Text Generation | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| ART500K | 311K nodes; 643M edges | 311K nodes | 643M edges | - | Text + Vision | Artwork relationships | Image Generation | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| Amazon Coview | 178K nodes; 3M edges | 178K nodes | 3M edges | - | Text + Vision | E-commerce products | Image Generation | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |
| Goodreads | 93K nodes; 637K edges | 93K nodes | 637K edges | - | Text + Vision | Book recommendation | Image Generation | Survey-collected row | [MG-LLM Survey](https://arxiv.org/pdf/2506.09738) |

### Graph-level Datasets

| Name | #graphs | #classes / tasks | Avg. #nodes | Avg. #edges | Domain | Task / notes | Source |
|---|---:|---|---:|---:|---|---|---|
| Chemblpre | 365,065 | - | 25.87 | 55.92 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| molproperties | 363,336 | - | 25.57 | 55.32 | Molecular | Graph Question Answering | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| PCBA | 437,929 | - | 25.97 | 56.20 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| HIV | 41,127 | - | 25.51 | 54.94 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| BBBP | 2,039 | - | 24.06 | 51.91 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| BACE | 1,513 | - | 34.09 | 73.72 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| toxcast | 8,575 | - | 18.76 | 38.50 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| esol | 1,128 | - | 13.29 | 27.35 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| freesolv | 642 | - | 8.72 | 16.76 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| lipo | 4,200 | - | 27.04 | 59.00 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| cyp450 | 16,896 | - | 24.52 | 53.02 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| tox21 | 7,831 | - | 18.57 | 38.59 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| muv | 93,087 | - | 24.23 | 52.56 | Molecular | Graph-level property prediction | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| ExplaGraphs | 2,766 | - | 5.17 | 4.25 | Commonsense | Graph Question Answering | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| SceneGraphs | 100,000 | - | 19.13 | 68.44 | Scene graph | Graph Question Answering | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| MAG240M-subset | 1 | 153 classes | 5,875,010 | 26,434,726 | Citation | Node Classification on one large graph | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| Ultrachat200k | 449,929 | - | 3.72 | 2.72 | Conversation | Graph Question Answering | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| Wikikg90m | 1 | - | 91,230,610 | 1,202,155,622 | Knowledge graph | Link Prediction on one large graph | [TAGLAS](https://arxiv.org/pdf/2406.14683) |
| MUTAG | 188 | 2 | 17.93 | 19.79 | Small molecules | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| NCI1 | 4,110 | 2 | 29.87 | 32.30 | Small molecules | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| Mutagenicity | 4,337 | 2 | 30.32 | 30.77 | Small molecules | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| PROTEINS | 1,113 | 2 | 39.06 | 72.82 | Bioinformatics | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| ENZYMES | 600 | 6 | 32.63 | 62.14 | Bioinformatics | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| DD | 1,178 | 2 | 284.32 | 715.66 | Bioinformatics | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| COIL-RAG | 3,900 | 100 | 3.01 | 3.02 | Computer vision | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| MSRC_21 | 563 | 20 | 77.52 | 198.32 | Computer vision | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| COLLAB | 5,000 | 3 | 74.49 | 2,457.78 | Social networks | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| IMDB-BINARY | 1,000 | 2 | 19.77 | 96.53 | Social networks | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| IMDB-MULTI | 1,500 | 3 | 13.00 | 65.94 | Social networks | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| REDDIT-BINARY | 2,000 | 2 | 429.63 | 497.75 | Social networks | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |
| REDDIT-MULTI-5K | 4,999 | 5 | 508.52 | 594.87 | Social networks | Graph Classification | [TUDataset](https://chrsmrrs.github.io/datasets/docs/datasets/) |

## Dataset Repositories

| Name                                                                                       | Type                                   | Collected by             |
|--------------------------------------------------------------------------------------------|----------------------------------------|--------------------------|
|[SNAP](http://snap.stanford.edu/data/index.html)                                            |Graphs & Networks                       | Stanford                 |
|[LAW](http://law.di.unimi.it/datasets.php)                                                  |Graphs & Networks                       | UNIMI                    |
|[BioSNAP](http://snap.stanford.edu/biodata/index.html)                                      |Biomedical Networks                     | Stanford                 |
|[KONECT](http://konect.cc/networks/)                                                        |Graphs & Networks                       | Jérôme Kunegis           |
|[Aminer](https://www.aminer.cn/data/)                                                       |Academic Networks                       | AMiner                   |
|[UCI Network Data Repository](https://networkdata.ics.uci.edu/)                             |Graphs & Networks                       | UCI Datalab               |
|[Network Repository](https://networkrepository.com)                                         |Graphs & Networks                       | -                         |
|[Open Academic Graph](https://www.microsoft.com/en-us/research/project/open-academic-graph/)|Academic Networks                       | Microsoft                |
|[Open Graph Benchmark](https://ogb.stanford.edu/)                                           |Graphs & Networks                       | Stanford                 |
|[TuDatasets](https://chrsmrrs.github.io/datasets/)                                          |Graphs & Networks                       | Christopher Morris, etc. |
|[StreamingGraphs](https://eecs.wsu.edu/~yyao/StreamingGraphs.html)                          |Streaming Graphs                        | Yibo Yao                 |
|[ARB](https://www.cs.cornell.edu/~arb/data/)                                                |Graphs & Networks                       | Austin R. Benson         |
|[SuiteSparse Matrix Collection](https://sparse.tamu.edu/)                                   |Matrix/Graphs                           | TAMU                     |
|[Web Data Commons](http://webdatacommons.org/)                                              |Hyperlink Graphs/Web Tables/RDFa        | University of Mannheim   |
|[Yahoo Webscope Datasets](https://webscope.sandbox.yahoo.com/#datasets)                     |Graphs/Ratings/Languages/Advertising    | Yahoo                    |
|[UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets.php)              |Multivariate/Text/Time-Series           | UCI                      |
|[Yelp Open Dataset](https://www.yelp.com/dataset)                                           |businesses/reviews/user data            | Yelp                     |
|[Recommender Systems Datasets](https://cseweb.ucsd.edu/~jmcauley/datasets.html)             |graphs/interactions/reviews/ratings     | UCSD                     |
|[MIcrosoft News Dataset](https://msnews.github.io/)                                         |user behavior logs                      | Microsoft                |
|[Search Query Logs](https://jeffhuang.com/search_query_logs/)                               |query logs                              | Jeff Huang               |
|[AOL DS](http://www.ccc.ipt.pt/~ricardo/experiments/AOL_DS.html)                            |query logs                              | Ricardo Campos           |
|[AWS](https://registry.opendata.aws/)                            |-                             | Amazon           |
|[Kaggle Datasets](https://www.kaggle.com/datasets)                            |-                             | Kaggle           |
|[OpenML](https://www.openml.org/search?type=data&sort=runs&status=active) | - | OpenML |
|[Datasets](https://courses.cs.washington.edu/courses/cse547/19sp/data.html) | - | - |
|[Netzschleuder](https://networks.skewed.de/) | - | - |
