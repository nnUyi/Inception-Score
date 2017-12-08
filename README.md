# Inception-Score
  - Inception score script for measuring quality of images generating from GAN

# Method

  - This repo derived from paper named [Improved Techniques for Training GANs](https://arxiv.org/abs/1606.03498), In this paper, we can see more tricks and improved methods used for training GAN. Anyway, sometimes, they are helpful.
  
  - Inception score is used to measure the quality of images generating from GAN model. It is considered as a good way to measure performance of GAN in quantity.

# Requirements
  - tensorflow 1.3.0

  - python 2.7.12

  - numpy 1.13.1

  - scipy 0.17.0
  
# Usages
## download repo
    $ git clone https://github.com/nnuyi/Inception-Score.git
    $ cd Inception-Score

## load data
   - In this repo, I provide 30 images sampled from cifar10. All the images are stored in the data directory(named **data**).
   
   - If you want to use your own data, images should be stored in data directory. And then launch the code.

## launch repo
    $ python inception_score.py

# Results
  
  - In this repo, you can easily get the result below:
 
      |cifar10 images|cifar10 images|
      |:------------:|:------------:|
      |![Alt test](cifar10.png)|![Alt test](cifar10.png)|
      |inception score:<br/> mean:2.1532264 </br> stddev:0.27045175|inception score:<br/> mean:2.1532264 </br> stddev:0.27045175||
  
# References
  - Code is derived from [openai/improved-gan](https://github.com/openai/improved-gan). Thanks all the way.
  
# Contacts

  - Email:computerscienceyyz@163.com
  
