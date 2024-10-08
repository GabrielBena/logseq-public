public:: true

- ## First Meeting
	- ### Question 1: Are structurally modular networks better at solving compositionnal tasks ?
	  collapsed:: true
		- **Questions**
			- Is SM a good *inductive architectural bias* ?
			- At *equal number of parameters*, can modular networks outperfom monolithic ones ?
			- Can we take into account not only pure performance but also *sample efficiency* ?
				- Does this inductive bias allows for faster convergence towards good solutions?
				- Does it lead to faster fine-tuning / adaptation
					- This starts to go in the continual learning domain
		- **Available literature:**
			- [[@Neural Modularity Helps Organisms Evolve to Learn New Skills without Forgetting Old Skills]]
				- Oldie but goodie paper showing how evolved networks (no GD) end up being more modular when cost-minimization is applied, which in turn make them better at retaining knowledge
			- [[@Modular Growth of Hierarchical Networks: Efficient, General, and Robust Curriculum Learning]]
				- Paper showing that a (very) strong architectural bias perfectly suited for a task enables it to learn more tasks without forgetting, compared to monolothic arch trained end-to-end that suffers from forgetting and interferences.
			- [[@Is a Modular Architecture Enough?]]
				- Paper creating a family of task composed of rules to be applied to inputs, and measures the resulting modularity of trained networks and the effect of such modularity on generalization.
				- ((6703fd20-f78a-4c73-962f-ed385ca5e2bf))
			- [[@Combining Modular Skills in Multitask Learning]]
				- Paper showing modular design can lead to better sample efficiency and generalization in RL tasks.
			- [[@Systematic Generalization: What Is Required and Can It Be Learned?]]
				- As said before, this work shows that modularity can indeed improve on generalization abilities but is hardly found end-to-end when not explicitely regularized
			- [[@RECURRENT INDEPENDENT MECHANISMS]]
			- [[@Modular Networks: Learning to Decompose Neural Computation]]
			- [[@Inductive biases of neural network modularity in spatial navigation]]
		- **Goals**
			- It seems there is a solid body of work showing a strong link between modularity (in a functional sens most of the time) and the ability to generalize / compose
			- However most of these work nuance this by showing that modular solutions are hard to attain under standard **unconstrained** optimization
			- This is where we come into play ! Our hardware conditions could constrain modules sufficiently to lead to strong modularity in the networks, which in turn enable better generalization ?
			-
	- ### Question 2 : For a given problem, what's the optimal modularity we need ?
		- This is in sort the inverse problem of the first one. Letting structure emerge from the requirements of the tasks
		-
- ## Second meeting
	- [[draws/2024-10-08-17-23-01.excalidraw]]
	-
-