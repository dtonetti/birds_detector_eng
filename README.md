# Birds Species Detector
This notebook is inspired in the first class of fast.ai **Practical Deep Learning for Coders** course.

The goal of this project is to build a machine learning aplication that can classify birds imagens into 9 different species using fast.ai library with transfer learning.

# Data Scrapping

I used the [**googliser**](https://github.com/teracow/googliser) script to download bird images from web and build my database.

# Models
For this project I used transfer learning on a CNN trained on resnet34, and did some fine-tunning to improve a little the results.

# Models Performance
- Default Resnet34: Accuracy = 92.06 % 
- Fine-Tuned Resnet34: Accuracy = 95.24 %

# Code and Resources Used

- Python Version: 3.7
- Packages: fast.ai
