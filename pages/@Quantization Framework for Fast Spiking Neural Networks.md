date:: 2022
issn:: 1662-453X
title:: @Quantization Framework for Fast Spiking Neural Networks
volume:: 16
item-type:: [[journalArticle]]
access-date:: 2024-02-13T15:35:34Z
original-title:: Quantization Framework for Fast Spiking Neural Networks
url:: https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2022.918793
publication-title:: Frontiers in Neuroscience
authors:: [[Chen Li]], [[Lei Ma]], [[Steve Furber]]
library-catalog:: Frontiers
links:: [Local library](zotero://select/library/items/PKPBL4PU), [Web library](https://www.zotero.org/users/8224007/items/PKPBL4PU)

- [[Abstract]]
	- Compared with artificial neural networks (ANNs), spiking neural networks (SNNs) offer additional temporal dynamics with the compromise of lower information transmission rates through the use of spikes. When using an ANN-to-SNN conversion technique there is a direct link between the activation bit precision of the artificial neurons and the time required by the spiking neurons to represent the same bit precision. This implicit link suggests that techniques used to reduce the activation bit precision of ANNs, such as quantization, can help shorten the inference latency of SNNs. However, carrying ANN quantization knowledge over to SNNs is not straightforward, as there are many fundamental differences between them. Here we propose a quantization framework for fast SNNs (QFFS) to overcome these difficulties, providing a method to build SNNs with enhanced latency and reduced loss of accuracy relative to the baseline ANN model. In this framework, we promote the compatibility of ANN information quantization techniques with SNNs, and suppress “occasional noise” to minimize accuracy loss. The resulting SNNs overcome the accuracy degeneration observed previously in SNNs with a limited number of time steps and achieve an accuracy of 70.18% on ImageNet within 8 time steps. This is the first demonstration that SNNs built by ANN-to-SNN conversion can achieve a similar latency to SNNs built by direct training.
- [[Atachments]]
	- [li_2022_quantization framework for fast spiking neural networks.pdf](zotero://select/library/items/753SXDPP) {{zotero-linked-file "Li/li_2022_quantization framework for fast spiking neural networks.pdf"}}