---
layout: default
title:  Proposal
---
## Proposal
# Summary of the Project 
Our goal for this Project is to get our Agent to build buildings based off of what the users asks for AI to build. The inspiration came from the frustration of players that want to have a cool and or even a simple buildings for their world but don't want to put too much time  and effort into it since there’s much more to do in Minecraft! The user should be able to tell the AI to “build me a castle” and the AI should know what type of blocks to use in order to build it as well as know other blocks/feature that come along with making a castle look like a castle. In addition to that, the AI should also know where to put certain objects, for example, know to put the door at the bottom of the building and roof blocks on top. 

# AI/ML Algorithms
Natural Language Processing (NLP) for the queries (e.g., build a castle) and Convolutional Neural Networks (CNN) to classify the building style of the input models and K-Nearest Neighbors (K-NN) to provide the self-taught, automated suggestion of what it should build (e.g., building, house, castle)

# Evaluation Plan
Our program will be evaluated by testing features that determine the accuracy of the completed task as well as the appropriateness of the design. Penalties will be awarded if the agent fails to include specific features in the architecture of the build such as included 2 windows instead of the requested 3 or failing to execute requirement within an appropriate threshold such as height. Additionally, the agent will be judged on the utility of the design itself such as having doors that are accessible to walk through and ceilings that cover the appropriate area. We expect the metric to improve the agent’s building ability significantly because we will train him buildings of increasing complexity and thus allow him to learn from his reward / penalty incrementally until he is able to build intricate requests accurately. 

The qualitative sanity checks will be observing whether or not the buildings look like buildings, rather than piles of materials and if the features are positioned in appropriate places. Our moonshot case is that the agent is able to design and build something architecturally interesting and appealing by human design and aesthetic standards.


