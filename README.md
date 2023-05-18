# Neural-Style-Transfer---Tensorflow
# Introduction
This is the process which utilises deep learning to compose one image in the style of another image. The paper titled "A Neural Algorithm of Artistic Style" by Gatys et al. [1] gave the inspiration to build this project.

"Neural style transfer is an optimization technique used to take two images—a content image and a style reference image (such as an artwork by a famous painter)—and blend them together so the output image looks like the content image, but “painted” in the style of the style reference image.

This is implemented by optimizing the output image to match the content statistics of the content image and the style statistics of the style reference image. These statistics are extracted from the images using a convolutional network." [2]

<img width="926" alt="image" src="https://github.com/sahilfaizal01/Neural-Style-Transfer---Tensorflow/assets/106440078/d25c6972-4e1b-4ced-8a0b-9d0b0e0b65ce">

# Example
<img width="1040" alt="Screenshot 2023-05-18 at 10 08 13 AM" src="https://github.com/sahilfaizal01/Neural-Style-Transfer---Tensorflow/assets/106440078/b7c98e1a-4ac6-455c-aefd-a9186c82a8bb">
Content Image A followed by respective style images on left corner of images B, C and D

# Input
## Style Image
<img width="227" alt="image" src="https://github.com/sahilfaizal01/Neural-Style-Transfer---Tensorflow/assets/106440078/3a92bc9c-8380-4701-bfbc-42a8de04624d">

## Content Image
<img width="227" alt="image" src="https://github.com/sahilfaizal01/Neural-Style-Transfer---Tensorflow/assets/106440078/f5e510a9-0fbc-4ea2-8818-2063fe5a53e2">

# Output
<img width="372" alt="image" src="https://github.com/sahilfaizal01/Neural-Style-Transfer---Tensorflow/assets/106440078/7c6968f0-c16e-4b36-b161-34b36d2f54d6">

# Note:-
## 1) Gram-Matrix 
* Is a measure of correlation between two filters
* If suppose a filter to detect black and brown stripes and one to detect eyes are present then it might imply the presence of a tiger
## 2) Loss Function

### Content Loss
<img width="392" alt="image" src="https://github.com/sahilfaizal01/Neural-Style-Transfer---Tensorflow/assets/106440078/9790570e-e789-4f3b-9663-ebb04ca1c2de">

### Style Loss
<img width="392" alt="image" src="https://github.com/sahilfaizal01/Neural-Style-Transfer---Tensorflow/assets/106440078/806471bc-f8b2-4ddb-99ee-d597d43438db">

### Total Loss
<img width="474" alt="image" src="https://github.com/sahilfaizal01/Neural-Style-Transfer---Tensorflow/assets/106440078/c71fa7af-a7e5-4c49-9595-e85647eb5ba8">


## Content Image

# References
* [1] https://arxiv.org/pdf/1508.06576.pdf
* [2] https://www.tensorflow.org/tutorials/generative/style_transfer
* [3] https://www.tensorflow.org/api_docs/python/tf/GradientTape
* [4] https://aihub.cloud.google.com/u/0/p/products%2Fd422cfe8-669a-4cc0-8695-46138988b718
