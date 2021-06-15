# Nima Azbijari

I am a PhD student at Oregon State University studying Computer Science and Artificial Intelligence. I have worked on a variety of different projects ranging from speeding up graph computations for social network analysis to building deep learning models to classify cancer from genotypes of individuals. This website is meant to be a location for writing about my research and other projects.

## Education
- University of California, San Diego, B.Sc. Cognitive Science (2018)
- University of Hawaii at Manoa, M.Sc. Computer Science (2021)
- Oregon State University, Ph.D. Computer Science (Present)

## Selected Projects
### Genome Deep Learning
Developed a deep learning model to classify 12 types of cancer from genotypes of individuals. (Link)

### Structural Balance in R
Created a software library in R for quickly computing structural balance in signed graphs. (Link)

### Image Segmentation for Monocular Visual Odometry
Surveyed different approaches for image segmentation and how it helps with monocular visual odometry. (Link)

# Daily Notes
## June 14, 2021: Exploring OOD detection with Likelihood Ratios
Robust AI is becoming very popular due to the rising necessity of AI safety. This lead to some exploration around the topic and I stumbled upon this paper from Google from a few years ago. They discuss an approach for detecting data outside of the distribution of the training data. This approach uses likelihood ratios to obtain probabilities for classes by only considering the semantic information in the input. To explore this idea I built a toy model for the Fashion MNIST benchmark dataset and evaluate the confidence on the MNIST dataset. It is easy to notice that as the model performance improves on Fashion MNIST the probabilities outputed for MNIST begin to skew towards a fashion class. In other words, the model is learning about different clothing and then once it sees a number it is really confident that it is also a piece of clothing. 



