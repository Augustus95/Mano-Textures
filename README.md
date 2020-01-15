[Mano Textures](https://github.com/JenathanHoo/Mano-Textures)
=========================
This repository is the implement of digitalizated Mano-textures for neural hand renderer


Feature
=========================
- **MANO-texture Dataset**：textures for [Mano](https://mano.is.tue.mpg.de/) model.
- **Appearance decoder**: learning hand pose、shape and appearance from a single image with differentiable renderer.
- **Neural hand app generation**：generating stylized hands for VR/AR applications.


Usage
=========================
**MANO-texture dataset**

Over 50 different [textures](https://github.com/JenathanHoo/Mano-Textures) for Mano model, where each mano-texture file includes： 
- **hand_id.mtl**: material library file for this mano-texture model.   
- **texture_id.png**: 2048x2048 texture image for this mano-texture model.  
- **hand_id.obj**: random mano pose obj file with this mano-texture for immediate visualization.

**Appearance decoder** 

This work learns hand pose、shape and appearance from a single image with differentiable renderer, with the help of over 500k images dataset rendered from digitalizated Mano-textures and deep CNN. 
- **usage**: [code](https://github.com/JenathanHoo/Mano-Textures) coming soon.

**Neural hand app generation** 

This work is the inverse version of Appearance decoder，which generates stylized hands with arbitrary image input and can be used in many VR/AR applications.
- **usage**: [code](https://github.com/JenathanHoo/Mano-Textures) coming soon.

Results
=========================

**MANO-texture dataset** 

![](https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/r01.gif)![](https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/r2.png)![](https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/r3.png)

![](https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/r00.gif)![](https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/r1.png)




**Neural hand app generation**

 <img src="https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/out1.gif" width="140"/><img src="https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/in1.jpg" width="140"/><img src="https://github.com/JenathanHoo/Mano-Textures/blob/master/imgs/out3.gif" width="140"/>


**Appearance decoder**

[code](https://github.com/JenathanHoo/Mano-Textures) coming soon.


Links
=========================
[1] Official Website of MANO: [https://mano.is.tue.mpg.de.](https://mano.is.tue.mpg.de) 

[2] Official Website of SMPL: [http://smpl.is.tue.mpg.de.](http://smpl.is.tue.mpg.de) 

[3] Official Website of SMPLify: [http://smplify.is.tue.mpg.de.](http://smplify.is.tue.mpg.de) 

