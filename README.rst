Deep Learning for Graphs in Chemistry and Biology
*************************************************

This is a paper list of deep learning on graphs in chemistry and biology from ML community, chemistry community and biology community.

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

`Opportunities and obstacles for deep learning in biology and medicine
<https://royalsocietypublishing.org/doi/10.1098/rsif.2017.0387>`_
    | `Travers Ching, Daniel S. Himmelstein, Brett K. Beaulieu-Jones, Alexandr A. Kalinin, Brian T. Do, Gregory P. Way, Enrico Ferrero, Paul-Michael Agapow, Michael Zietz, Michael M. Hoffman, Wei Xie, Gail L. Rosen, Benjamin J. Lengerich, Johnny Israeli, Jack Lanchantin, Stephen Woloszynek, Anne E. Carpenter, Avanti Shrikumar, Jinbo Xu, Evan M. Cofer, Christopher A. Lavender, Srinivas C. Turaga, Amr M. Alexandari, Zhiyong Lu, David J. Harris, Dave DeCaprio, Yanjun Qi, Anshul Kundaje, Yifan Peng, Laura K. Wiley, Marwin H. S. Segler, Simina M. Boca, S. Joshua Swamidass, Austin Huang, Anthony Gitter and Casey S. Greene`
    | :venue:`Journal of the Royal Society Interface, 2018, Volume 15, Issue 141`
    | `Protein-protein interaction networks and graph analysis, Chemical featurization and representation learning`

`Applications of Machine Learning in Drug Discovery and Development
<https://www.nature.com/articles/s41573-019-0024-5>`_
    | `Jessica Vamathevan, Dominic Clark, Paul Czodrowski, Ian Dunham, Edgardo Ferran, George Lee, Bin Li, Anant Madabhushi, Parantu Shah, Michaela Spitzer, Shanrong Zhao`
    | :venue:`Nature Reviews Drug Discovery 18`
    | `target identification, molecule optimization, biomarker discovery, computational pathology`

`Deep learning for molecular design—a review of the state of the art
<https://pubs.rsc.org/en/content/articlelanding/2019/ME/C9ME00039A#!divAbstract>`_
    | `Daniel C. Elton, Zois Boukouvalas, Mark D. Fuge, Peter W. Chunga`
    | :venue:`Molecular Systems Design & Engineering, 2019, 4`
    | `molecular representation, deep learning architectures, evaluation, prospective and future directions`

`Generative Models for Automatic Chemical Design
<https://arxiv.org/abs/1907.01632>`_
    | `Daniel Schwalbe-Koda, Rafael Gómez-Bombarelli`
    | :venue:`arXiv 1907`
    | `inverse design, generative models, prospects, challenges`

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

`Atomic Convolutional Networks for Predicting Protein-Ligand Binding Affinity
<https://arxiv.org/abs/1703.10603>`_
    | `Joseph Gomes, Bharath Ramsundar, Evan N. Feinberg, Vijay S. Pande`
    | :venue:`arXiv 1703`
    | `graph neural networks, protein-ligand binding affinity, PDBBind, nearest neighbor graphs`

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

`Prediction Errors of Molecular Machine Learning Models Lower than Hybrid DFT Error
<https://pubs.acs.org/doi/abs/10.1021%2Facs.jctc.7b00577>`_
    | `Felix A. Faber, Luke Hutchison, Bing Huang, Justin Gilmer, Samuel S. Schoenholz, George E. Dahl, Oriol Vinyals, Steven Kearnes, Patrick F. Riley, O. Anatole von Lilienfeld`
    | :venue:`Journal of Chemical Theory and Computation 2017, 13, 11`
    | `graph neural networks, benchmark results`

`Predicting Organic Reaction Outcomes with Weisfeiler-Lehman Network
<https://arxiv.org/abs/1709.04555>`_
    | `Wengong Jin, Connor W. Coley, Regina Barzilay, Tommi Jaakkola`
    | :venue:`NeurIPS 2017`
    | `graph neural networks, reaction prediction`
    | `Github <https://github.com/wengong-jin/nips17-rexgen>`_

