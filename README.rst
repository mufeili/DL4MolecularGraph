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

Property Prediction
-------------------

`MoleculeNet: A Benchmark for Molecular Machine Learning
<https://arxiv.org/abs/1703.00564>`_
    | `Zhenqin Wu, Bharath Ramsundar, Evan N. Feinberg, Joseph Gomes, Caleb Geniesse, Aneesh S. Pappu, Karl Leswing, Vijay Pande`
    | :venue:`Journal of Chemical Sciences, 2018, 9`
    | `public datasets, evaluation metrics, baseline results, quantum mechanics, physical chemistry, biophysics, physiology`
    | `Website <http://moleculenet.ai/>`_

`Alchemy: A Quantum Chemistry Dataset for Benchmarking AI Models
<https://arxiv.org/abs/1906.09427>`_
    | `Guangyong Chen, Pengfei Chen, Chang-Yu Hsieh, Chee-Kong Lee, Benben Liao, Renjie Liao, Weiwen Liu, Jiezhong Qiu, Qiming Sun, Jie Tang, Richard Zemel, Shengyu Zhang`
    | :venue:`arXiv 1906`
    | `public datasets, baseline results, quantum mechanics`
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

Property Prediction
===================

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

`Convolutional Embedding of Attributed Molecular Graphs for Physical Property Prediction
<https://pubs.acs.org/doi/10.1021/acs.jcim.6b00601>`_
    | `Connor W. Coley, Regina Barzilay, William H. Green, Tommi S. Jaakkola, Klavs F. Jensen`
    | :venue:`Journal of Chemical Information and Modeling, 2017, 57, 8`
    | `graph neural networks`
    | `Github <https://github.com/connorcoley/conv_qsar_fast>`_

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
