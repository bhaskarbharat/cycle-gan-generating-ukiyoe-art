# cycle-gan-generating-ukiyoe-art
CycleGANs to generate Ukiyo-e Art

[Project Notebook](https://colab.research.google.com/drive/1SljAM52fu1ZmW2LJc3Hoq5PpVAXQPvpM?usp=sharing) | [Project Presentation](https://drive.google.com/file/d/1yYP2Y22v2nWPcPaygBM5MaAWIyR8G_RD/view?usp=sharing)  | [Project Poster](https://drive.google.com/file/d/1TVO_Sf3i9OWk3FhskLIWxXRCYyrIkaZY/view?usp=sharing)  | [Project Video Presentation](https://drive.google.com/file/d/1QJ79OLgbd-4E5_kyHp9Sebvb1ydVhX5L/view?usp=sharing)

## Problem Statement

Image-to-image translation involves generating a new synthetic version of a given image with a specific modification. The CycleGAN is a technique that involves the automatic training of image-to-image translation models. The models are trained in an unsupervised manner using a collection of images from the source and target domain that do not need to be related in any way. In this project, we will take in an input image and generate Ukiyo-e art.

![input_to_output](https://github.com/bhaskarbharat/cycle-gan-generating-ukiyoe-art/raw/main/images/input_to_output.png)

Download the dataset [here](https://people.eecs.berkeley.edu/~taesung_park/CycleGAN/datasets/ukiyoe2photo.zip).

Read the CycleGAN paper [here](https://www.cs.cmu.edu/~junyanz/projects/CycleGAN/CycleGAN.pdf).

## Motivation

Why not just use Autoencoders? or Conditional GANs (like Pix2Pix) ?
- Need labelled & paired images
- Preparing such training data is often difficult , expensive and even impossible. 
- Less generalisable

![dataset](https://github.com/bhaskarbharat/cycle-gan-generating-ukiyoe-art/raw/main/images/dataset.png)

![cycleGAN_losses](https://github.com/bhaskarbharat/cycle-gan-generating-ukiyoe-art/raw/main/images/cycleGAN_losses.png)

![model_architecture](https://github.com/bhaskarbharat/cycle-gan-generating-ukiyoe-art/raw/main/images/model_architecture.png)

![results](https://github.com/bhaskarbharat/cycle-gan-generating-ukiyoe-art/raw/main/images/results.png)

![conclusions](https://github.com/bhaskarbharat/cycle-gan-generating-ukiyoe-art/raw/main/images/conclusions.png)

![future_work](https://github.com/bhaskarbharat/cycle-gan-generating-ukiyoe-art/raw/main/images/future_work.png)

## Project Presentation
[![project presentation](https://github.com/bhaskarbharat/cycle-gan-generating-ukiyoe-art/raw/main/images/video_screenshot.png)](https://drive.google.com/file/d/1QJ79OLgbd-4E5_kyHp9Sebvb1ydVhX5L/view?usp=sharing)
