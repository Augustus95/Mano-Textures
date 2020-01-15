[Mano Textures](https://github.com/JenathanHoo/Mano-Textures)
=========================
This repository is the implement of digitalizated Mano-textures for neural hand renderer


Feature
=========================
- **MANO-texture Dataset**：different textures for [Mano](https://mano.is.tue.mpg.de/) model.
- **Appearance decoder**: learning hand pose、shape and appearance from a single image with differentiable renderer.
- **Neural hand app generation**：generating stylized hands for VR/AR application.


Usage
=========================
**MANO-texture dataset**

Over 50 different [textures](https://github.com/JenathanHoo/Mano-Textures) for Mano model, where each mano-texture file includes： 
- **hand_[id].mtl**: material library file for our mano-texture model.   
- **texture_[id].png**: 2048x2048 texture image for our mano-texture model.  
- **hand_[id].obj**: random mano pose obj file with our mano-texture.

**Appearance decoder** 

This work learns hand pose、shape and appearance from a single image with differentiable renderer, with the help of over 500k images dataset rendered from digitalizated Mano-textures and deep CNN. 
- **usage**: [code](https://github.com/JenathanHoo/Mano-Textures) coming soon.

**Neural hand app generation** 

This work is the inverse version of Appearance decoder，which generates stylized hands with arbitrary image input and can be used in many VR/AR applications.
- **usage**: [code](https://github.com/JenathanHoo/Mano-Textures) coming soon.

Results
=========================
**MANO-texture** dataset 


**Appearance decoder**

[updating]

**Neural hand app generation**

![](https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/in.jpg) ![](https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/out1.gif)



