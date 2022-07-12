### Neural-Style-Transfer

With an increase in popularity in NFT's there is a rise in generating images that do not even exist. Neural Style Transfer similarly generates a blend in the images 
between context and style.Deep neural networks have already surpassed human level performance in tasks such as object recognition and detection. However, deep networks
were lagging far behind in tasks like generating artistic artefacts having high perceptual quality until recent times. Creating better quality art using machine learning
techniques is imperative for reaching human-like capabilities, as well as opens up a new spectrum of possibilities.

#Building The Model
* Used Pretrained Model from Tensorflow for training removed some layers and trained with customised weights to generate an image that represented the context image and
does not loose all its characteristics.
* Used Foreground-Background Extraction for retaining the background and removing the image of person detected with high probability.
* Added the images together after masking them to generate the final images.

Points to note:
* There are lot of changes in the image generated on changing the hyperparamter values.

##Generated images:
![image](https://user-images.githubusercontent.com/83583106/178488282-fc6a25e4-e108-4418-aa7d-ea4150be444d.png)
Image generated without tuning.
![image](https://user-images.githubusercontent.com/83583106/178488616-4b1a33cb-a645-494b-9a4e-5a5cec6f2b29.png)

The image genrated on tuning the hyperparameters.
![image](https://user-images.githubusercontent.com/83583106/178488371-301ae959-c0e3-4b22-aba5-bce2a74a4f13.png)