`Protein Interface Prediction Using Graph Convolutional Networks
<https://papers.nips.cc/paper/7231-protein-interface-prediction-using-graph-convolutional-networks>`_
    | `Alex Fout, Jonathon Byrd, Basir Shariat, Asa Ben-Hur`
    | :venue:`NeurIPS 2017`
    | `graph neural networks, protein interface prediction`
    | `Github <https://github.com/fouticus/pipgcn>`_

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

`Chemi-net: a graph convolutional network for accurate drug property prediction
<https://arxiv.org/abs/1803.06236>`_
    | `Ke Liu, Xiangyan Sun, Lei Jia, Jun Ma, Haoming Xing, Junqiu Wu, Hua Gao, Yax Sun, Florian Boulnois, Jie Fan`
    | :venue:`arXiv 1803`
    | `graph neural networks`

`Deeply Learning Molecular Structure-property Relationships Using Attention and Gate-augmented Graph Convolutional Network
<https://arxiv.org/abs/1805.10988>`_
    | `Seongok Ryu, Jaechang Lim, Seung Hwan Hong, Woo Youn Kim`
    | :venue:`arXiv 1805`
    | `graph neural networks`
    | `Github <https://github.com/SeongokRyu/augmented-GCN>`_

`Neural Message Passing with Edge Updates for Predicting Properties of Molecules and Materials
<https://arxiv.org/abs/1806.03146>`_
    | `Peter Bjørn Jørgensen, Karsten Wedel Jacobsen, Mikkel N. Schmidt`
    | :venue:`arXiv 1806`
    | `graph neural networks`

`Modeling polypharmacy side effects with graph convolutional networks
<https://academic.oup.com/bioinformatics/article/34/13/i457/5045770>`_
    | `Marinka Zitnik, Monica Agrawal, Jure Leskovec`
    | :venue:`Bioinformatics, Volume 34, Issue 13, 01 July 2018`
    | `graph neural networks, polypharmacy side effects, interaction prediction, multi-relation`
    | `Github <https://github.com/marinkaz/decagon>`_

`BayesGrad: Explaining Predictions of Graph Convolutional Networks
<https://arxiv.org/abs/1807.01985>`_
    | `Hirotaka Akita, Kosuke Nakago, Tomoki Komatsu, Yohei Sugawara, Shin-ichi Maeda, Yukino Baba, Hisashi Kashima`
    | :venue:`arXiv 1807`
    | `graph neural networks, interpretability`

`Graph Convolutional Neural Networks for Predicting Drug-Target Interactions
<https://www.biorxiv.org/content/10.1101/473074v1>`_
    | `Wen Torng, Russ B. Altman`
    | :venue:`bioRXiv`
    | `graph neural networks, auto encoders, interaction prediction`

`Three-Dimensionally Embedded Graph Convolutional Network (3DGCN) for Molecule Interpretation
<https://arxiv.org/abs/1811.09794>`_
    | `Hyeoncheol Cho, Insung S. Choi`
    | :venue:`arXiv 1811`
    | `graph neural networks, property prediction, interpretability`

`A graph-convolutional neural network model for the prediction of chemical reactivity
<https://pubs.rsc.org/en/content/articlelanding/2019/SC/C8SC04228D#!divAbstract>`_
    | `Connor W. Coley, Wengong Jin, Luke Rogers, Timothy F. Jamison, Tommi S. Jaakkola, William H. Green, Regina Barzilay, Klavs F. Jensen`
    | :venue:`Chemical Science, 2019, 10`
    | `graph neural networks, reaction prediction`
    | `Github <https://github.com/connorcoley/rexgen_direct>`_

