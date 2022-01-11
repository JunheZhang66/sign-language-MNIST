# DATS6450 Final Project Sign-Language MNIST Problem
 Present by: Junhe Zhang

## Introduction of Sign-Language MNIST Problem (American Sign Language)

American Sign Language (ASL) is a complete natural language that has the similar linguistic properties as spoken language. ASL use hand movements combined with special gestures and face expressions to deliver their thought. ASL is the primary language of many North Americans who have speaking or hearing issues. The training and testing datasets which provided by Kaggle.com contains approximately 35,000 data points about 25 different gestures which represent alphabetic letters from A-Z without letter J and Z because of gesture motions issue. The datasets come with .CSV format which have 785 columns. The first column indicates the corresponding alphabetic letters label (from 0-25) and the rest of 784 columns represent 28x28 image pixels. 

<div style="text-align:center"><img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ6X3YuMamMSOulZ8lXSjmR6dXPB4jW1XKE3Q&usqp=CAU" /></div>

## Project Objective

The goal of this project is to utilize the GPU computational power, which obtained from AWS GPU instance, to process large dataset on deep neuron network model. In order to construct an accurate NN-model to correctly classify new coming ASL data points. This model could be used to create large YOLO format dataset for future real-time Object detection purpose study.
