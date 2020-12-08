---
title: "Workshop on Graph Learning Benchmarks (GLB 2021)"
featured_image: '/images/glb-bg.jpg'
description: "@ The Web Conference 2021"
---

# Overview

Graph-structured data are ubiquitous, heterogeneous, and diverse in real world applications. There are a variety of machine learning tasks formulated on top of the graph-structured data. While recent literature has demonstrated that graph machine learning models---especially graph neural networks (GNNs)---achieve promising performance on many such tasks [1,2,3], there is a trend that further improvements on particular tasks often face dramatically different technical bottlenecks. For example, there is a clear distinction between node-level prediction tasks and graph-level prediction tasks: the expressive power of GNNs is mainly a concern for graph-level prediction tasks, and the recently developed higher-order GNNs with better expressive power are almost entirely evaluated on graph-level prediction tasks [4,5,6]; on the other hand, techniques that help GNNs to avoid the over-smoothing problem [7] are mainly tested on node-level prediction tasks [8,9]. Furthermore, among the node-level prediction tasks, a couple of recent works have identified that the standard way of GNNs training implicitly assumes conditional independence among the node labels [10,11], and thus prevents the GNNs from fully leveraging the graph information on some tasks [12,13]. There are also studies revealing that common GNNs only work well when the node labels are smooth or the graphs exhibit homophily [14,15,16].

Unfortunately, despite the clear heterogeneity of graph machine learning tasks and their associated technical challenges, there lack enough quantity and diversity of benchmark tasks and datasets reflecting the rich heterogeneity. The lack of benchmarks not only hinders the community's progress in finding the synergy among the variety of models, it may even bias the development of new models towards narrow directions: there might be an implicit mutual selection procedure between the benchmark datasets and the development of models in the publications. The pitfalls of mainstream models, the advantages of alternatives, and the special needs for new models may all be concealed by the restricted existing benchmarks. When practitioners apply conclusions from the literature to a new task in their own context, they may be surprised by the mismatch between the known results and the reality. 

We attribute the aforementioned problems partially to the lack of a comprehensive understanding of the meta-knowledge of graph machine learning tasks. As a comparison, in computer vision, there have been well-categorized tasks in the Computing Classification System (CCS), such as object detection, image segmentation, tracking, etc. And the meta-knowledge of these tasks, e.g., the major technical challenges, are better understood compared to graph learning. A similar trend can be observed in natural language processing, where researchers have a much better understanding of the difficulty of different tasks (e.g., part-of-speech tagging, parsing, entity extraction, machine translation, textual entailment, Web search, etc.), as well as the behaviors of different families of models on each task. In both computer vision and natural language processing, there exist a rich collection of benchmark datasets for almost every task, compared to a rather narrow group of benchmarks for graph learning (e.g., [17,18,19])---partially because these communities have long recognized the importance of establishing new benchmark datasets and tasks for research progress, and have established dedicated conference tracks that encourage these types of (non-methodological) contributions. 

In consideration of these issues, this workshop aims to initiate an effort to obtain diverse graph benchmark tasks and datasets, and gain meta-knowledge of these tasks.  In particular, we propose to call for contributions by establishing novel machine learning tasks on novel graph-structured data which have the potential to provide benchmark evaluations for various graph neural network models. The acceptance of the contributed papers will be decided on the meaningfulness of the established graph learning tasks/datasets and their potential of being formalized into new benchmarks, rather than the performance of machine learning models (old or new) on these tasks. Importantly, contributions of negative results of popular, state-of-the-art models on a new task/dataset are particularly welcome, as these provide novel insights to the community's understanding of the meta-knowledge of graph machine learning.  The benefits of these contributions are three-fold:
- crowdsourcing benchmark datasets for various tasks of graph machine learning;
- identifying systematic failure modes of existing GNNs and providing new technical challenges for the development of new models, thus highlighting diverse future directions;
- raising the attention of the synergy of graph learning: e.g., explicitly categorizing tasks on graph data, identifying the unique technical challenges associated with them, and describing the common behavior patterns of existing models. 


# Call for Papers

TBD


