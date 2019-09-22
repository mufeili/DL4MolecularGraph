Deep Learning for Molecular Graphs
**********************************

This is a paper list of deep learning on molecular graphs from both the ML community and the computational chemistry
community.-

This is inspired by the
`Literature of Deep Learning for Graphs <https://github.com/DeepGraphLearning/LiteratureDL4Graph>`_ project.

.. contents::
    :local:
    :depth: 2

.. sectnum::
    :depth: 2

.. role:: venue(strong)

Review
======

`The Rise of Deep Learning in Drug Discovery
<https://www.ncbi.nlm.nih.gov/pubmed/29366762>`_
    | `Hongming Chen, Ola Engkvist, Yinhai Wang, Marcus Olivecrona, Thomas Blaschke`
    | :venue:`Drug Discov Today, 2018, 23, 6`
    | `property and activity prediction, de novo design, reaction prediction, retrosynthetic analysis, ligand–protein interactions, biological imaging analysis`

Benchmark and Dataset
=====================

Discriminative Models
---------------------

`MoleculeNet: A Benchmark for Molecular Machine Learning
<https://arxiv.org/abs/1703.00564>`_
    | `Zhenqin Wu, Bharath Ramsundar, Evan N. Feinberg, Joseph Gomes, Caleb Geniesse, Aneesh S. Pappu, Karl Leswing, Vijay Pande`
    | :venue:`Journal of Chemical Sciences, 2018, 9`
    | `property prediction, public datasets, evaluation metrics, baseline results, quantum mechanics, physical chemistry, biophysics, physiology`
    | `Website <http://moleculenet.ai/>`_

`Alchemy: A Quantum Chemistry Dataset for Benchmarking AI Models
<https://arxiv.org/abs/1906.09427>`_
    | `Guangyong Chen, Pengfei Chen, Chang-Yu Hsieh, Chee-Kong Lee, Benben Liao, Renjie Liao, Weiwen Liu, Jiezhong Qiu, Qiming Sun, Jie Tang, Richard Zemel, Shengyu Zhang`
    | :venue:`arXiv 1906`
    | `property prediction, public datasets, baseline results, quantum mechanics`
    | `Website <https://alchemy.tencent.com/>`_

Generative Models
-----------------

`GuacaMol: Benchmarking Models for De Novo Molecular Design
<https://arxiv.org/abs/1811.09621>`_
    | `Nathan Brown, Marco Fiscato, Marwin H.S. Segler, Alain C. Vaucher`
    | :venue:`Journal of Chemical Information and Modeling, 2019, 59, 3`
    | `ChEMBL, public datasets, evaluation metrics, baseline results, distribution learning, goal-directed optimization`
    | `Github <https://github.com/BenevolentAI/guacamol>`_

`Molecular Sets (MOSES): A Benchmarking Platform for Molecular Generation Models
<https://arxiv.org/abs/1811.12823>`_
    | `Daniil Polykovskiy, Alexander Zhebrak, Benjamin Sanchez-Lengeling, Sergey Golovanov, Oktai Tatanov, Stanislav Belyaev, Rauf Kurbanov, Aleksey Artamonov, Vladimir Aladinskiy, Mark Veselov, Artur Kadurin, Sergey Nikolenko, Alan Aspuru-Guzik, Alex Zhavoronkov`
    | :venue:`arXiv 1811`
    | `ZINC, public datasets, evaluation metrics, baseline results, distribution-learning`
    | `Github <https://github.com/molecularsets/moses>`_

Discriminative Models
=====================

`Convolutional Networks on Graphs for Learning Molecular Fingerprints
<https://arxiv.org/abs/1509.09292>`_
    | `David Duvenaud, Dougal Maclaurin, Jorge Aguilera-Iparraguirre, Rafael Gómez-Bombarelli, Timothy Hirzel, Alán Aspuru-Guzik, Ryan P. Adams`
    | :venue:`NeurIPS 2015`
    | `graph neural networks`
    | `Github <https://github.com/HIPS/neural-fingerprint>`_

`Molecular graph convolutions: moving beyond fingerprints
<https://arxiv.org/abs/1603.00856>`_
    | `Steven Kearnes, Kevin McCloskey, Marc Berndl, Vijay Pande, Patrick Riley`
    | :venue:`Journal of Computer-Aided Molecular Design, 2016, 30, 8`
    | `graph neural networks`

`Low Data Drug Discovery with One-shot Learning
<https://arxiv.org/abs/1611.03199>`_
    | `Han Altae-Tran, Bharath Ramsundar, Aneesh S. Pappu, Vijay Pande`
    | :venue:`ACS Central Science, 2017, 3, 4`
    | `graph neural networks, one-shot learning`

