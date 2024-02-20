tags:: [[Computer Science - Hardware Architecture]], [[Computer Science - Machine Learning]], [[Computer Science - Neural and Evolutionary Computing]]
date:: [[Jul 18th, 2021]]
proceedings-title:: 2021 International Joint Conference on Neural Networks (IJCNN)
extra:: arXiv:2107.01807 [cs]
doi:: 10.1109/IJCNN52387.2021.9534087
title:: @Q-SpiNN: A Framework for Quantizing Spiking Neural Networks
pages:: 1-8
item-type:: [[conferencePaper]]
access-date:: 2024-02-13T15:50:34Z
original-title:: Q-SpiNN: A Framework for Quantizing Spiking Neural Networks
url:: http://arxiv.org/abs/2107.01807
short-title:: Q-SpiNN
authors:: [[Rachmad Vidya Wicaksana Putra]], [[Muhammad Shafique]]
library-catalog:: arXiv.org
links:: [Local library](zotero://select/library/items/JWS79RAZ), [Web library](https://www.zotero.org/users/8224007/items/JWS79RAZ)

- [[Abstract]]
	- A prominent technique for reducing the memory footprint of Spiking Neural Networks (SNNs) without decreasing the accuracy significantly is quantization. However, the state-of-the-art only focus on employing the weight quantization directly from a specific quantization scheme, i.e., either the post-training quantization (PTQ) or the in-training quantization (ITQ), and do not consider (1) quantizing other SNN parameters (e.g., neuron membrane potential), (2) exploring different combinations of quantization approaches (i.e., quantization schemes, precision levels, and rounding schemes), and (3) selecting the SNN model with a good memory-accuracy trade-off at the end. Therefore, the memory saving offered by these state-of-the-art to meet the targeted accuracy is limited, thereby hindering processing SNNs on the resource-constrained systems (e.g., the IoT-Edge devices). Towards this, we propose Q-SpiNN, a novel quantization framework for memory-efficient SNNs. The key mechanisms of the Q-SpiNN are: (1) employing quantization for different SNN parameters based on their significance to the accuracy, (2) exploring different combinations of quantization schemes, precision levels, and rounding schemes to find efficient SNN model candidates, and (3) developing an algorithm that quantifies the benefit of the memory-accuracy trade-off obtained by the candidates, and selects the Pareto-optimal one. The experimental results show that, for the unsupervised network, the Q-SpiNN reduces the memory footprint by ca. 4x, while maintaining the accuracy within 1% from the baseline on the MNIST dataset. For the supervised network, the Q-SpiNN reduces the memory by ca. 2x, while keeping the accuracy within 2% from the baseline on the DVS-Gesture dataset.
- [[Atachments]]
	- [putra_2021_q-spinn.pdf](zotero://select/library/items/8UDQN25Q) {{zotero-linked-file "Putra/putra_2021_q-spinn.pdf"}}