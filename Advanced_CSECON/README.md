## Question 1:

Data analysis is stressed in experimental economics. For behavioral game research, large amounts of data under different scenarios are often collected (Croson, 2005). As a platform for several players to do small scale experiments, oTree needs the researchers to manually modify the scenarios to exhaust the possibilities, and the experiment can only be held among one group of participants at a time. Also, the UI is too simple and plain. Answering questions with no incentivizing image illustration might be dull for participants. Below is a demo of my trust game, which has no illustrations and can only be conducted one at a time.

![2_1](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/eb1468ec-bdc3-44cf-afc0-9206063691bc)

I will develop software based on oTree with the following modifications to improve it:

**1: Supporting Multiple Sessions Simultaneously:**

**Importance:** Efficiency and Scalability: The ability to run multiple sessions concurrently significantly enhances the efficiency and scalability of experimental studies. By conducting several sessions simultaneously, researchers can gather data from larger participant samples within a shorter timeframe. This scalability is crucial for achieving robust statistical power and generalizability in strategic interaction studies, as it allows researchers to capture a broader range of behaviors and responses across diverse populations.

**2: Automatic Generation of Different Scenarios:**

**Importance:** Enhanced Experimental Variation: Automatically generating different scenarios diversifies experimental conditions, enabling researchers to explore a wider spectrum of strategic interactions. This variation is essential for testing the robustness of theoretical models and uncovering subtle behavioral patterns that may arise under different circumstances. By automating scenario generation, researchers can efficiently explore a multitude of experimental conditions, enriching the depth and breadth of their analyses.

**3: Enhanced User-Friendly UI with Visual Illustrations:**

**Importance:** Improved Participant Engagement and Comprehension: A user-friendly UI with visual illustrations enhances participant engagement and comprehension, reducing potential confounds introduced by misunderstandings or misinterpretations of experimental instructions. Clear visual representations of game scenarios promote active participation and reduce cognitive load, ensuring that participants can focus on strategic decision-making. By enhancing the quality of participant data, Stratify Pro enables more accurate and reliable insights into human behavior in strategic interactions.

![image](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/b993b635-751d-44b7-978b-c018696c7f20)

## Question 2:

The environment constraints in MARL involve the difficulty in simulating realistic interactions between agents. In Connect Four, while the environment is static and predictable, simulating a diverse range of opponent strategies can be challenging. MARL frameworks need to encompass not just the mechanics of the game board, but also the potentially complex strategies and counterstrategies that evolve as part of learning. Each agent’s move alters the state of the environment, leading to a combinatorial explosion of possible states, which can be computationally expensive to handle and learn from. In terms of algorithm customization, agents in MARL frameworks must be adaptive to the strategies of others while also improving their play. Yet, most MARL algorithms struggle with non-stationarity, where the behavior of one agent changes the environment, thereby affecting the learning process of the other. To illustrate, in Connect Four, if one agent begins to favor a new column as a starting move, this changes the expected game progression, thus requiring the other agent to adapt. Customizing algorithms that can efficiently manage this non-stationarity remains a significant hurdle. As the endgame shows below, the agent seems to be focusing on its success while ignoring the opponent’s strategy of winning, thus failing to make the best move to prevent potential failure.

![image](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/8fc2c6ce-10d1-46c7-a65e-263a377c69f0)

The development process of a MARL agent for Connect Four would first involve defining the game states. These include every possible combination of tokens on the 7x6 grid board, which are vast but finite. Actions for an agent are relatively straightforward: placing a token in one of the seven columns, as long as it is not already full. In implementing MARL for Connect Four, designers program agents to observe the environment (game board), perform actions (place tokens), and receive rewards (win/lose feedback). Learning progresses through multiple games where agents adapt their strategy to maximize their long-term reward, which, in simple terms, translates to increasing their chances of winning the game.

To overcome existing MARL limitations, research is directed towards creating more scalable algorithms capable of managing complex state-action spaces like those in Connect Four. Techniques such as function approximation, hierarchical reinforcement learning, and transfer learning are explored to tackle the non-stationarity and to allow agents to generalize their knowledge to new, unseen states effectively. Furthermore, while playing against a diverse set of strategies can be computationally intensive, employing parallel computing and distributed systems enables more extensive and varied training, leading to robust agents. Moreover, customized rewards shaping can incentivize agents to explore the state space more efficiently and learn the desired strategies. Continuous or intermediate rewards, instead of just a final win/lose outcome, can provide richer learning signals for agents, leading to improved performance.

## Question 3:

1. The paper addresses the challenge of designing incentive mechanisms for unbiased federated learning with randomized client participation. It aims to incentivize clients with non-i.i.d. data distributions to actively participate while ensuring fairness and convergence. Methodologies include deriving a convergence bound to characterize the impact of client participation levels and non-i.i.d. data on model performance. The proposed solution involves a randomized client participation mechanism combined with an optimal pricing scheme. The proposed solutions are intended for real-world federated learning contexts where data is distributed across multiple clients with non-i.i.d. distributions. The paper suggests adapting pricing schemes and participation mechanisms to accommodate varying levels of client interest in contributing to the global model. Practical considerations such as budget constraints and client heterogeneity are taken into account during evaluation.

2. While the research questions posed in the paper are relevant and address important aspects of federated learning, there could be additional objectives that enhance its impact. For instance, investigating the trade-offs between privacy preservation and model accuracy in federated learning could provide valuable insights. Understanding how different privacy-preserving techniques affect model performance and convergence could be crucial for deploying federated learning in sensitive domains like healthcare and finance. Additionally, exploring the scalability of incentive mechanisms for federated learning across large-scale networks could offer practical insights into managing diverse and dynamic client populations efficiently.

3. The paper assumes rational behavior among participating clients and employs mathematical models to analyze their interactions. While this assumption simplifies the analysis, it may overlook factors such as altruism, competitiveness, or bounded rationality, which could significantly influence clients' decision-making. To address this, incorporating behavioral economics principles into the model could provide a more realistic depiction of client behavior. Additionally, conducting empirical studies or simulations with real-world data could validate the model's assumptions and provide more robust insights into client behavior in federated learning environments.

4. The paper's application scenarios are relevant but may benefit from exploring more modern contexts. For instance, integrating federated learning with blockchain can enhance data privacy and security. Additionally, exploring generative AI and federated learning could enable collaborative model training while preserving data privacy. Finally, investigating federated learning in quantum computing environments could leverage quantum-enhanced algorithms for more efficient and secure model training. These modern scenarios offer promising avenues for extending federated learning research to address evolving challenges in data privacy, security, and computational efficiency.

5. Generally, I believe AI is more rational than human in making decisions. Involving AI participants means less uncertainty for the research. AI agents are more rational with fewer personal feelings, and they often have a more comprehensive understanding of the research scenario. Therefore, they are more willing to do full participation. Here’s the mini-ex

![image](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/aa1747ff-e2bc-4936-a79d-a33d6e0a4773)
![image](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/237944c4-b02d-4d83-9d72-a8be5c53e77e)

**Bibliography**

Croson, Rachel. "The Method of Experimental Economics", International Negotiation 10, 1 (2005): 131-148, doi: https://doi.org/10.1163/1571806054741100

Luo, Bing, Yutong Feng, Shiqiang Wang, Jianwei Huang, and Leandros Tassiulas. 2023. “Incentive Mechanism Design for Unbiased Federated Learning with Randomized Client Participation.” ArXiv (Cornell University), April. https://doi.org/10.48550/arxiv.2304.07981.