`Compound–protein interaction prediction with end-to-end learning of neural networks for graphs and sequences
<https://academic.oup.com/bioinformatics/article/35/2/309/5050020>`_
    | `Masashi Tsubaki, Kentaro Tomii, Jun Sese`
    | :venue:`Bioinformatics, Volume 35, Issue 2, 15 January 2019`
    | `graph neural networks, interaction prediction`
    | `Github <https://github.com/masashitsubaki/CPI_prediction>`_

`Graph Warp Module: an Auxiliary Module for Boosting the Power of Graph Neural Networks in Molecular Graph Analysis
<https://arxiv.org/abs/1902.01020>`_
    | `Katsuhiko Ishiguro, Shin-ichi Maeda, Masanori Koyama`
    | :venue:`arXiv 1902`
    | `graph neural networks`
    | `Github <https://github.com/pfnet-research/chainer-chemistry>`_

`A Transformer Model for Retrosynthesis
<https://chemrxiv.org/articles/A_Transformer_Model_for_Retrosynthesis/8058464>`_
    | `Pavel Karpov, Guillaume Godin, Igor Tetko`
    | :venue:`ChemRxiv`
    | `graph neural networks, transformer, retrosynthesis, SMILES, USPTO`
    | `Github <https://github.com/bigchem/retrosynthesis>`_

`Functional Transparency for Structured Data: a Game-Theoretic Approach
<https://arxiv.org/abs/1902.09737>`_
    | `Guang-He Lee, Wengong Jin, David Alvarez-Melis, Tommi S. Jaakkola`
    | :venue:`ICML 2019`
    | `graph neural networks, interpretability, transparency, decision trees`

`Interpretable Deep Learning in Drug Discovery
<https://arxiv.org/abs/1903.02788>`_
    | `Kristina Preuer, Günter Klambauer, Friedrich Rippmann, Sepp Hochreiter, Thomas Unterthiner`
    | :venue:`arXiv 1903`
    | `graph neural networks, interpretability`
    | `Github <https://github.com/bioinf-jku/interpretable_ml_drug_discovery>`_

`Analyzing Learned Molecular Representations for Property Prediction
<https://arxiv.org/abs/1904.01561v4>`_
    | `Kevin Yang, Kyle Swanson, Wengong Jin, Connor Coley, Philipp Eiden, Hua Gao, Angel Guzman-Perez, Timothy Hopper, Brian Kelley, Miriam Mathea, Andrew Palmer, Volker Settels, Tommi Jaakkola, Klavs Jensen, Regina Barzilay`
    | :venue:`Journal of Chemical Information and Modeling, 2019, 59, 8`
    | `graph neural networks, benchmark results, quantum mechanics, physical chemistry, biophysics, physiology`
    | `Github <https://github.com/swansonk14/chemprop#requirements>`_

`Graph Networks as a Universal Machine Learning Framework for Molecules and Crystals
<https://pubs.acs.org/doi/10.1021/acs.chemmater.9b01294>`_
    | `Chi Chen, Weike Ye, Yunxing Zuo, Chen Zheng, Shyue Ping Ong`
    | :venue:`Chemistry of Materials, 2019, 31, 9`
    | `graph neural networks, transfer learning`
    | `Github <https://github.com/materialsvirtuallab/megnet>`_

`A Bayesian Graph Convolutional Network for Reliable Prediction of Molecular Properties with Uncertainty Quantification
<https://pubs.rsc.org/en/content/articlelanding/2019/sc/c9sc01992h#!divAbstract>`_
    | `Seongok Ryu, Yongchan Kwon, Woo Youn Kim`
    | :venue:`Chemical Science, 2019, 36`
    | `graph neural networks, Bayesian inference, uncertainty`

`Predicting Drug-Target Interaction Using a Novel Graph Neural Network with 3D Structure-Embedded Graph Representation
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

`Drug-Drug Adverse Effect Prediction with Graph Co-Attention
<https://arxiv.org/abs/1905.00534>`_
    | `Andreea Deac, Yu-Hsiang Huang, Petar Veličković, Pietro Liò, Jian Tang`
    | :venue:`arXiv 1905`
    | `graph neural networks, polypharmacy side effects`

