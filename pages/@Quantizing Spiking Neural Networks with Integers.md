tags:: [[Local Learning]], [[Memory Efficiency]], [[Quantization]], [[Quantized Learning]], [[Spiking Neural Networks]], [[Surrogate Gradient]]
date:: [[Jul 28th, 2020]]
publisher:: Association for Computing Machinery
place:: "New York, NY, USA"
series:: ICONS 2020
proceedings-title:: International Conference on Neuromorphic Systems 2020
isbn:: 978-1-4503-8851-1
doi:: 10.1145/3407197.3407203
title:: @Quantizing Spiking Neural Networks with Integers
pages:: 1–8
item-type:: [[conferencePaper]]
access-date:: 2024-02-19
original-title:: Quantizing Spiking Neural Networks with Integers
url:: https://dl.acm.org/doi/10.1145/3407197.3407203
authors:: [[Clemens JS Schaefer]], [[Siddharth Joshi]]
library-catalog:: ACM Digital Library
links:: [Local library](zotero://select/library/items/GA6M455J), [Web library](https://www.zotero.org/users/8224007/items/GA6M455J)

- [[Abstract]]
	- Spiking neural networks (SNNs) are a promising approach to developing autonomous agents that continuously adapt to their environment. Developing low-power SNNs that can be implemented on a digital platform is a critical step to the realization of such agents. One of the most important methods of implementing low-power SNNs requires operating at reduced precision. While traditional computer vision has seen a lot of research examining the trade-offs between precision and model performance, such trade-offs are underexamined for contemporary SNNs. This paper studies the trade-offs associated with learning-performance and the quantization of neural dynamics, weights and learning components in SNNs. Our results show that SNNs trained using only integer fixed-point representations can still retain their accuracy while occupying dramatically lower memory footprints and using only energy-efficient fixed-point arithmetic. We show that the memory usage of SNNs trained with reduced precision weights, errors, gradients and neural dynamics can be downsized by 73.78% at the cost of 1.04% test error increase on the DVS gesture data set.
- [[Atachments]]
	- [schaefer_2020_quantizing spiking neural networks with integers.pdf](zotero://select/library/items/SWMPUU9K) {{zotero-linked-file "Schaefer/schaefer_2020_quantizing spiking neural networks with integers.pdf"}}