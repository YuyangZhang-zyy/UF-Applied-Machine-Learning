[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/xYyCX8kr)
# Project 3

This is an **individual assignment**.

## Code Implementation & Technical Report

The final deliverables include a 4-page IEEE-format report, code implementation and a detailed GitHub readme file.

Project 3 is due December 6 @ 11:59 PM. Find the complete [rubric](https://ufl.instructure.com/courses/479519/assignments/5884806) in the Canvas assignment.

## Dataset 1 -  Car Detection Dataset

[Download](https://ufl.instructure.com/files/82943015/download?download_frd=1) the training images, test images and the csv bounding box coordinates.

## Dataset 2 - Custom Flower Species Dataset

[Download](https://ufl.instructure.com/files/82943306/download?download_frd=1) the training and test images and labels.

## Edit this READ-ME

Please edit this read-me file with information about your project. There are no requirements for this readme file, but you can find a [template here](https://github.com/catiaspsilva/README-template).

## README

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#authors">Authors</a></li>
  </ol>
</details>

## About The Project

In this project, we trained different artificial neural network models to complete flower species classification tasks and car detection tasks. We will find the best model for both tasks by training multiple neural network models and testing their performance. In the car detection task, we will also discuss how to deal with abnormal situations in the training set. In this experiment we use TensorFlow 2.7.0 to create the model.

### File list:

## Files in github:

1. Project 3 - Artificial Neural Networks.ipynb: Project 3 guideline.

2. training.ipynb: Training file that contains the models training and hyperparameter tuning steps.

3. training.pdf: pdf version of training.ipynb.

4. test.ipynb: Test file for evaluating the final trained model in the test set. This file loads all trained objects and simply evaluate the performance. All expected plot and graph are contained

5. test.pdf: pdf version of test.ipynb.

6. Project 3 Report.pdf: 4-page IEEE-format paper addressing the questions in model.

7. requirements.yml: Python working environment, allow users to clone it locally

8. Model (file):

   Flower classification: ANN.h5 - Artificial neural network with 2 hidden layers; CNN.h5 - Custom convolutional neural network; TL.h5 - Transfer learning with Xception
   
   Car detection: VGG.h5 - Transfer learning with VGG16 

9. Training and test data:

   flower_species_classification (file): data_train.npy, data_test.npy, label_train.npy, label_test.npy

   car_detection_dataset (file): train_bounding_boxes.csv (training data's bounding boxes points), test_bounding_boxes.csv (test data's bounding boxes points), training_images (file that contains images of training set), testing_images (file that contains images of test set)


## Download links for large files:

Model.zip: https://drive.google.com/file/d/1c0wkB08HOiARqTgsYeFe_BFG_oTXHs6K/view?usp=sharing

flower_species_classification.zip: https://drive.google.com/file/d/1PuqBiD-dMHElILmGPG1mLetpJIHi1hyw/view?usp=sharing

car_detection_dataset.zip: https://drive.google.com/file/d/1VehSMAcEJ6_JOg6tUU7C13U4BUCp7-ak/view?usp=sharing

## Getting Started

### Dependencies

This project uses HiperGator environment: TensorFlow 2.7.0

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/UF-AppliedMLSystems-Fall23/project-3-YuyangZhang-zyy.git
   ```

## Usage

After downloading all necessary files, you can open training.ipynb and test.ipynb using Jupyter Notebook or any IDE you like. Remember the running environment is on HiperGator TensorFlow 2.7.0. So better use TensorFlow 2.7.0 on your local. First run all the codes in training.ipynb in order from top to bottom. You can get all the models and test sets created by the project and any components required for test.ipynb to run. On test.ipynb, run all the code from top to bottom, you can get performance evaluation of all models. You can directly run the test.ipynb to test the created models.

## Authors

Yuyang Zhang - yuyoungzhang@gmail.com

Project Link: [https://github.com/UF-AppliedMLSystems-Fall23/project-3-YuyangZhang-zyy](https://github.com/UF-AppliedMLSystems-Fall23/project-3-YuyangZhang-zyy)

## Thank you