`Quantum-chemical Insights from Deep Tensor Neural Networks
<https://www.nature.com/articles/ncomms13890>`_
    | `Kristof T. Schütt, Farhad Arbabzadah, Stefan Chmiela, Klaus R. Müller, Alexandre Tkatchenko`
    | :venue:`Nature Communications 8`
    | `graph neural networks, quantum mechanics`

`Neural Message Passing for Quantum Chemistry
<https://arxiv.org/abs/1704.01212>`_
    | `Justin Gilmer, Samuel S. Schoenholz, Patrick F. Riley, Oriol Vinyals, George E. Dahl`
    | :venue:`ICML 2017`
    | `graph neural networks, quantum mechanics`
    | `Github <https://github.com/brain-research/mpnn>`_

`Deep Learning Based Regression and Multi-class Models for Acute Oral Toxicity Prediction with Automatic Chemical Feature Extraction
<https://arxiv.org/abs/1704.04718v3>`_
    | `Youjun Xu, Jianfeng Pei, Luhua Lai`
    | :venue:`Journal of Chemical Information and Modeling 2017, 57, 11`
    | `graph neural networks`

`Deriving Neural Architectures from Sequence and Graph Kernels
<https://arxiv.org/abs/1705.09037>`_
    | `Tao Lei, Wengong Jin, Regina Barzilay, Tommi Jaakkola`
    | :venue:`ICML 2017`
    | `graph neural networks`
    | `Github <https://github.com/taolei87/icml17_knn>`_

`SchNet: A continuous-filter convolutional neural network for modeling quantum interactions
<https://arxiv.org/abs/1706.08566>`_
    | `Kristof T. Schütt, Pieter-Jan Kindermans, Huziel E. Sauceda, Stefan Chmiela, Alexandre Tkatchenko, Klaus-Robert Müller`
    | :venue:`arXiv 1706`
    | `graph neural networks, quantum mechanics`
    | `Github <https://github.com/atomistic-machine-learning/schnetpack>`_

`Learning Graph-Level Representation for Drug Discovery
<https://arxiv.org/pdf/1709.03741.pdf>`_
    | `Junying Li, Deng Cai, Xiaofei He`
    | :venue:`arXiv 1709`
    | `graph neural networks`
    | `Github <https://github.com/ZJULearning/graph_level_drug_discovery>`_

`Predicting Organic Reaction Outcomes with Weisfeiler-Lehman Network
<https://arxiv.org/abs/1709.04555>`_
    | `Wengong Jin, Connor W. Coley, Regina Barzilay, Tommi Jaakkola`
    | :venue:`NeurIPS 2017`
    | `graph neural networks, reaction prediction`
    | `Github <https://github.com/wengong-jin/nips17-rexgen>`_

`Convolutional Embedding of Attributed Molecular Graphs for Physical Property Prediction
<https://pubs.acs.org/doi/10.1021/acs.jcim.6b00601>`_
    | `Connor W. Coley, Regina Barzilay, William H. Green, Tommi S. Jaakkola, Klavs F. Jensen`
    | :venue:`Journal of Chemical Information and Modeling, 2017, 57, 8`
    | `graph neural networks`
    | `Github <https://github.com/connorcoley/conv_qsar_fast>`_

`PotentialNet for Molecular Property Prediction
<https://pubs.acs.org/doi/full/10.1021/acscentsci.8b00507>`_
    | `Evan N. Feinberg, Debnil Sur, Zhenqin Wu, Brooke E. Husic, Huanghao Mai, Yang Li, Saisai Sun, Jianyi Yang, Bharath Ramsundar, Vijay S. Pande`
    | :venue:`ACS Central Science 2018, 4, 11`
    | `graph neural networks, protein-ligand binding affinity, metric`

`Deeply Learning Molecular Structure-property Relationships Using Attention and Gate-augmented Graph Convolutional Network
<https://arxiv.org/abs/1805.10988>`_
    | `Seongok Ryu, Jaechang Lim, Seung Hwan Hong, Woo Youn Kim`
    | :venue:`arXiv 1805`
    | `graph neural networks`
    | `Github <https://github.com/SeongokRyu/augmented-GCN>`_

`Modeling polypharmacy side effects with graph convolutional networks
<https://academic.oup.com/bioinformatics/article/34/13/i457/5045770>`_
    | `Marinka Zitnik, Monica Agrawal, Jure Leskovec`
    | :venue:`Bioinformatics, Volume 34, Issue 13, 01 July 2018`
    | `graph neural networks, polypharmacy side effect, interaction prediction, multi-relation`
    | `Github <https://github.com/marinkaz/decagon>`_

`Graph Convolutional Neural Networks for Predicting Drug-Target Interactions
<https://www.biorxiv.org/content/10.1101/473074v1>`_
    | `Wen Torng, Russ B. Altman`
    | :venue:`bioRXiv`
    | `graph neural networks, auto encoders, interaction prediction`

