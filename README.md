# Awesome Machine Learning On Source Code [![Awesome Machine Learning On Source Code](badges/awesome.svg)](https://github.com/src-d/awesome-machine-learning-on-source-code)

![Awesome Machine Learning On Source Code](img/awesome-machine-learning-artwork.png)

A curated list of awesome research papers, datasets and software projects devoted to machine learning *and* source code. Inspired by [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning).

## Contents

- [Digests](#digests)
- [Conferences](#conferences)
- [Competitions](#competitions)
- [Papers](#papers)
    - [Program Synthesis and Induction](#program-synthesis-and-induction)
    - [Source Code Analysis and Language modeling](#source-code-analysis-and-language-modeling)
    - [Neural Network Architectures and Algorithms](#neural-network-architectures-and-algorithms)
    - [Embeddings in Software Engineering](#embeddings-in-software-engineering)
    - [Program Translation](#program-translation)
    - [Code Suggestion and Completion](#code-suggestion-and-completion)
    - [Program Repair and Bug Detection](#program-repair-and-bug-detection)
    - [APIs and Code Mining](#apis-and-code-mining)
    - [Code Optimization](#code-optimization)
    - [Topic Modeling](#topic-modeling)
    - [Sentiment Analysis](#sentiment-analysis)
    - [Code Summarization](#code-summarization)
    - [Clone Detection](#clone-detection)
    - [Differentiable Interpreters](#differentiable-interpreters)
    - [Related research](#related-research)<details><summary>(links require "Related research" spoiler to be open)</summary>
        - [Binary Data Modeling](#binary-data-modeling)
        - [Soft Clustering Using T-mixture Models](#soft-clustering-using-t-mixture-models)
        </details>
- [Posts](#posts)
- [Talks](#talks)
- [Software](#software)
    - [Machine Learning](#machine-learning)
    - [Utilities](#utilities)
- [Datasets](#datasets)
- [Credits](#credits)
- [Contributions](#contributions)
- [License](#license)

## Digests

* [Learning from "Big Code"](http://learnbigcode.github.io)
* [A Survey of Machine Learning for Big Code and Naturalness](https://ml4code.github.io/)

## Conferences

* <img src="badges/origin-academia-blue.svg" alt="origin-academia" align="top"> [2018 IEEE 25th International Conference on Software Analysis, Evolution, and Reengineering (SANER)](https://www.conference-publishing.com/list.php?Event=SANER18MAIN)
* <img src="badges/origin-academia-blue.svg" alt="origin-academia" align="top"> [Machine Learning for Programming](http://ml4p.org/)
* <img src="badges/origin-academia-blue.svg" alt="origin-academia" align="top"> [Workshop on NLP for Software Engineering](https://nl4se.github.io/)
* <img src="badges/origin-industry-green.svg" alt="origin-industry" align="top"> [SysML](http://www.sysml.cc/)
    * [Talks](https://www.youtube.com/channel/UChutDKIa-AYyAmbT45s991g/)
* <img src="badges/origin-academia-blue.svg" alt="origin-academia" align="top"> [Mining Software Repositories](http://www.msrconf.org/)
* <img src="badges/origin-industry-green.svg" alt="origin-industry" align="top"> [AIFORSE](aiforse.org)
* <img src="badges/origin-industry-green.svg" alt="origin-industry" align="top"> [source{d} tech talks](https://talks.sourced.tech/machine-learning-2017/)
    * [Talks](https://www.youtube.com/playlist?list=PL5Ld68ole7j3iQFUSB3fR9122dHCUWXsy)
* <img src="badges/origin-academia-blue.svg" alt="origin-academia" align="top"> [NIPS Neural Abstract Machines and Program Induction workshop](ucmlr.github.io/nampi)
    * [Talks](https://www.youtube.com/playlist?list=PLzTDea_cM27LVPSTdK9RypSyqBHZWPywt)

## Competitions

* [CodRep](https://github.com/KTH/CodRep-competition)

## Papers

#### Program Synthesis and Induction

* <img src="badges/12-pages-beginner-brightgreen.svg" alt="12-pages-beginner" align="top"> [NL2Bash: A Corpus and Semantic Parser for Natural Language Interface to the Linux Operating System](https://arxiv.org/abs/1802.08979v2) - Xi Victoria Lin, Chenglong Wang, Luke Zettlemoyer, Michael D. Ernst, 2018.
* <img src="badges/18-pages-gray.svg" alt="18-pages" align="top"> [Recent Advances in Neural Program Synthesis](https://arxiv.org/abs/1802.02353v1) - Neel Kant, 2018.
* <img src="badges/16-pages-gray.svg" alt="16-pages" align="top"> [Neural Sketch Learning for Conditional Program Generation](https://arxiv.org/abs/1703.05698) - Vijayaraghavan Murali, Letao Qi, Swarat Chaudhuri, Chris Jermaine, 2018.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Neural Program Search: Solving Programming Tasks from Description and Examples](https://arxiv.org/abs/1802.04335v1) - Illia Polosukhin, Alexander Skidanov, 2018.
* <img src="badges/16-pages-gray.svg" alt="16-pages" align="top"> [Neural Program Synthesis with Priority Queue Training](https://arxiv.org/abs/1801.03526v1) - Daniel A. Abolafia, Mohammad Norouzi, Quoc V. Le, 2018.
* <img src="badges/31-pages-gray.svg" alt="31-pages" align="top"> [Towards Synthesizing Complex Programs from Input-Output Examples](https://arxiv.org/abs/1706.01284v3) - Xinyun Chen, Chang Liu, Dawn Song, 2018.
* <img src="badges/13-pages-beginner-brightgreen.svg" alt="13-pages-beginner" align="top"> [SQLNet: Generating Structured Queries From Natural Language Without Reinforcement Learning](https://arxiv.org/abs/1711.04436v1) - Xiaojun Xu, Chang Liu, Dawn Song, 2017.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Learning to Select Examples for Program Synthesis](https://arxiv.org/abs/1711.03243v1) - Yewen Pu, Zachery Miranda, Armando Solar-Lezama, Leslie Pack Kaelbling, 2017.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Neural Program Meta-Induction](https://arxiv.org/abs/1710.04157v1) - Jacob Devlin, Rudy Bunel, Rishabh Singh, Matthew Hausknecht, Pushmeet Kohli, 2017.
* <img src="badges/8-pages-gray.svg" alt="8-pages" align="top"> [Glass-Box Program Synthesis: A Machine Learning Approach](https://arxiv.org/abs/1709.08669v1) - Konstantina Christakopoulou, Adam Tauman Kalai, 2017.
* <img src="badges/14-pages-beginner-brightgreen.svg" alt="14-pages-beginner" align="top"> [Learning to Infer Graphics Programs from Hand-Drawn Images](https://arxiv.org/abs/1707.09627v4) - Kevin Ellis, Daniel Ritchie, Armando Solar-Lezama, Joshua B. Tenenbaum, 2017.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Neural Attribute Machines for Program Generation](https://arxiv.org/abs/1705.09231v2) - Matthew Amodio, Swarat Chaudhuri, Thomas Reps, 2017.
* <img src="badges/11-pages-beginner-brightgreen.svg" alt="11-pages-beginner" align="top"> [Abstract Syntax Networks for Code Generation and Semantic Parsing](https://arxiv.org/abs/1704.07535v1) - Maxim Rabinovich, Mitchell Stern, Dan Klein, 2017.
* <img src="badges/20-pages-gray.svg" alt="20-pages" align="top"> [Making Neural Programming Architectures Generalize via Recursion](https://arxiv.org/pdf/1704.06611v1.pdf) - Jonathon Cai, Richard Shin, Dawn Song, 2017.
* <img src="badges/14-pages-gray.svg" alt="14-pages" align="top"> [A Syntactic Neural Model for General-Purpose Code Generation](https://arxiv.org/abs/1704.01696v1) - Pengcheng Yin, Graham Neubig, 2017.
* <img src="badges/12-pages-beginner-brightgreen.svg" alt="12-pages-beginner" align="top"> [Program Synthesis from Natural Language Using Recurrent Neural Networks](https://homes.cs.washington.edu/~mernst/pubs/nl-command-tr170301.pdf) - Xi Victoria Lin, Chenglong Wang, Deric Pang, Kevin Vu, Luke Zettlemoyer, Michael Ernst, 2017.
* <img src="badges/18-pages-beginner-brightgreen.svg" alt="18-pages-beginner" align="top"> [RobustFill: Neural Program Learning under Noisy I/O](https://arxiv.org/abs/1703.07469v1) - Jacob Devlin, Jonathan Uesato, Surya Bhupatiraju, Rishabh Singh, Abdel-rahman Mohamed, Pushmeet Kohli, 2017.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Lifelong Perceptual Programming By Example](https://openreview.net/pdf?id=HJStZKqel) - Gaunt, Alexander L., Marc Brockschmidt, Nate Kushman, and Daniel Tarlow, 2017.
* <img src="badges/7-pages-gray.svg" alt="7-pages" align="top"> [Neural Programming by Example](https://arxiv.org/abs/1703.04990v1) - Chengxun Shu, Hongyu Zhang, 2017.
* <img src="badges/21-pages-gray.svg" alt="21-pages" align="top"> [DeepCoder: Learning to Write Programs](http://arxiv.org/abs/1611.01989) - Balog, Matej, Alexander L. Gaunt, Marc Brockschmidt, Sebastian Nowozin, and Daniel Tarlow, 2017.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [A Differentiable Approach to Inductive Logic Programming](https://uclmr.github.io/nampi/extended_abstracts/yang.pdf) - Yang, Fan, Zhilin Yang, and William W. Cohen, 2017.
* <img src="badges/12-pages-beginner-brightgreen.svg" alt="12-pages-beginner" align="top"> [Latent Attention For If-Then Program Synthesis](https://arxiv.org/abs/1611.01867v1) - Xinyun Chen, Chang Liu, Richard Shin, Dawn Song, Mingcheng Chen, 2016.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Latent Predictor Networks for Code Generation](https://arxiv.org/abs/1603.06744) - Wang Ling, Edward Grefenstette, Karl Moritz Hermann, Tomáš Kočiský, Andrew Senior, Fumin Wang, Phil Blunsom, 2016.
* <img src="badges/2-pages-gray.svg" alt="2-pages" align="top"> [Meta-Interpretive Learning of Efficient Logic Programs](https://uclmr.github.io/nampi/extended_abstracts/cropper.pdf) - Cropper, Andrew, and Stephen H. Muggleton, 2016.
* <img src="badges/6-pages-gray.svg" alt="6-pages" align="top"> [Neural Symbolic Machines: Learning Semantic Parsers on Freebase with Weak Supervision (Short Version)](http://arxiv.org/abs/1612.01197) - Liang, Chen, Jonathan Berant, Quoc Le, Kenneth D. Forbus, and Ni Lao, 2016.
* <img src="badges/5-pages-gray.svg" alt="5-pages" align="top"> [Programs as Black-Box Explanations](http://arxiv.org/abs/1611.07579) - Singh, Sameer, Marco Tulio Ribeiro, and Carlos Guestrin, 2016.
* <img src="badges/14-pages-gray.svg" alt="14-pages" align="top"> [Structured Generative Models of Natural Source Code](https://arxiv.org/abs/1401.0514) - Chris J. Maddison, Daniel Tarlow, 2014.

#### Source Code Analysis and Language modeling

* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Syntax and Sensibility: Using language models to detect and correct syntax errors](http://softwareprocess.es/pubs/santos2018SANER-syntax.pdf) - Eddie Antonio Santos, Joshua Charles Campbell, Dhvani Patel, Abram Hindle, and José Nelson Amaral, 2018.
* <img src="badges/25-pages-gray.svg" alt="25-pages" align="top"> [code2vec: Learning Distributed Representations of Code](https://arxiv.org/abs/1803.09473v2) - Uri Alon, Meital Zilberstein, Omer Levy, Eran Yahav, 2018.
* <img src="badges/36-pages-gray.svg" alt="36-pages" align="top"> [A Survey of Machine Learning for Big Code and Naturalness](https://arxiv.org/abs/1709.06182v1) - Miltiadis Allamanis, Earl T. Barr, Premkumar Devanbu, Charles Sutton, 2017.
* <img src="badges/16-pages-gray.svg" alt="16-pages" align="top"> [Learning to Represent Programs with Graphs](https://arxiv.org/abs/1711.00740v1) - Miltiadis Allamanis, Marc Brockschmidt, Mahmoud Khademi, 2017.
* <img src="badges/4-pages-gray.svg" alt="4-pages" align="top"> [A deep language model for software code](https://arxiv.org/abs/1608.02715v1) - Hoa Khanh Dam, Truyen Tran, Trang Pham, 2016.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Suggesting Accurate Method and Class Names](http://homepages.inf.ed.ac.uk/csutton/publications/accurate-method-and-class.pdf) - Miltiadis Allamanis, Earl T. Barr, Christian Bird, Charles Sutton, 2015.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Mining Source Code Repositories at Massive Scale using Language Modeling](http://homepages.inf.ed.ac.uk/csutton/publications/msr2013.pdf) - Miltiadis Allamanis, Charles Sutton, 2013.

#### Neural Network Architectures and Algorithms

* <img src="badges/16-pages-gray.svg" alt="16-pages" align="top"> [A General Path-Based Representation for Predicting Program Properties](https://arxiv.org/abs/1803.09544) - Uri Alon, Meital Zilberstein, Omer Levy, Eran Yahav, 2018.
* <img src="badges/4-pages-gray.svg" alt="4-pages" align="top"> [Cross-Language Learning for Program Classification using Bilateral Tree-Based Convolutional Neural Networks](https://arxiv.org/abs/1710.06159v2) - Nghi D. Q. Bui, Lingxiao Jiang, Yijun Yu, 2017.
* <img src="badges/17-pages-gray.svg" alt="17-pages" align="top"> [Syntax-Directed Variational Autoencoder for Structured Data](https://openreview.net/pdf?id=SyqShMZRb) - Hanjun Dai, Yingtao Tian, Bo Dai, Steven Skiena, Le Song, 2018.
* <img src="badges/19-pages-gray.svg" alt="19-pages" align="top"> [Divide and Conquer with Neural Networks](http://arxiv.org/abs/1611.02401) - Nowak, Alex, and Joan Bruna, 2017.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Learning Efficient Algorithms with Hierarchical Attentive Memory](http://arxiv.org/abs/1602.03218) - Andrychowicz, Marcin, and Karol Kurach, 2016.
* <img src="badges/6-pages-gray.svg" alt="6-pages" align="top"> [Learning Operations on a Stack with Neural Turing Machines](http://arxiv.org/abs/1612.00827) - Deleu, Tristan, and Joseph Dureau, 2016.
* <img src="badges/5-pages-gray.svg" alt="5-pages" align="top"> [Probabilistic Neural Programs](http://arxiv.org/abs/1612.00712) - Murray, Kenton W., and Jayant Krishnamurthy, 2016.
* <img src="badges/3-pages-gray.svg" alt="3-pages" align="top"> [Learning Latent Multiscale Structure Using Recurrent Neural Networks](https://uclmr.github.io/nampi/extended_abstracts/chung.pdf) - Chung, Junyoung, Sungjin Ahn, and Yoshua Bengio, 2016.
* <img src="badges/18-pages-gray.svg" alt="18-pages" align="top"> [Neural Programmer: Inducing Latent Programs with Gradient Descent](http://arxiv.org/abs/1511.04834) - Neelakantan, Arvind, Quoc V. Le, and Ilya Sutskever, 2016.
* <img src="badges/13-pages-gray.svg" alt="13-pages" align="top"> [Neural Programmer-Interpreters](http://arxiv.org/abs/1511.06279) - Reed, Scott, and Nando de Freitas, 2016.
* <img src="badges/9-pages-gray.svg" alt="9-pages" align="top"> [Neural GPUs Learn Algorithms](http://arxiv.org/abs/1511.08228) - Kaiser, Łukasz, and Ilya Sutskever, 2016.
* <img src="badges/17-pages-gray.svg" alt="17-pages" align="top"> [Neural Random-Access Machines](https://arxiv.org/abs/1511.06392v3) - Karol Kurach, Marcin Andrychowicz, Ilya Sutskever, 2016.
* <img src="badges/25-pages-gray.svg" alt="25-pages" align="top"> [Learning to Execute](https://arxiv.org/abs/1410.4615v3) - Wojciech Zaremba, Ilya Sutskever, 2015.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Inferring Algorithmic Patterns with Stack-Augmented Recurrent Nets](http://arxiv.org/abs/1503.01007) - Joulin, Armand, and Tomas Mikolov, 2015.
* <img src="badges/26-pages-gray.svg" alt="26-pages" align="top"> [Neural Turing Machines](http://arxiv.org/abs/1410.5401) - Graves, Alex, Greg Wayne, and Ivo Danihelka, 2014.
* <img src="badges/15-pages-gray.svg" alt="15-pages" align="top"> [From Machine Learning to Machine Reasoning](http://arxiv.org/abs/1102.1808) - Bottou, Leon, 2011.

#### Embeddings in Software Engineering

* <img src="badges/4-pages-gray.svg" alt="4-pages" align="top"> [Word Embeddings for the Software Engineering Domain](https://github.com/vefstathiou/SO_word2vec/blob/master/MSR18-w2v.pdf) - Vasiliki Efstathiou, Christos Chatzilenas, Diomidis Spinellis, 2018.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Document Distance Estimation via Code Graph Embedding](https://www.researchgate.net/publication/320074701_Document_Distance_Estimation_via_Code_Graph_Embedding) - Zeqi Lin, Junfeng Zhao, Yanzhen Zou, Bing Xie, 2017.
* <img src="badges/3-pages-gray.svg" alt="3-pages" align="top"> [Combining Word2Vec with revised vector space model for better code retrieval](https://www.researchgate.net/publication/318123700_Combining_Word2Vec_with_Revised_Vector_Space_Model_for_Better_Code_Retrieval) - Thanh Van Nguyen, Anh Tuan Nguyen, Hung Dang Phan, Trong Duc Nguyen, Tien N. Nguyen, 2017.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [From word embeddings to document similarities for improved information retrieval in software engineering](https://www.researchgate.net/publication/296526040_From_Word_Embeddings_To_Document_Similarities_for_Improved_Information_Retrieval_in_Software_Engineering) - Xin Ye, Hui Shen, Xiao Ma, Razvan Bunescu, Chang Liu, 2016.
* <img src="badges/3-pages-gray.svg" alt="3-pages" align="top"> [Mapping API Elements for Code Migration with Vector Representation](https://dl.acm.org/citation.cfm?id=2892661) - Trong Duc Nguyen, Anh Tuan Nguyen, Tien N. Nguyen, 2016.

#### Program Translation

* <img src="badges/14-pages-gray.svg" alt="14-pages" align="top"> [Tree-to-tree Neural Networks for Program Translation](https://arxiv.org/abs/1802.03691v1) - Xinyun Chen, Chang Liu, Dawn Song, 2018.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Code Attention: Translating Code to Comments by Exploiting Domain Features](https://arxiv.org/abs/1709.07642v2) - Wenhao Zheng, Hong-Yu Zhou, Ming Li, Jianxin Wu, 2017.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Automatically Generating Commit Messages from Diffs using Neural Machine Translation](https://arxiv.org/abs/1708.09492v1) - Siyuan Jiang, Ameer Armaly, Collin McMillan, 2017.
* <img src="badges/5-pages-gray.svg" alt="5-pages" align="top"> [A Parallel Corpus of Python Functions and Documentation Strings for Automated Code Documentation and Code Generation](https://arxiv.org/abs/1707.02275v1) - Antonio Valerio Miceli Barone, Rico Sennrich, 2017.
* <img src="badges/6-pages-gray.svg" alt="6-pages" align="top"> [A Neural Architecture for Generating Natural Language Descriptions from Source Code Changes](https://arxiv.org/abs/1704.04856v1) - Pablo Loyola, Edison Marrese-Taylor, Yutaka Matsuo, 2017.

#### Code Suggestion and Completion

* <img src="badges/8-pages-gray.svg" alt="8-pages" align="top"> [Code Completion with Neural Attention and Pointer Networks](https://arxiv.org/abs/1711.09573v1) - Jian Li, Yue Wang, Irwin King, Michael R. Lyu, 2017.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Learning Python Code Suggestion with a Sparse Pointer Network](https://arxiv.org/abs/1611.08307) - Avishkar Bhoopchand, Tim Rocktäschel, Earl Barr, Sebastian Riedel, 2016.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Code Completion with Statistical Language Models](http://www.srl.inf.ethz.ch/papers/pldi14-statistical.pdf) - Veselin Raychev, Martin Vechev, Eran Yahav, 2014.

#### Program Repair and Bug Detection

* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Dynamic Neural Program Embedding for Program Repair](https://arxiv.org/abs/1711.07163v2) - Ke Wang, Rishabh Singh, Zhendong Su, 2018.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [To Type or Not to Type: Quantifying Detectable Bugs in JavaScript](http://earlbarr.com/publications/typestudy.pdf) - Zheng Gao, Christian Bird, Earl Barr, 2017.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Semantic Code Repair using Neuro-Symbolic Transformation Networks](https://arxiv.org/abs/1710.11054v1) - Jacob Devlin, Jonathan Uesato, Rishabh Singh, Pushmeet Kohli, 2017.
* <img src="badges/6-pages-gray.svg" alt="6-pages" align="top"> [Automated Identification of Security Issues from Commit Messages and Bug Reports](http://asankhaya.github.io/pdf/automated-identification-of-security-issues-from-commit-messages-and-bug-reports.pdf) - Yaqin Zhou and Asankhaya Sharma, 2017.
* <img src="badges/31-pages-gray.svg" alt="31-pages" align="top"> [SmartPaste: Learning to Adapt Source Code](https://arxiv.org/abs/1705.07867) - Miltiadis Allamanis, Marc Brockschmidt, 2017.
* <img src="badges/7-pages-gray.svg" alt="7-pages" align="top"> [End-to-End Prediction of Buffer Overruns from Raw Source Code via Neural Memory Networks](https://arxiv.org/abs/1703.02458v1) - Min-je Choi, Sehun Jeong, Hakjoo Oh, Jaegul Choo, 2017.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Tailored Mutants Fit Bugs Better](https://arxiv.org/abs/1611.02516) - Miltiadis Allamanis, Earl T. Barr, René Just, Charles Sutton, 2016.

#### APIs and Code Mining

* <img src="badges/7-pages-gray.svg" alt="7-pages" align="top"> [DeepAM: Migrate APIs with Multi-modal Sequence to Sequence Learning](https://arxiv.org/abs/1704.07734v1) - Xiaodong Gu, Hongyu Zhang, Dongmei Zhang, Sunghun Kim, 2017.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Deep API Learning](https://arxiv.org/abs/1605.08535v3) - Xiaodong Gu, Hongyu Zhang, Dongmei Zhang, Sunghun Kim, 2017.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [API usage pattern recommendation for software development](http://www.sciencedirect.com/science/article/pii/S0164121216301200) - Haoran Niu, Iman Keivanloo, Ying Zou, 2017.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Exploring API Embedding for API Usages and Applications](http://home.eng.iastate.edu/~trong/projects/jv2cs/) - Nguyen, Nguyen, Phan and Nguyen, 2017.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Parameter-Free Probabilistic API Mining across GitHub](http://homepages.inf.ed.ac.uk/csutton/publications/fse2016.pdf) - Jaroslav Fowkes, Charles Sutton, 2016.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [A Subsequence Interleaving Model for Sequential Pattern Mining](http://homepages.inf.ed.ac.uk/csutton/publications/kdd2016-subsequence-interleaving.pdf) - Jaroslav Fowkes, Charles Sutton, 2016.
* <img src="badges/4-pages-gray.svg" alt="4-pages" align="top"> [Lean GHTorrent: GitHub data on demand](https://bvasiles.github.io/papers/lean-ghtorrent.pdf) - Georgios Gousios, Bogdan Vasilescu, Alexander Serebrenik, Andy Zaidman, 2014.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Mining idioms from source code](http://homepages.inf.ed.ac.uk/csutton/publications/idioms.pdf) - Miltiadis Allamanis, Charles Sutton, 2014.
* <img src="badges/4-pages-gray.svg" alt="4-pages" align="top"> [The GHTorent Dataset and Tool Suite](http://www.gousios.gr/pub/ghtorrent-dataset-toolsuite.pdf) - Georgios Gousios, 2013.

#### Code Optimization

* <img src="badges/27-pages-gray.svg" alt="27-pages" align="top"> [The Case for Learned Index Structures](https://arxiv.org/abs/1712.01208v2) - Tim Kraska, Alex Beutel, Ed H. Chi, Jeffrey Dean, Neoklis Polyzotis, 2017.
* <img src="badges/14-pages-gray.svg" alt="14-pages" align="top"> [Learning to superoptimize programs](https://arxiv.org/abs/1611.01787v3) - Rudy Bunel, Alban Desmaison, M. Pawan Kumar, Philip H.S. Torr, Pushmeet Kohlim 2017.
* <img src="badges/18-pages-gray.svg" alt="18-pages" align="top"> [Neural Nets Can Learn Function Type Signatures From Binaries](https://www.usenix.org/system/files/conference/usenixsecurity17/sec17-chua.pdf) - Zheng Leong Chua, Shiqi Shen, Prateek Saxena, and Zhenkai Liang, 2017.
* <img src="badges/25-pages-gray.svg" alt="25-pages" align="top"> [Adaptive Neural Compilation](https://arxiv.org/abs/1605.07969v2) - Rudy Bunel, Alban Desmaison, Pushmeet Kohli, Philip H.S. Torr, M. Pawan Kumar, 2016.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Learning to Superoptimize Programs - Workshop Version](http://arxiv.org/abs/1612.01094) - Bunel, Rudy, Alban Desmaison, M. Pawan Kumar, Philip H. S. Torr, and Pushmeet Kohli, 2016.

#### Topic Modeling

* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Topic modeling of public repositories at scale using names in source code](https://arxiv.org/abs/1704.00135) - Vadim Markovtsev, Eiso Kant, 2017.
* <img src="badges/4-pages-gray.svg" alt="4-pages" align="top"> [Why, When, and What: Analyzing Stack Overflow Questions by Topic, Type, and Code](http://homepages.inf.ed.ac.uk/csutton/publications/msrCh2013.pdf) - Miltiadis Allamanis, Charles Sutton, 2013.
* <img src="badges/30-pages-gray.svg" alt="30-pages" align="top"> [Semantic clustering: Identifying topics in source code](https://pdfs.semanticscholar.org/c9ba/722322912419e59ea251c22b437d251f1644.pdf) - Adrian Kuhn, Stéphane Ducasse, Tudor Girba, 2007.

#### Sentiment Analysis

* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [A Benchmark Study on Sentiment Analysis for Software Engineering Research](https://arxiv.org/pdf/1803.06525.pdf) - Nicole Novielli, Daniela Girardi, Filippo Lanubile, 2018.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Sentiment Analysis for Software Engineering: How Far Can We Go?](http://www.inf.usi.ch/phd/lin/downloads/Lin2018a.pdf) - Bin Lin, Fiorella Zampetti, Gabriele Bavota, Massimiliano Di Penta, Michele Lanza, Rocco Oliveto, 2018.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Leveraging Automated Sentiment Analysis in Software Engineering](http://cs.uno.edu/~zibran/resources/MyPapers/SentiStrengthSE_2017.pdf) - Md Rakibul Islam, Minhaz F. Zibran, 2017.
* <img src="badges/27-pages-gray.svg" alt="27-pages" align="top"> [Sentiment Polarity Detection for Software Development](https://arxiv.org/pdf/1709.02984.pdf) - Fabio Calefato, Filippo Lanubile, Federico Maiorano, Nicole Novielli, 2017.
* <img src="badges/6-pages-gray.svg" alt="6-pages" align="top"> [SentiCR: A Customized Sentiment Analysis Tool for Code Review Interactions](https://drive.google.com/file/d/0Byog0ILN8S1haGxpT3hvSzZxdms/view) - Toufique Ahmed, Amiangshu Bosu, Anindya Iqbal, Shahram Rahimi, 2017.

#### Code Summarization

* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [A Convolutional Attention Network for Extreme Summarization of Source Code](http://arxiv.org/abs/1602.03001) - Miltiadis Allamanis, Hao Peng, Charles Sutton, 2016.
* <img src="badges/4-pages-gray.svg" alt="4-pages" align="top"> [TASSAL: Autofolding for Source Code Summarization](http://homepages.inf.ed.ac.uk/csutton/publications/icse2016-demo.pdf) - Jaroslav Fowkes, Pankajan Chanthirasegaran, Razvan Ranca, Miltiadis Allamanis, Mirella Lapata, Charles Sutton, 2016.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Summarizing Source Code using a Neural Attention Model](https://github.com/sriniiyer/codenn/blob/master/summarizing_source_code.pdf) - Srinivasan Iyer, Ioannis Konstas, Alvin Cheung, Luke Zettlemoyer, 2016.

#### Clone Detection

* <img src="badges/28-pages-gray.svg" alt="28-pages" align="top"> [DéjàVu: a map of code duplicates on GitHub](http://janvitek.org/pubs/oopsla17b.pdf) - Cristina V. Lopes, Petr Maj, Pedro Martins, Vaibhav Saini, Di Yang, Jakub Zitny, Hitesh Sajnani, Jan Vitek, 2017.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [Some from Here, Some from There: Cross-project Code Reuse in GitHub](http://web.cs.ucdavis.edu/~filkov/papers/clones.pdf) - Mohammad Gharehyazie, Baishakhi Ray, Vladimir Filkov, 2017.
* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [Deep Learning Code Fragments for Code Clone Detection](http://www.cs.wm.edu/~denys/pubs/ASE'16-DeepLearningClones.pdf) - Martin White, Michele Tufano, Christopher Vendome, and Denys Poshyvanyk, 2016.
* <img src="badges/11-pages-gray.svg" alt="11-pages" align="top"> [A study of repetitiveness of code changes in software evolution](https://lib.dr.iastate.edu/cgi/viewcontent.cgi?referer=https://scholar.google.com/&httpsredir=1&article=1016&context=cs_conf) - HA Nguyen, AT Nguyen, TT Nguyen, TN Nguyen, H Rajan, 2013.

#### Differentiable Interpreters

* <img src="badges/12-pages-gray.svg" alt="12-pages" align="top"> [DDRprog: A CLEVR Differentiable Dynamic Reasoning Programmer](https://arxiv.org/abs/1803.11361v1) - Joseph Suarez, Justin Johnson, Fei-Fei Li, 2018.
* <img src="badges/16-pages-gray.svg" alt="16-pages" align="top"> [Improving the Universality and Learnability of Neural Programmer-Interpreters with Combinator Abstraction](https://arxiv.org/abs/1802.02696v1) - Da Xiao, Jo-Yu Liao, Xingyuan Yuan, 2018.
* <img src="badges/10-pages-gray.svg" alt="10-pages" align="top"> [Differentiable Programs with Neural Libraries](https://arxiv.org/abs/1611.02109v2) - Alexander L. Gaunt, Marc Brockschmidt, Nate Kushman, Daniel Tarlow, 2017.
* <img src="badges/15-pages-gray.svg" alt="15-pages" align="top"> [Differentiable Functional Program Interpreters](https://arxiv.org/abs/1611.01988v2) - John K. Feser, Marc Brockschmidt, Alexander L. Gaunt, Daniel Tarlow, 2017.
* <img src="badges/18-pages-gray.svg" alt="18-pages" align="top"> [Programming with a Differentiable Forth Interpreter](http://arxiv.org/abs/1605.06640) - Bošnjak, Matko, Tim Rocktäschel, Jason Naradowsky, and Sebastian Riedel, 2017.
* <img src="badges/15-pages-gray.svg" alt="15-pages" align="top"> [Neural Functional Programming](http://arxiv.org/abs/1611.01988) - Feser, John K., Marc Brockschmidt, Alexander L. Gaunt, and Daniel Tarlow, 2017.
* <img src="badges/7-pages-gray.svg" alt="7-pages" align="top"> [TerpreT: A Probabilistic Programming Language for Program Induction](http://arxiv.org/abs/1612.00817) - Gaunt, Alexander L., Marc Brockschmidt, Rishabh Singh, Nate Kushman, Pushmeet Kohli, Jonathan Taylor, and Daniel Tarlow, 2016.


<a name="related-research"></a>
<details>
<summary>Related research</summary>

#### Binary Data Modeling

* [Clustering Binary Data with Bernoulli Mixture Models](http://nsgrantham.com/documents/clustering-binary-data.pdf) - Neal S. Grantham
* [A Family of Blockwise One-Factor Distributions for Modelling High-Dimensional Binary Data](https://arxiv.org/pdf/1511.01343.pdf) - Matthieu Marbac and Mohammed Sedki
* [BayesBinMix: an R Package for Model Based Clustering of Multivariate Binary Data](https://arxiv.org/pdf/1609.06960.pdf) - Panagiotis Papastamoulis and Magnus Rattray

#### Soft Clustering Using T-mixture Models

* [Robust mixture modelling using the t distribution](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.218.7334&rep=rep1&type=pdf) - D. PEEL and G. J. MCLACHLAN
* [Robust mixture modeling using the skew t distribution](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.1030.9865&rep=rep1&type=pdf) - Tsung I. Lin, Jack C. Lee and Wan J. Hsieh
</details>

## Posts

* [Learning from Source Code](https://www.microsoft.com/en-us/research/blog/learning-source-code/)
* [Training a Model to Summarize Github Issues](https://towardsdatascience.com/how-to-create-data-products-that-are-magical-using-sequence-to-sequence-models-703f86a231f8)
* [Sequence Intent Classification Using Hierarchical Attention Networks](https://www.microsoft.com/developerblog/2018/03/06/sequence-intent-classification/)
* [Syntax-Directed Variational Autoencoder for Structured Data](https://mlatgt.blog/2018/02/08/syntax-directed-variational-autoencoder-for-structured-data/)
* [Weighted MinHash on GPU helps to find duplicate GitHub repositories.](https://blog.sourced.tech//post/minhashcuda/)
* [Source Code Identifier Embeddings](https://blog.sourced.tech/post/id2vec/)
* [Using recurrent neural networks to predict next tokens in the java solutions](http://near.ai/articles/2017-06-01-Code-Completion-Demo/)
* [The half-life of code & the ship of Theseus](https://erikbern.com/2016/12/05/the-half-life-of-code.html)
* [The eigenvector of "Why we moved from language X to language Y"](https://erikbern.com/2017/03/15/the-eigenvector-of-why-we-moved-from-language-x-to-language-y.html)
* [Analyzing Github, How Developers Change Programming Languages Over Time](https://blog.sourced.tech/post/language_migrations/)
* [Topic Modeling of GitHub Repositories](https://blog.sourced.tech//post/github_topic_modeling/)

## Talks

* [Machine Learning on Source Code](http://vmarkovtsev.github.io/pydays-2018-vienna/)
* [Similarity of GitHub Repositories by Source Code Identifiers](http://vmarkovtsev.github.io/techtalks-2017-moscow/)
* [Using deep RNN to model source code](http://vmarkovtsev.github.io/re-work-2016-london/)
* [Source code abstracts classification using CNN (1)](http://vmarkovtsev.github.io/re-work-2016-berlin/)
* [Source code abstracts classification using CNN (2)](http://vmarkovtsev.github.io/data-natives-2016/)
* [Source code abstracts classification using CNN (3)](http://vmarkovtsev.github.io/slush-2016/)
* [Embedding the GitHub contribution graph](https://egorbu.github.io/techtalks-2017-moscow)
* [Measuring code sentiment in a Git repository](http://vmarkovtsev.github.io/gophercon-2018-moscow/)

## Software

#### Machine Learning

* [Differentiable Neural Computer (DNC)](https://github.com/deepmind/dnc) - TensorFlow implementation of the Differentiable Neural Computer.
* [sourced.ml](https://github.com/src-d/ml) - Abstracts feature extraction from source code syntax trees and working with ML models.
* [vecino](https://github.com/src-d/vecino) - Finds similar Git repositories.
* [apollo](https://github.com/src-d/apollo) - Source code deduplication as scale, research.
* [gemini](https://github.com/src-d/gemini) - Source code deduplication as scale, production.
* [enry](https://github.com/src-d/enry) - Insanely fast file based programming language detector.
* [hercules](https://github.com/src-d/hercules) - Git repository mining framework with batteries on top of go-git.
* [Code Neuron](https://github.com/vmarkovtsev/codeneuron) - Recurrent neural network to detect code blocks in natural language text.
* [Naturalize](https://github.com/mast-group/naturalize) - Language agnostic framework for learning coding conventions from a codebase and then expoiting this information for suggesting better identifier names and formatting changes in the code.
* [Extreme Source Code Summarization](https://github.com/mast-group/convolutional-attention ) - Convolutional attention neural network that learns to summarize source code into a short method name-like summary by just looking at the source code tokens.
* [Summarizing Source Code using a Neural Attention Model](https://github.com/sriniiyer/codenn) - CODE-NN, uses LSTM networks with attention to produce sentences that describe C# code snippets and SQL queries from StackOverflow. Torch over C#/SQL
* [Probabilistic API Miner](https://github.com/mast-group/api-mining) - Near parameter-free probabilistic algorithm for mining the most interesting API patterns from a list of API call sequences.
* [Interesting Sequence Miner](https://github.com/mast-group/sequence-mining) - Novel algorithm that mines the most interesting sequences under a probabilistic model. It is able to efficiently infer interesting sequences directly from the database.
* [TASSAL](https://github.com/mast-group/tassal) - Tool for the automatic summarization of source code using autofolding. Autofolding automatically creates a summary of a source code file by folding non-essential code and comment blocks.
* [JNice2Predict](http://www.nice2predict.org/) - Efficient and scalable open-source framework for structured prediction, enabling one to build new statistical engines more quickly.
* [Clone Digger](http://clonedigger.sourceforge.net/download.html) - clone detection for Python and Java.

#### Utilities

* [go-git](https://github.com/src-d/go-git) - Highly extensible Git implementation in pure Go which is friendly to data mining.
* [bblfsh](https://github.com/bblfsh) - Self-hosted server for source code parsing.
* [engine](https://github.com/src-d/engine) - Scalable and distributed data retrieval pipeline for source code.
* [minhashcuda](https://github.com/src-d/minhashcuda) - Weighted MinHash implementation on CUDA to efficiently find duplicates.
* [kmcuda](https://github.com/src-d/kmcuda) - k-means on CUDA to cluster and to search for nearest neighbors in dense space.
* [wmd-relax](https://github.com/src-d/wmd-relax) - Python package which finds nearest neighbors at Word Mover's Distance.

#### Datasets

* [Public Git Archive](https://github.com/src-d/datasets/tree/master/PublicGitArchive) - 3 TB of Git repositories from GitHub.
* [StackOverflow Question-Code Dataset](https://github.com/LittleYUYU/StackOverflow-Question-Code-Dataset) - ~148K Python and ~120K SQL question-code pairs mined from StackOverflow.
* [GitHub Issue Titles and Descriptions for NLP Analysis](https://www.kaggle.com/davidshinn/github-issues/) - ~8 million GitHub issue titles and descriptions from 2017.
* [GitHub repositories - languages distribution](https://data.world/source-d/github-repositories-languages-distribution) - Programming languages distribution in 14,000,000 repositories on GitHub (October 2016).
* [452M commits on GitHub](https://data.world/vmarkovtsev/452-m-commits-on-github) - ≈ 452M commits' metadata from 16M repositories on GitHub (October 2016).
* [GitHub readme files](https://data.world/vmarkovtsev/github-readme-files) - Readme files of all GitHub repositories (16M) (October 2016).
* [from language X to Y](https://data.world/vmarkovtsev/from-language-x-to-y) - Cache file Erik Bernhardsson collected for his awesome blog post.
* [GitHub word2vec 120k](https://data.world/vmarkovtsev/github-word-2-vec-120-k) - Sequences of identifiers extracted from top starred 120,000 GitHub repositories.
* [GitHub Source Code Names](https://data.world/vmarkovtsev/github-source-code-names) - Names in source code extracted from 13M GitHub repositories, not people.
* [GitHub duplicate repositories](https://data.world/vmarkovtsev/github-duplicate-repositories) - GitHub repositories not marked as forks but very similar to each other.
* [GitHub lng keyword frequencies](https://data.world/vmarkovtsev/github-lng-keyword-frequencies) - Programming language keyword frequency extracted from 16M GitHub repositories.
* [GitHub Java Corpus](http://groups.inf.ed.ac.uk/cup/javaGithub/ ) - GitHub Java corpus is a set of Java projects collected from GitHub that we have used in a number of our publications. The corpus consists of 14,785 projects and 352,312,696 LOC.
* [150k Python Dataset](http://www.srl.inf.ethz.ch/py150.php) - Dataset consisting of 150,000 Python ASTs.
* [150k JavaScript Dataset](http://www.srl.inf.ethz.ch/js150.php) - Dataset consisting of 150,000 JavaScript files and their parsed ASTs.
* [card2code](https://github.com/deepmind/card2code) - This dataset contains the language to code datasets described in the paper [Latent Predictor Networks for Code Generation](https://arxiv.org/abs/1603.06744).
* [NL2Bash](https://github.com/TellinaTool/nl2bash) - This dataset contains a set of ~10,000 bash one-liners collected from websites such as StackOverflow and their English descriptions written by Bash programmers, as described in the [paper](https://arxiv.org/abs/1802.08979).

## Credits

* A lot of references and articles were taken from [mast-group](https://mast-group.github.io/)

## Contributions

See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[![License: CC BY-SA 4.0](badges/License-CC-BY--SA-4.0-lightgrey.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
