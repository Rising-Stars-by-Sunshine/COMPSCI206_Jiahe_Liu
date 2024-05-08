# Comparative Analysis of Generative AI and Reinforcement Learning Models on Strategic Play in the Centipede Game

![poster](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/a631096d-399c-4bf8-b720-ac7b494e26a4)
**Fig. 1. Research Poster**


[URL to my shared view overleaf ](https://www.overleaf.com/read/xqmhntdkcsjb#0b18c9)

![image](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/a36a79c5-e9f2-4e0c-af3b-6cf458cf4e64)
**Fig. 2. Research Outline**

## Summarize the Background/Motivation

- The gap between existing literature and pressing social and economic issues in the digital economy arises from the complexities of interactions between humans and AI agents. This inspires my research to address how AI decision-making impacts human behavior and vice versa in strategic scenarios.

## Research Questions

*What are the questions that your research intends to answer?*

- How do interactions between human and AI agents in strategic scenarios affect overall system performance and individual welfare?
- What are the behavioral and decision-making dynamics that emerge when humans interact with AI agents in strategic settings?

*Why are the questions important?*

- These questions are essential for understanding the dynamics of human-AI interactions and crucial for designing effective policies, regulations, and algorithms in the digital economy.

*Why are the questions not answered by existing game theory literature?*

- Traditional game theory often overlooks the nuances of human decision-making, assuming purely rational behavior. However, bounded rationality sometimes leads to worse outcome. Besides, previous research fail to identify the potential of computational agents, which will be increasingly frequently involved in strategic scenarios. For example, in Gamba and Regner's research (2019), they examinated how personal preference influences mistrust among human participant in Centipede game. My research would switch to observing the behavior of computational agents in this game, specifically reinforcement learning model and generative AI.

## Application Scenario

*In which real-world situation does your newly proposed game and/or solution concept or mechanism apply?*

- My proposed research applies to various real-world situations where strategic decision-making is crucial. One example is in the field of economics, where understanding how different agents interact and make decisions can inform policy interventions aimed at improving market efficiency, resource allocation, and overall economic welfare. Additionally, this research can be applied in negotiation settings, conflict resolution processes, and strategic planning in business, politics, and international relations, where insights into human and AI decision-making dynamics are essential for achieving desirable outcomes.

*What is the literature in another discipline such as psychology that could provide a behavioral foundation for your newly proposed game and/or solution concept, or mechanism?*

- The literature in psychology provides a behavioral foundation for understanding human responses to AI agents. Studies on human-computer interaction, trust in automation, and decision-making in uncertain environments offer valuable insights into how individuals perceive and interact with AI agents. For instance, research by Nass and Reeves (1996) on the media equation theory suggests that individuals tend to apply social rules and expectations to interactions with computers and AI agents, shaping their trust and reliance on these systems. Additionally, work by Acquisti and Grossklags (2005) highlights the role of privacy concerns and perceived control in users' acceptance of AI-driven recommendations and decisions, further informing our understanding of human-AI interactions in online environments.

## Methodology

*What is the key game theoretical or mechanism design framework that you build upon?*

- My research is built upon the classic centipede game, as is illustrated in the game tree in my poster. In this game, two players take turns deciding whether to continue or stop the game. Each time the game continues, the prize pot grows, but if one player decides to stop, the game ends, the prize is divided, and the one who chooses to stop gets more reward. By backward induction, players typically end the game immediately for the best outcome.

*What are the key computational or analytical tools that you apply to answer your research question?*

- I applied reinforcement learning models and AI agents, which are the objects in my research. My reinforcement learning model, which is based on Q learning, will focus on getting more rewards, while generative AI, specifically ChatGPT 4.0, will consider human factors like trust. Understanding how different agents interact and make decisions can inform policy interventions aimed at improving market efficiency, resource allocation, and overall economic welfare. Additionally, this research can be applied in negotiation settings, conflict resolution processes, and strategic planning in business, politics, and international relations, where insights into human and AI decision-making dynamics are essential for achieving desirable outcomes.

*What is the advanced technology or interdisciplinary insights that you integrate into the existing methods that smartly solve your research question?*

- I intergrate the advanced computational technology with classic economic models to investigate the trust issue among AI agents and in human-AI interactions.

## Preliminary Results

*Can you provide a concrete illustration example of game theory or mechanism design that your approach significantly improves at least one objective of human welfare compared to existing research without your approach?*

- In the context of the Centipede Game, my research compares the performance of generative AI ChatGPT 4.0 and Q learning model in the centipede game. By analyzing simulated game scenarios, we found that ChatGPT 4.0 outperforms Q learning in capturing complex strategic interactions and predicting decision-making processes. This improvement leads to a deeper understanding of player behavior and more accurate predictions of game outcomes, thereby enhancing decision-making in strategic settings. Below are the screenshot of my experiment with GPT 4, and the colab link to my Q learning model.

![gpt question](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/747b082c-c006-4797-b9dc-93c527ed7179)
**Fig. 3. Question for GPT**


![gpt answer](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/a21a69cb-913f-42d4-8609-dcf60c32c860)
**Fig. 4. Answer from GPT**

![q learning result](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/6fc8455a-4723-43ae-9f17-a3c28610e360)
**Fig. 5. Q learning result**

[Colab](https://colab.research.google.com/drive/1wFoMbtwd9U5mJ26s0nzbOXEsWmb_vU7P?usp=sharing)


## Intellectual Merits and Practical Impacts of Your Project

*Can you demonstrate the limitations of your current research that would inspire future research?*

- My model and experiment might not be an accurate description of the real world strategic contexts. Future research could focus on refining the reinforcement learning model to adapt to dynamic strategic scenarios. Besides, my research only reveals some behavioral patterns of different agents. Researchers could also apply the patterns and explore the possibilities in building trust and effective contracts between different computational agents and human.

*Can you elaborate on how your research can be applied to improve individual, company, and government decisions in strategic scenarios or social choice issues?*

- By providing policymakers, businesses, and individuals with a deeper understanding of human-AI interactions, my research enables more informed decision-making and the development of policies and systems that promote fairness, efficiency, and societal welfare in the digital economy.

**Bibliography**

Acquisti, A., & Grossklags, J. (2005). Privacy and rationality in individual decision making. IEEE Security & Privacy, 3(1), 26-33.

Gamba, A., & Regner, T. (2019). Preferences-dependent learning in the centipede game: The persistence of mistrust. European Economic Review, 120, 103316. https://doi.org/10.1016/j.euroecorev.2019.103316.

Nass, C., & Reeves, B. (1996). The Media Equation: How People Treat Computers, Television, and New Media Like Real People and Places. Cambridge University Press.


![image](https://github.com/Rising-Stars-by-Sunshine/COMPSCI206_Jiahe_Liu/assets/124045985/b3393444-2217-44f3-bab0-d1c193e5bfd9)
**Fig. 6. Grammarly test**
