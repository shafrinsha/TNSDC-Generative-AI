Introduction:

In today's digital landscape, the analysis of demographic information extracted from images has gained significant importance. This project offers a solution for predicting both gender and approximate age of individuals based on their photographs. Utilizing the capabilities of deep learning, specifically employing Keras with TensorFlow backend, the system can discern patterns within images to make accurate predictions.

Dataset Overview:

The UTKFace dataset stands as a large-scale repository of facial images spanning a wide age range, from newborns to centenarians (ranging from 0 to 116 years old). Comprising over 20,000 facial images annotated with age, gender, and ethnicity, this dataset encapsulates a rich diversity of poses, facial expressions, lighting conditions, occlusions, resolutions, and more. Its versatility lends itself to a multitude of tasks, including but not limited to face detection, age estimation, age progression/regression, and landmark localization.

Project Objective:

The primary aim of this endeavor is to discern gender and age from facial images. This is achieved through the implementation of a Convolutional Neural Network (CNN) for image classification. The network yields two distinct outputs: gender (M or F) and age.

Dataset Download Link: [UTKFace Dataset](https://www.kaggle.com/datasets/jangedoo/utkface-new)
Environment: Kaggle

Required Libraries:

- Pandas
- Numpy
- Matplotlib
- Keras
- TensorFlow
- Scikit-learn

Neural Network Specifications:

- CNN Gender Accuracy: 90.00%
- Age Mean Absolute Error (MAE): 6.5

Demo Video Link: [Demo Video](https://drive.google.com/file/d/1EHgEZeka4uB9c2ou2JU-PMQxMD9K2uhB/view?usp=drivesdk)