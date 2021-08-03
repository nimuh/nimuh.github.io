## Education
- University of California, San Diego, B.Sc. Cognitive Science (2018)
- University of Hawaii at Manoa, M.Sc. Computer Science (2021)

## Current Interests
I am passionate about understanding artificial intelligence and using it to solve hard problems. My current interests are in the applications of deep learning to better understanding large genomic datasets. For example, large language models such as GPT-2 from OpenAI have been shown to generalize very well to other tasks besides language. These transformer-based architectures have shown promise in many domains so how would well would it work it the context of genomic analysis? Outside of genomics I am interested in deep learning itself such as neural network training dynamics. Outside of working in this incredible field I enjoy surfing and playing chess.

## Selected Projects
### [Genome Deep Learning](https://github.com/nimuh/cancer-dl)
This research focuses on predicting cancer risk across multiple cancer types only from the genotype of an individual. We were fortunate to get access to data from The Cancer Genome Atlas to perform this research. Since this was a group effort, my role was to try different neural architectures to find the best performing model. This required some creativity: a standard feed-forward network was not cutting it! We eventually found our best performing model to be an encoder-based architecture that attempts to learn a latent representation of the genomic data and a classifier at the same time. Ultimately, the performance of the paper this project was inspired by was not replicable in our case. We performed further analysis on the data to find much overlap between different cancer types and concluded that the classifier was having difficulty separating these highly entangled data points. My capstone project expanded upon this by attempting to look at how different loci in the genomic data contributed to the classification and if we can observe which cancers are similar based on the representation learned from the genomic data.

### [Deep Learning Interpretability for Genomics](https://drive.google.com/file/d/1cu25Det7OxyFogoY4xCjai3EWOHDV90n/view?usp=sharing)
This research was my focus for the past 18 months. This expands upon the project described above by exploring the hypothesis that we can extract class similarity from the learned neural network. To be thorough, I worked with simulated data and real genomic data. This was interesting work because it involved analysis of the learned parameters of neural networks and studying if we can gain useful information about the problem being studied. The title link points to the paper.

### [Image Segmentation for Monocular Visual Odometry](https://github.com/nimuh/deep-learning)
This survey was my my first step into computer vision. Some backstory to this project: I worked on a code challenge for a company that involved predicting the speed of a vehicle purely from the stream of frames captured by a dashboard camera. I completely failed the challenge (my solution did not generalize as well as I thought!) so this brought me to think about scene understanding, or image segmentation, for road scenes and how segmentation could help with estimating vehicle speed. This project involved surveying multiple classical methods for scene segmentation and a full implementation of [SegNet](https://arxiv.org/abs/1511.00561). The survey of methods provided a fresh perspective on the power of neural networks and how to perform scene segmentation with deep learning. The implementation itself was done in PyTorch with use of Weights and Biases to monitor training performance. I also used a GTX1660 Super to speed up the training of the neural network. 

### [Structural Balance in R](https://github.com/nimuh/StructuralBalanceInR)
This project involved optimizing R code with C++ for speeding up large scale graph computations. We specifically created a library that can be used to compute the structural balance of signed graphs. To be clear, a graph is considered "balanced" if we can separated the nodes into groups that do not like each other. The relationship between nodes is represented by a + or -, where - means the connected nodes are enemies. This is computationally intensive. We created an algorithm from scratch and then implemented it so others can use it. My responsibility in this project was to write the C++ code for the graph computations required by our algorithm. The technical details are all provided in the title link.

 