`Pre-training Graph Neural Networks
<https://arxiv.org/abs/1905.12265>`_
    | `Weihua Hu, Bowen Liu, Joseph Gomes, Marinka Zitnik, Percy Liang, Vijay Pande, Jure Leskovec`
    | :venue:`arXiv 1905`
    | `graph neural networks, pre-training, self-supervised learning, protein function prediction, molecular property prediction`

`Graph Normalizing Flows
<https://arxiv.org/abs/1905.13177>`_
    | `Jenny Liu, Aviral Kumar, Jimmy Ba, Jamie Kiros, Kevin Swersky`
    | :venue:`NeurIPS 2019`
    | `graph neural networks, invertible model, flow model, AE, QM9`

`Retrosynthesis Prediction with Conditional Graph Logic Network
<https://papers.nips.cc/paper/9090-retrosynthesis-prediction-with-conditional-graph-logic-network>`_
    | `Hanjun Dai, Chengtao Li, Connor W. Coley, Bo Dai, Le Song`
    | :venue:`NeurIPS 2019`
    | `graphical model, graph neural networks, retrosynthesis`

`Molecular Property Prediction: A Multilevel Quantum Interactions Modeling Perspective
<https://arxiv.org/pdf/1906.11081.pdf>`_
    | `Chengqiang Lu, Qi Liu, Chao Wang, Zhenya Huang, Peize Lin, Lixin He`
    | :venue:`AAAI 2019`
    | `graph neural networks, quantum mechanics`

`Molecular Transformer: A Model for Uncertainty-Calibrated Chemical Reaction Prediction
<https://pubs.acs.org/doi/full/10.1021/acscentsci.9b00576>`_
    | `Philippe Schwaller, Teodoro Laino, Théophile Gaudin, Peter Bolgar, Christopher A. Hunter, Costas Bekas, Alpha A. Lee`
    | :venue:`ACS Central Science 2019, 5, 9`
    | `graph neural networks, reaction prediction, SMILES, machine translation, transformer`

`Decomposing Retrosynthesis into Reactive Center Prediction and Molecule Generation
<https://www.biorxiv.org/content/10.1101/677849v1.full>`_
    | `Xianggen Liu, Pengyong Li, Sen Song`
    | :venue:`bioRXiv`
    | `retrosynthesis, GAT, attention, LSTM, USPTO`

`Pushing the Boundaries of Molecular Representation for Drug Discovery with the Graph Attention Mechanism
<https://pubs.acs.org/doi/abs/10.1021/acs.jmedchem.9b00959>`_
    | `Zhaoping Xiong, Dingyan Wang, Xiaohong Liu, Feisheng Zhong, Xiaozhe Wan, Xutong Li, Zhaojun Li, Xiaomin Luo, Kaixian Chen, Hualiang Jiang, Mingyue Zheng`
    | :venue:`Journal of Medicinal Chemistry 2019`
    | `graph neural networks, interpretability`
    | `Github <https://github.com/OpenDrugAI/AttentiveFP>`_

`Structure-Based Function Prediction using Graph Convolutional Networks
<https://www.biorxiv.org/content/10.1101/786236v1>`_
    | `Vladimir Gligorijevic, P. Douglas Renfrew, Tomasz Kosciolek, Julia Koehler Leman, Kyunghyun Cho, Tommi Vatanen, Daniel Berenberg, Bryn Taylor, Ian M. Fisk, Ramnik J. Xavier, Rob Knight, Richard Bonneau`
    | :venue:`bioRXiv`
    | `graph neural networks, protein function prediction, Protein Data Bank, pre-trained language model, Bi-LSTM, interpretability`

`Molecule-Augmented Attention Transformer
<https://grlearning.github.io/papers/105.pdf>`_
    | `Łukasz Maziarka, Tomasz Danel, Sławomir Mucha, Krzysztof Rataj, Jacek Tabor, Stanisław Jastrz˛ebski`
    | :venue:`Graph Representation Learning Workshop at NeurIPS 2019`
    | `graph neural networks, property prediction, transformer`

