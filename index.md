## Multimodal Differential Network for Visual Question Generation[pdf](https://arxiv.org/abs/1808.03986)

Badri N. Patro, Sandeep Kumar, Vinod K. Kurmi, Vinay P. Namboodiri

## Link for [MDN_VQG Code](https://github.com/badripatro/Visual_Question_Generation)

<p align="center">
 <img src="fig/cvpr_intro.png" width="600">
</p>

<p align="center">
 <img src="fig/cvpr_intro.png" width="600">
</p>

<p align="center">
 <img src="fig/cvpr_intro.png" width="600">
</p>

<p align="center">
 <img src="fig/cvpr_intro.png" width="600">
</p>


![](fig/cvpr_DAN.png) 

![](fig/cvpr_DAN.png) 

### Method
* Encoder Decoder architecture: We use Representation and Mixture modules to obtain a joint Image-Caption embedding and then a Decoder module to generate a natural language question.
* Representation Module: consists of a VGG-19 CNN to obtain image representation and LSTM for caption embedding for Target, Supporting and Contrasting exemplars.
* Mixture Module: takes in the image and caption embeddings and outputs 3 joint embeddings which are fed into a triplet network.
* Decoder Module: takes the target image-caption embedding and produces a sequence of question words. Our method is trained end to end.


