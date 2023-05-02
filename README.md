# Project Title

**Image Captioning System**

# Project Description

In this project, I will be building an image captioning system using deep learning techniques. The goal of the project is to create a system that can generate natural language descriptions for images. I will use an off-the-shelf image encoder to create matrices of image representations and an LSTM language generator to produce captions for those images. Data source: https://www.cv-foundation.org/openaccess/content_cvpr_2016/html/Szegedy_Rethinking_the_Inception_CVPR_2016_paper.html

# Project Workflow

I will start by reading and preprocessing the image captions, and then I will write a generator function that returns one training instance (input/output sequence pair) at a time. After that, I will train the LSTM language generator on the caption data and write a decoder function for it.

Next, I will add the image input to write an LSTM caption generator, and finally, I will implement beam search for the image caption generator.

# Project Goals

By the end of this project, I will have a working image captioning system that can generate captions for a given image.

# Technologies Used

Python
TensorFlow
Keras
NumPy
