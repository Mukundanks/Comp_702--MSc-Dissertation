# Comp-702
This  repository is about the Diabetic Retinopathy Detection using deep learning frame works like CNN and Vision Transformer(ViT). This work was done as a part of the Masters dissertation(COMP 702) for the course Big Data and High-Performance Computing in University of Liverpool.

The problem statement is to deploy a Machine Learning model in web. It was planned in such a way that, once a model is trained properly, the small hospitals can utilise the benefit of it, without spending much of their budget. For the same, I used Deep Learning methods like Resnet, Densenet and Vision Transformer. The dataset used here was the Kaggle-APTOS Diabetic Retinopathy detection, which was available to the public for competition. 

For the training, I planned to exlplore the benefits of GPU based training and Parallel training using single and multi-nodes. For single GPU training, I used Kaggle and Colab, and multi, I planned to use University of Liverpool's HPC system. Due to high demands, the HPC clusters were very limitedly available, and the idea of multi node was dropped for the time. 

Among the models, the Vision Transformer was the most complex one as it was developed from scratch and had many layers and processes compared with others. The other two models were Pretrained, and fine tuned for my project. 