`Learning Interaction Patterns from Surface Representations of Protein Structure
<https://grlearning.github.io/papers/115.pdf>`_
    | `Pablo Gainza, Freyr Sverrisson, Federico Monti, Emanuele Rodolà, Davide Boscaini, Michael Bronstein, Bruno E. Correia`
    | :venue:`Graph Representation Learning Workshop at NeurIPS 2019`
    | `graph neural networks, molecular surface, pocket similarity comparison, protein-protein interaction site prediction, prediction of interaction patterns`

`Machine Learning for Scent: Learning Generalizable Perceptual Representations of Small Molecules
<https://arxiv.org/abs/1910.10685>`_
    | `Benjamin Sanchez-Lengeling, Jennifer N Wei, Brian K Lee, Richard C Gerkin, Alán Aspuru-Guzik, and Alexander B Wiltschko`
    | :venue:`arXiv 1910`
    | `graph neural networks, property prediction, quantitative structure-odor relationship (QSOR) modeling, transfer learning`

`Deciphering interaction fingerprints from protein molecular surfaces using geometric deep learning
<https://www.nature.com/articles/s41592-019-0666-6>`_
    | `P. Gainza, F. Sverrisson, F. Monti, E. Rodol, D. Boscaini, M. M. Bronstein, B. E. Correia`
    | :venue:`Nature Methods 2019`
    | `graph neural networks, molecular surface interaction fingerprinting, geometric deep learning, protein pocket-ligand prediction, protein-protein interaction site prediction, ultrafast scanning of surfaces`

Generative Models
=================

`GraphVAE: Towards Generation of Small Graphs Using Variational Autoencoders
<https://arxiv.org/abs/1802.03480>`_
    | `Martin Simonovsky, Nikos Komodakis`
    | :venue:`arXiv 1802`
    | `graph neural networks, VAE, non-autoregressive, conditional generation, distribution-learning, QM9, ZINC`

`Junction Tree Variational Autoencoder for Molecular Graph Generation
<https://arxiv.org/abs/1802.04364>`_
    | `Wengong Jin, Regina Barzilay, Tommi Jaakkola`
    | :venue:`ICML 2018`
    | `graph neural networks, VAE, goal-directed optimization, ZINC`
    | `Github <https://github.com/wengong-jin/icml18-jtnn>`_

`NEVAE: A Deep Generative Model for Molecular Graphs
<https://arxiv.org/abs/1802.05283>`_
    | `Bidisha Samanta, Abir De, Gourhari Jana, Pratim Kumar Chattaraj, Niloy Ganguly, Manuel Gomez-Rodriguez`
    | :venue:`AAAI 2019`
    | `graph neural networks, VAE, distribution learning, goal-directed optimization, ZINC, QM9`
    | `Github <https://github.com/Networks-Learning/nevae>`_

`Learning Deep Generative Models of Graphs
<https://arxiv.org/abs/1803.03324>`_
    | `Yujia Li, Oriol Vinyals, Chris Dyer, Razvan Pascanu, Peter Battaglia`
    | :venue:`arXiv 1803`
    | `graph neural networks, distribution learning, autoregressive, conditional generation, ChEMBL, ZINC`

`MolGAN: An implicit generative model for small molecular graphs
<https://arxiv.org/abs/1805.11973>`_
    | `Nicola De Cao, Thomas Kipf`
    | :venue:`arXiv 1805`
    | `graph neural networks, goal-directed optimization, non-autoregressive, RL, GAN, QM9`
    | `Github <https://github.com/nicola-decao/MolGAN>`_

`Constrained Graph Variational Autoencoders for Molecule Design
<https://arxiv.org/abs/1805.09076>`_
    | `Qi Liu, Miltiadis Allamanis, Marc Brockschmidt, Alexander L. Gaunt`
    | :venue:`NeurIPS 2018`
    | `graph neural networks, distribution-learning, goal-directed optimization, autoregressive, VAE, QM9, ZINC, CEPDB`
    | `Github <https://github.com/microsoft/constrained-graph-variational-autoencoder>`_

