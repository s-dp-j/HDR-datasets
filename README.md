# HDR Dataset

This repository provides the processed datasets used in the experiments of the paper:

**An Explicit-Implicit Feature Hybrid Developer Recommendation Algorithm Based on Implicit Feature Enhancement in the Bidding Mode**

Recently, developer recommendations on Crowd-sourcing Software Development (CSD) platforms have gained more and more attention. Generally, CSD includes the competition mode and bidding mode. Since one task can only rate one developer, the sparsity problem in the bidding mode is severer, which results in unsatisfactory performance. We note that, while we lack numerical ratings information, we have more information on developers' registration for tasks, i.e., bidding information. Developers can choose the suitable tasks for registration based on their experience, and these tasks can also reflect the developers' ability. In this paper, to alleviate the severe data sparsity, we propose to augment the implicit feature representation by using the binary empirical data expressed in the form of bidding/not bidding. We utilize a multi-task feature learning approach for joint modeling of numerical ratings and bidding/not bidding, using a neural network to align the latent feature space and learn the dependency effects between the two data. Besides, the platform also has descriptive information of tasks and developers. Based on four different heterogeneous data, we propose a hybrid developer recommendation algorithm. Furthermore, our model can alleviate the developer cold-start problem by learning implicit representations from explicit features. Experimental results show that our model outperforms the state-of-the-art methods in different metrics. 

The datasets are collected from real-world crowdsourcing software development platforms and are used to evaluate developer recommendation under the bidding mode. The data contain heterogeneous information from tasks and developers, including task descriptions, developer profiles, bidding interactions, and rating feedback.

## Dataset Overview

the Zhubajie dataset contains 27,407 tasks, 5,578 developers, and 115,068 bidding interactions. The Topcoder dataset contains 57,596 tasks, 11,562 developers, and 76,464 bidding interactions, while the Freelancer dataset contains 9,193 tasks and 5,037 developers. These platforms differ in language, data scale, task characteristics, rating distributions, and bidding behaviors, providing heterogeneous environments for evaluating the cross-platform generalizability of HDR.