# Organizers
- [Yuxiao Dong](https://ericdongyx.github.io/), Facebook AI
- [Danai Koutra](https://web.eecs.umich.edu/~dkoutra/), University of Michigan
- [Jiaqi Ma](http://www.jiaqima.com/), University of Michigan
- [Qiaozhu Mei](http://www-personal.umich.edu/~qmei/), University of Michigan
- [Jiong Zhu](https://www.jiongzhu.net/), University of Michigan

---

## References

- [1] Kipf, T., and Welling, M., 2017.  Semi-supervised classification with graph convolutional networks. ICLR 2017.
- [2] Gilmer, J., Schoenholz, S.S., Riley, P.F., Vinyals, O. and Dahl, G.E., 2017. Neural message passing for quantum chemistry. ICML 2017.
- [3] Yu, B., Yin, H. and Zhu, Z., 2018. Spatio-temporal graph convolutional networks: a deep learning framework for traffic forecasting. IJCAI 2018.
- [4] Morris, C., Ritzert, M., Fey, M., Hamilton, W.L., Lenssen, J.E., Rattan, G. and Grohe, M., 2019. Weisfeiler and leman go neural: Higher-order graph neural networks. AAAI 2019.
- [5] Xu, K., Hu, W., Leskovec, J. and Jegelka, S., 2018. How Powerful are Graph Neural Networks?. ICLR 2019.
- [6] Maron, H., Ben-Hamu, H., Serviansky, H. and Lipman, Y., 2019. Provably powerful graph networks. NeurIPS 2019.
- [7] Li, Q., Han, Z. and Wu, X.M., 2018. Deeper Insights into Graph Convolutional Networks for Semi-Supervised Learning. In Proceedings of the Thirty-Second AAAI Conference on Artificial Intelligence (AAAI-18) (pp. 3538-3545). Association for the Advancement of Artificial Intelligence.
- [8] Rong, Y., Huang, W., Xu, T. and Huang, J., 2019. Dropedge: Towards deep graph convolutional networks on node classification. ICLR 2019.
- [9] Zhao, L. and Akoglu, L., 2019. PairNorm: Tackling Oversmoothing in GNNs. ICLR 2019.
- [10] Qu, M., Bengio, Y. and Tang, J., 2019. GMNN: Graph Markov Neural Networks. ICML 2019.
- [11] Ma, J., Tang, W., Zhu, J. and Mei, Q., 2019. A Flexible Generative Framework for Graph-based Semi-supervised Learning. NeurIPS 2019.
- [12] Jia, J. and Benson, A.R., 2020. Residual Correlation in Graph Neural Network Regression. KDD 2020.
- [13] Ma, J., Chang, B., Zhang, X. and Mei, Q., 2020. CopulaGNN: Towards Integrating Representational and Correlational Roles of Graphs in Graph Neural Networks. arXiv preprint arXiv:2010.02089.
- [14] NT, H. and Maehara, T., 2019. Revisiting graph neural networks: All we have is low-pass filters. arXiv preprint arXiv:1905.09550.
- [15] Hou, Y., Zhang, J., Cheng, J., Ma, K., Ma, R.T., Chen, H. and Yang, M.C., 2019. Measuring and improving the use of graph information in graph neural networks. ICLR 2019.
- [16] Zhu, J., Yan, Y., Zhao, L., Heimann, M., Akoglu, L. and Koutra, D., 2020. Beyond Homophily in Graph Neural Networks: Current Limitations and Effective Designs. NeurIPS 2020.
- [17] Sen, P., Namata, G., Bilgic, M., Getoor, L., Galligher, B. and Eliassi-Rad, T., 2008. Collective classification in network data. AI magazine, 29(3), pp.93-93.
- [18] Namata, G., London, B., Getoor, L., Huang, B. and EDU, U., 2012. Query-driven active surveying for collective classification. In 10th International Workshop on Mining and Learning with Graphs (Vol. 8).
- [19] Hu, W., Fey, M., Zitnik, M., Dong, Y., Ren, H., Liu, B., Catasta, M. and Leskovec, J., 2020. Open graph benchmark: Datasets for machine learning on graphs. arXiv preprint arXiv:2005.00687.