`Graph Convolutional Policy Network for Goal-Directed Molecular Graph Generation
<https://arxiv.org/abs/1806.02473>`_
    | `Jiaxuan You, Bowen Liu, Rex Ying, Vijay Pande, Jure Leskovec`
    | :venue:`NeurIPS 2018`
    | `graph neural networks, RL, GAN, MDP, goal-directed optimization, property targeting, ZINC`
    | `Github <https://github.com/bowenliu16/rl_graph_generation>`_

`Fréchet ChemNet Distance: A Metric for Generative Models for Molecules in Drug Discovery
<https://pubs.acs.org/doi/abs/10.1021/acs.jcim.8b00234>`_
    | `Kristina Preuer, Philipp Renz, Thomas Unterthiner, Sepp Hochreiter, Günter Klambauer`
    | :venue:`Journal of Chemical Information and Modeling 2018, 58, 9`
    | `evaluation metric`
    | `Github <https://github.com/bioinf-jku/FCD>`_

`Constrained Generation of Semantically Valid Graphs via Regularizing Variational Autoencoders
<https://arxiv.org/abs/1809.02630>`_
    | `Tengfei Ma, Jie Chen, Cao Xiao`
    | :venue:`NeurIPS 2018`
    | `ConvNet, DeconvNet, non-autoregressive, distribution learning, QM9, ZINC`

`Molecular Hypergraph Grammar with Its Application to Molecular Optimization
<https://arxiv.org/abs/1809.02745>`_
    | `Hiroshi Kajino`
    | :venue:`ICML 2019`
    | `grammar, VAE, hypergraph, goal-directed optimization`
    | `Github <https://github.com/ibm-research-tokyo/graph_grammar>`_

`Multi-objective de novo drug design with conditional graph generative model
<https://jcheminf.biomedcentral.com/articles/10.1186/s13321-018-0287-6>`_
    | `Yibo Li, Liangren Zhang, Zhenming Liu`
    | :venue:`Journal of Cheminformatics, 10`
    | `graph neural networks, distribution-learning, auto-regressive, conditional generation, ChEMBL`
    | `Github <https://github.com/kevinid/molecule_generator>`_

`DEFactor: Differentiable Edge Factorization-based Probabilistic Graph Generation
<https://arxiv.org/abs/1811.09766>`_
    | `Rim Assouel, Mohamed Ahmed, Marwin H Segler, Amir Saffari, Yoshua Bengio`
    | :venue:`arXiv 1811`
    | `graph neural networks, auto-regressive, goal-directed optimization, GAN, conditional generation, ZINC`

`Learning Multimodal Graph-to-Graph Translation for Molecular Optimization
<https://arxiv.org/abs/1812.01070>`_
    | `Wengong Jin, Kevin Yang, Regina Barzilay, Tommi Jaakkola`
    | :venue:`ICLR 2019`
    | `graph neural networks, VAE, WGAN, goal-directed optimization, ZINC`
    | `Github <https://github.com/wengong-jin/iclr19-graph2graph>`_

`A Generative Model For Electron Paths
<https://arxiv.org/abs/1805.10970>`_
    | `John Bradshaw, Matt J. Kusner, Brooks Paige, Marwin H. S. Segler, José Miguel Hernández-Lobato`
    | :venue:`ICLR 2019`
    | `graph neural networks, chemical reaction prediction, RL, MDP`
    | `Github <https://github.com/john-bradshaw/electro>`_

`Graph Transformation Policy Network for Chemical Reaction Prediction
<https://arxiv.org/abs/1812.09441>`_
    | `Kien Do, Truyen Tran, Svetha Venkatesh`
    | :venue:`KDD 2019`
    | `graph neural networks, chemical reaction prediction`

