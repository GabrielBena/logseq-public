tags:: [[Computer Science - Computation and Language]], [[Computer Science - Machine Learning]]
date:: [[Mar 1st, 2022]]
extra:: arXiv: 2202.13914
title:: @Combining Modular Skills in Multitask Learning
item-type:: [[journalArticle]]
access-date:: 2022-06-07T14:52:16Z
original-title:: Combining Modular Skills in Multitask Learning
url:: http://arxiv.org/abs/2202.13914
publication-title:: arXiv:2202.13914 [cs]
authors:: [[Edoardo M. Ponti]], [[Alessandro Sordoni]], [[Yoshua Bengio]], [[Siva Reddy]]
library-catalog:: arXiv.org
links:: [Local library](zotero://select/library/items/ETKR62Q2), [Web library](https://www.zotero.org/users/8224007/items/ETKR62Q2)

- [[Abstract]]
	- A modular design encourages neural models to disentangle and recombine different facets of knowledge to generalise more systematically to new tasks. In this work, we assume that each task is associated with a subset of latent discrete skills from a (potentially small) inventory. In turn, skills correspond to parameter-efficient (sparse / low-rank) model parameterisations. By jointly learning these and a task-skill allocation matrix, the network for each task is instantiated as the average of the parameters of active skills. To favour non-trivial soft partitions of skills across tasks, we experiment with a series of inductive biases, such as an Indian Buffet Process prior and a two-speed learning rate. We evaluate our latent-skill model on two main settings: 1) multitask reinforcement learning for grounded instruction following on 8 levels of the BabyAI platform; and 2) few-shot adaptation of pre-trained text-to-text generative models on CrossFit, a benchmark comprising 160 NLP tasks. We find that the modular design of a network significantly increases sample efficiency in reinforcement learning and few-shot generalisation in supervised learning, compared to baselines with fully shared, task-specific, or conditionally generated parameters where knowledge is entangled across tasks. In addition, we show how discrete skills help interpretability, as they yield an explicit hierarchy of tasks.
- [[Atachments]]
	- [ponti_2022_combining_modular_skills_in_multitask_learning.pdf](zotero://select/library/items/8V3AM6WD) {{zotero-linked-file "Ponti/ponti_2022_combining_modular_skills_in_multitask_learning.pdf"}}
	- [arXiv.org Snapshot](https://arxiv.org/abs/2202.13914) {{zotero-imported-file 5LVFLB6M, "2202.html"}}