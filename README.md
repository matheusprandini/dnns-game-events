## Investigating the Performance of Various Deep Neural Networks-based Approaches Designed to Identify Game Events in Gameplay Footage

### Authors

- Matheus Prado Prandini Faria.
- Etienne Silva Julia.
- Marcelo Zanchetta do Nascimento.
- Rita Maria Silva Julia.

### Conference

ACM SIGGRAPH Symposium on Interactive 3D Graphics and Games, 2022 (SI3D 2022).

### Abstract

Video games, in addition to representing an extremely relevant field of entertainment and market, have been widely used as a case study in artificial intelligence for representing a problem with a high degree of complexity. In such studies, the investigation of approaches that endow player agents with the ability to retrieve relevant information from game scenes stands out, since such information can be very useful to improve their learning ability. This work proposes and analyses new deep learning-based models to identify game events occurring in Super Mario Bros gameplay footage. The architecture of each model is composed of a feature extractor convolutional neural network (CNN) and a classifier neural network (NN). The extracting CNN aims to produce a feature-based representation for game scenes and submit it to the classifier, so that the latter can identify the game event present in each scene. The models differ from each other according to the following elements: the type of the CNN; the type of the NN classifier; and the type of the game scene representation at the CNN input, being either single frames, or chunks, which are n-sequential frames (in this paper 6 frames were used per chunk) grouped into a single input. The main contribution of this article is to demonstrate the greater performance reached by the models which combines the chunk representation for the game scenes with the resources of the classifier recurrent neural networks (RNN).

### Code

**[Jupyter Notebook](src/I3D_2022.ipynb).** We recommend to run the code on Google Colab.

### Paper

**[SI3D 2022](docs/SI3D_2022.pdf).** Camera ready version.
