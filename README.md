# Nima Azbijari

I am a PhD student at Oregon State University studying Artificial Intelligence. I have worked on a variety of different projects ranging from speeding up graph computations for social network analysis to building deep learning models to classify cancer from genotypes of individuals. This website is meant to be a location for writing about my research and other projects.

## Education
- University of California, San Diego, B.Sc. Cognitive Science (2018)
- University of Hawaii at Manoa, M.Sc. Computer Science (2021)
- Oregon State University, Ph.D. Artificial Intelligence (2025)

## Selected Projects
### [Genome Deep Learning](https://github.com/nimuh/cancer-dl)
Developed a deep learning model to classify 12 types of cancer from genotypes of individuals.

### [Structural Balance in R](https://github.com/nimuh/StructuralBalanceInR)
Created a software library in R for quickly computing structural balance in signed graphs.

### [Image Segmentation for Monocular Visual Odometry](https://github.com/nimuh/deep-learning)
Surveyed different approaches for image segmentation and how it helps with monocular visual odometry. Implemented SegNet for CityScapes dataset.

# Notes
## July 9, 2021: Language Models as Autoencoders
[This paper](https://arxiv.org/abs/2103.05247) discusses an interesting capability of transformers pretrained on a large language corpus. Specifically, they look at GPT-2 and how it this model can transfer to other modalities such as image classification. Surprisingly, the authors found performance in SOTA can be replicated with this model. As a result, this raises the question of what other types of non-language modality tasks can this model accomplish. To poke at this question, I became interested in observing how well GPT-2 can serve as a decoder for an image. Basically, can we reconstruct an input image with the same performance (or better) as an autoencoder for images?

### Preliminaries: What are transformers? How do we feed images to language models?

## June 15, 2021: Embodied AI (draft)
The embodiment thesis states that cognitive processing is highly impacted by an agent's physical body. The field of Embodied AI has gained popularity in recent years due to exponential advances in computer vision, natural language processing, and robotics. Researchers believe that solutions to certain problems such as navigation and exploration in a real world setting can lead to embodied artificial intelligence. The community has defined specific problems such as point goal navigation and embodied question answering as the next step. Point goal navigation involves telling an agent to navigate to a specified point on the map. Embodied question answering builds on this (and other exploration and navigation tasks) where the agent is asked a question ("What color is the car?") and the agent has to find the car and respond appropriately. 

Successful execution of these tasks is difficult and takes a big step away from Internet AI. Ultimately, the goal of artificial intelligence is to create machines that behave like humans do (or possibly better). A machine that can perform these tasks thus exhibits behavior closer to us. This post briefly talks about these research problems.

### Visual Navigation
#### Point Navigation
Point navigation seems straight forward: given a starting coordinate go to the destination coordinate. One complexity that arises is the objects and shape of the environment. Different obstacles can make going to the destination directly impossible so having prior knowledge about the environment is necessary.

#### Object Navigation
Object navigation provides more complexity. The agent cannot simply go to a specified point. It has to find an object in the environment. This also requires prior knowledge of the environment in order to know where to go. This prior knowledge can be obtained visual exploration of the environment.

#### Vision and Language Navigation
TODO




## June 14, 2021: Exploring OOD detection with Likelihood Ratios
Robust AI is becoming very popular due to the rising necessity of AI safety. This lead to some exploration around the topic and I stumbled upon this paper from Google from a few years ago. They discuss an approach for detecting data outside of the distribution of the training data. This approach uses likelihood ratios to obtain probabilities for classes by only considering the semantic information in the input. To explore this idea I built a toy model for the Fashion MNIST benchmark dataset and evaluate the confidence on the MNIST dataset. It is easy to notice that as the model performance improves on Fashion MNIST the probabilities outputed for MNIST begin to skew towards a fashion class. In other words, the model is learning about different clothing and then once it sees a number it is really confident that it is also a piece of clothing. 



