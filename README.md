# Inception-Score
  - Inception score script for measuring quality of images generating from GAN

# Method

  - This repo derived from paper named [Improved Techniques for Training GANs](https://arxiv.org/abs/1606.03498), In this paper, we can see more tricks and improved methods used for training GAN. 
  
  - Inception score is used to measure the quality of images generating from GAN model. It is considered as a good way to measure performance of GAN in quantity.

# Requirements
  - tensorflow 1.3.0

  - python 2.7.12

  - numpy 1.13.1

  - scipy 0.17.0

# Results
  
  - In this repo, you can easily get the result below:
 
      |cifar10 images|cifar10 images|
      |:------------:|:------------:|
      |![Alt test](cifar10.png)|![Alt test](cifar10.png)|
      |inception score:<br/> mean:2.1532264 </br> stddev:0.27045175|inception score:<br/> mean:2.1532264 </br> stddev:0.27045175||
  
# References
  - Code is derived from [openai/improved-gan](https://github.com/openai/improved-gan). 
  
  