`Mol-CycleGAN - a generative model for molecular optimization
<https://arxiv.org/abs/1902.02119>`_
    | `Łukasz Maziarka, Agnieszka Pocha, Jan Kaczmarczyk, Krzysztof Rataj, Michał Warchoł`
    | :venue:`arXiv 1902`
    | `graph neural networks, CycleGAN, goal-directed optimization`

`Molecular geometry prediction using a deep generative graph neural network
<https://arxiv.org/abs/1904.00314>`_
    | `Elman Mansimov, Omar Mahmood, Seokho Kang, Kyunghyun Cho`
    | :venue:`arXiv 1904`
    | `graph neural networks, VAE, molecular conformation generation, energy function, conditional generation, QM9, COD, CSD`
    | `Github <https://github.com/nyu-dl/dl4chem-geometry>`_

`Decoding Molecular Graph Embeddings with Reinforcement Learning
<https://arxiv.org/abs/1904.08915#>`_
    | `Steven Kearnes, Li Li, Patrick Riley`
    | :venue:`arXiv 1904`
    | `graph neural networks, goal-directed optimization, MDP, VAE, QM9`

`Likelihood-Free Inference and Generation of Molecular Graphs
<https://arxiv.org/abs/1905.10310>`_
    | `Sebastian Pölsterl, Christian Wachinger`
    | :venue:`arXiv 1905`
    | `graph neural networks, distribution learning, GAN, multi-graph, gumbel-softmax, QM9`

`GraphNVP: An Invertible Flow Model for Generating Molecular Graphs
<https://arxiv.org/abs/1905.11600>`_
    | `Kaushalya Madhawa, Katushiko Ishiguro, Kosuke Nakago, Motoki Abe`
    | :venue:`arXiv 1905`
    | `graph neural networks, invertible model, flow model, distribution learning, goal-directed optimization, QM9, ZINC`
    | `Github <https://github.com/pfnet-research/graph-nvp>`_

`Scaffold-based molecular design using graph generative model
<https://arxiv.org/abs/1905.13639>`_
    | `Jaechang Lim, Sang-Yeon Hwang, Seungsu Kim, Seokhyun Moon, Woo Youn Kim`
    | :venue:`arXiv 1905`
    | `graph neural networks, scaffold, VAE, conditional generation, goal-directed optimization`

`A Model to Search for Synthesizable Molecules
<https://arxiv.org/abs/1906.05221>`_
    | `John Bradshaw, Brooks Paige, Matt J. Kusner, Marwin H. S. Segler, José Miguel Hernández-Lobato`
    | :venue:`NeurIPS 2019`
    | `graph neural networks, reaction prediction, distribution learning, goal-directed optimization, retrosynthesis`

`Discrete Object Generation with Reversible Inductive Construction
<https://arxiv.org/abs/1907.08268>`_
    | `Ari Seff, Wenda Zhou, Farhan Damani, Abigail Doyle, Ryan P. Adams`
    | :venue:`arXiv 1907`
    | `graph neural networks, distribution learning, Markov kernel, auto-regressive`
    | `Github <https://github.com/PrincetonLIPS/reversible-inductive-construction>`_

`Multi-resolution Autoregressive Graph-to-Graph Translation for Molecules
<https://arxiv.org/abs/1907.11223>`_
    | `Wengong Jin, Regina Barzilay, Tommi Jaakkola`
    | :venue:`arXiv 1907`
    | `graph neural networks, goal-directed optimization, autoregressive, hierarchical, VAE, ZINC`

`Optimization of Molecules via Deep Reinforcement Learning
<https://www.nature.com/articles/s41598-019-47148-x>`_
    | `Zhenpeng Zhou, Steven Kearnes, Li Li, Richard N. Zare, Patrick Riley`
    | :venue:`Scientific Reports 9`
    | `MDP, DQN, learning from scratch, autoregressive, goal-directed optimization`
    | `Github <https://github.com/google-research/google-research/tree/master/mol_dqn>`_