`Compound–protein interaction prediction with end-to-end learning of neural networks for graphs and sequences
<https://academic.oup.com/bioinformatics/article/35/2/309/5050020>`_
    | `Masashi Tsubaki, Kentaro Tomii, Jun Sese`
    | :venue:`Bioinformatics, Volume 35, Issue 2, 15 January 2019`
    | `graph neural networks, interaction prediction`
    | `Github <https://github.com/masashitsubaki/CPI_prediction>`_

`Analyzing Learned Molecular Representations for Property Prediction
<https://arxiv.org/abs/1904.01561v4>`_
    | `Kevin Yang, Kyle Swanson, Wengong Jin, Connor Coley, Philipp Eiden, Hua Gao, Angel Guzman-Perez, Timothy Hopper, Brian Kelley, Miriam Mathea, Andrew Palmer, Volker Settels, Tommi Jaakkola, Klavs Jensen, Regina Barzilay`
    | :venue:`Journal of Chemical Information and Modeling, 2019, 59, 8`
    | `graph neural networks, benchmark results, quantum mechanics, physical chemistry, biophysics, physiology`
    | `Github <https://github.com/swansonk14/chemprop#requirements>`_

`A Bayesian Graph Convolutional Network for Reliable Prediction of Molecular Properties with Uncertainty Quantification
<https://pubs.rsc.org/en/content/articlelanding/2019/sc/c9sc01992h#!divAbstract>`_
    | `Seongok Ryu, Yongchan Kwon, Woo Youn Kim`
    | :venue:`Chemical Science, 2019, 36`
    | `graph neural networks, Bayesian inference, uncertainty`

`Predicting Drug–Target Interaction Using a Novel Graph Neural Network with 3D Structure-Embedded Graph Representation
<https://pubs.acs.org/doi/10.1021/acs.jcim.9b00387>`_
    | `Jaechang Lim, Seongok Ryu, Kyubyong Park, Yo Joong Choe, Jiyeon Ham, Woo Youn Kim`
    | :venue:`Journal of Chemical Information and Modeling, 2019`
    | `graph neural networks, interaction prediction, 3D information`

`Molecule Property Prediction Based on Spatial Graph Embedding
<https://pubs.acs.org/doi/10.1021/acs.jcim.9b00410>`_
    | `Xiaofeng Wang, Zhen Li, Mingjian Jiang, Shuang Wang, Shugang Zhang, Zhiqiang Wei`
    | :venue:`Journal of Chemical Information and Modeling, 2019`
    | `graph neural networks`
    | `Github <https://github.com/wxfsd/C-SGEN>`_

`DeepChemStable: Chemical Stability Prediction with an Attention-Based Graph Convolution Network
<https://pubs.acs.org/doi/10.1021/acs.jcim.8b00672>`_
    | `Xiuming Li, Xin Yan, Qiong Gu, Huihao Zhou, Di Wu, Jun Xu`
    | :venue:`Journal of Chemical Information and Modeling, 2019, 59, 3`
    | `graph neural networks`
    | `Github <https://github.com/MingCPU/DeepChemStable>`_

`Pre-training Graph Neural Networks
<https://arxiv.org/abs/1905.12265>`_
    | `Weihua Hu, Bowen Liu, Joseph Gomes, Marinka Zitnik, Percy Liang, Vijay Pande, Jure Leskovec`
    | :venue:`arXiv 1905`
    | `graph neural networks, pre-training, self-supervised learning`

Generative Models
=================

`Junction Tree Variational Autoencoder for Molecular Graph Generation
<https://arxiv.org/abs/1802.04364>`_
    | `Wengong Jin, Regina Barzilay, Tommi Jaakkola`
    | :venue:`ICML 2018`
    | `graph neural networks, VAE, goal-directed optimization`
    | `Github <https://github.com/wengong-jin/icml18-jtnn>`_

`Learning Deep Generative Models of Graphs
<https://arxiv.org/abs/1803.03324>`_
    | `Yujia Li, Oriol Vinyals, Chris Dyer, Razvan Pascanu, Peter Battaglia`
    | :venue:`arXiv 1803`
    | `graph neural networks, distribution learning, autoregressive, conditional generation`

`Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation
<https://arxiv.org/abs/1806.02473>`_
    | `Jiaxuan You, Bowen Liu, Rex Ying, Vijay Pande, Jure Leskovec`
    | :venue:`NeurIPS 2018`
    | `graph neural networks, RL, GAN, MDP, goal-directed optimization, property targeting`
    | `Github <https://github.com/bowenliu16/rl_graph_generation>`_

`Multi-resolution Autoregressive Graph-to-Graph Translation for Molecules
<https://arxiv.org/abs/1907.11223>`_
    | `Wengong Jin, Regina Barzilay, Tommi Jaakkola`
    | :venue:`arXiv 1907`
    | `graph neural networks, goal-directed optimization, autoregressive, hierarchical, VAE`
