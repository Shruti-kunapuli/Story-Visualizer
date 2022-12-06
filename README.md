# Story-Visualizer

## About

The ability to generate visualizations from a given text has improved due to recent developments in text-to-image synthesis that use large pretrained transformers but these transformers require additional features to interpret stories with multiple characters and translate them into images. Story visualization can facilitate creative applications of automatic storyboarding in movies, narration, and story development. Storyboarding in a sequence of pictures portrays the significant shifts in scene and action, this can enable story writers to improvise their creative thoughts effectively following the story visualization. Hence, we propose to build on the pretrained knowledge of text-to-image synthesis model architecture to improve image generation for story continuation. 

We aim to build a model given a series of captions narrating a story plot which can generate a corresponding sequence of images that depicts the contents of these captions. To achieve this, we will train a text-to-image synthesis model on a sequential text-to-image generation job with the added ability to copy from a previous input and support story continuation. The challenging aspect of this project is that the given sequence of images must consistently and coherently depict the whole story and also display the logic of the storyline.

## Dataset Overview

We have utilized Pororo- SV dataset. Pororo Dataset is a cartoon dataset where each one-second video clip in the collection is linked to multiple manually written descriptions. We have used the Pororo dataset with a total description-image pair of 15,336 which contains images, descriptions, and metadata. We have split the 13,000 data points for training and validation. 2,336 description and image pairs for testing.

