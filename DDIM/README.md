# Denoising Diffuison Implict Model
[[paper]](https://arxiv.org/pdf/2010.02502.pdf) [[official code]](https://github.com/ermongroup/ddim)

# Tutorial: Toy Example [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JeongJiHeon/ScoreDiffusionModel/blob/main/DDIM/DDIM_MNIST.ipynb) 
  
### DDIM( η =0.0 ) generation and reproducibility

| DDPM( η = 1.0 ) of First generation | DDIM( η = 0.0 ) of First generation | DDIM( η = 0.0 ) of Second generation |
| :---------------:  | :---------------: | :---------------: |
| <img width="300" src="https://github.com/JeongJiHeon/ScoreDiffusionModel/blob/main/DDIM/figure/DDPM.png"> | <img width="300" src="https://github.com/JeongJiHeon/ScoreDiffusionModel/blob/main/DDIM/figure/first_DDIM.png"> | <img width="300" src="https://github.com/JeongJiHeon/ScoreDiffusionModel/blob/main/DDIM/figure/second_DDIM.png">|

---
  
### Accelerating of DDIM
<img width="1200" src="https://github.com/JeongJiHeon/ScoreDiffusionModel/blob/main/DDIM/figure/Accelerating.png">

---
  
### Probability Flow ODE of DDIM
#### original -> forward ODE -> backward ODE
<img width="900" src="https://github.com/JeongJiHeon/ScoreDiffusionModel/blob/main/DDIM/figure/Probability Flow ODE-o2f2b.png">
  
#### latent -> backward ODE -> forward ODE
<img width="900" src="https://github.com/JeongJiHeon/ScoreDiffusionModel/blob/main/DDIM/figure/Probability Flow ODE-l2b2f.png">
