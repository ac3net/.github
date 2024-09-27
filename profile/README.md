## Autonomous Communication in Cooperative Computer Networks (AC3Net)

This is the official account of [AC3Net](https://softwarecampus.de/en/projekt/ac3net-autonomous-communication-in-cooperative-computer-networks/), a two-year microproject (from 03/2022 to 06/2024) funded by the Federal Ministry of Education and Research of Germany (BMBF) through the [Software Campus](https://softwarecampus.de/en/) program.

The goal of AC3Net was to improve the cooperation of learning systems in computer networks by allowing them to exchange learnable messages.
Methodologically, the focus was on [reinforcement learning](http://incompleteideas.net/book/the-book.html) and [learned communication](https://arxiv.org/abs/2203.08975).

The main result of the microproject is a novel framework that treats networked systems as nodes in a [graph neural network](https://www.cs.mcgill.ca/~wlh/grl_book/) and conceptually separates these systems from agents.
Within this framework, systems exchange learned messages with other systems in their local neighborhood to iteratively build up a graph representation.
This graph representation may capture local and global features from the whole network and is leveraged by agents to solve the given tasks.
Within the microproject, the feasibility of this framework was demonstrated in the context of a routing environment, where agents have to find the shortest paths to other nodes in the network.
The results show that the framework enables communication systems to learn a sufficient routing protocol, although the agents are only provided a sparse reward signal when they reach their destinations.
This is promising regarding the development of future intelligent communication systems, as the same methodology could be leveraged to improve cooperation in any network of autonomous systems.

### 🚀 Open-Source Software

The main contribution of the project is available under the MIT license: https://github.com/ac3net/graph-marl

### 📝 Papers

There have been two publications in the context of the microproject:

The main contribution [PDF](https://arxiv.org/pdf/2402.05027)

> J. Weil, Z. Bao, O. Abboud, and T. Meuser, “Towards Generalizability of Multi-Agent Reinforcement Learning in Graphs with Recurrent Message Passing,” in Proceedings of the 23rd International Conference on Autonomous Agents and Multiagent Systems, in AAMAS ’24. Auckland, New Zealand: International Foundation for Autonomous Agents and Multiagent Systems, 2024, pp. 1919–1927.

A positional paper in cooperation with the Software Campus microproject by Pegah Golchin [PDF](https://opus.bibliothek.uni-augsburg.de/opus4/frontdoor/deliver/index/docId/109656/file/109656.pdf)

> P. Golchin, J. Weil, R. Kundel, and R. Steinmetz, “Dynamic network intrusion detection system in Software-Defined Networking,” in 2nd Workshop on Machine Learning & Netwoking (MaLeNe), co-located with the 5th International Conference on Networked Systems (NetSys 2023), Potsdam, Berlin, September 4, 2023: proceedings, M. Seufert, A. Blenk, and O. Landsiedel, Eds., 2023.

---

© project logo: Alisha Hirsch

<!--
**Here are some ideas to get you started:**

🙋‍♀️ A short introduction - what is your organization all about?
🌈 Contribution guidelines - how can the community get involved?
👩‍💻 Useful resources - where can the community find your docs? Is there anything else the community should know?
🍿 Fun facts - what does your team eat for breakfast?
🧙 Remember, you can do mighty things with the power of [Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
-->
