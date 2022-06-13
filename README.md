# Machine-Vision-Satellite-Classifications

## Introduction
Marine vessels have been one of the most effective and trusted methods of shipping for centuries.
With the advent of mass remote ordering and a general increase in import and export demands, it is vital that boat shipping companies and port
authorities have accurate information on vessals. This helps to efficiently route ships to their destination, ensure that supply chains run swiftly, and
that the product is delivered to the end user in a timely fashion.

Keeping this context in mind, this project attempts to leverage both satellite imagery and the establishment of machine learning object detection models to enable an 
alternative solution to keeping track of marine vessels. With the world being struck by COVID and an increased demand that is putting strenious pressure on supply chains,
novel ideas such as this one can potentially make a difference.

## Methodology

Utilizing various object detection architectures, a trained model was created by leveraging **TensorFlow library**, **TensforFlow ModelZoo**, and **Sentinel 1 datasets**. Trained the models based on local annotated satellite images.

The following models were used, where R-CFN had the most effective results:
* **Faster R-CNN**
* **SSD or Singe Shot Detector**
* **R-CFN or Region-based Convolution Fusion Network**

## Results

The efficacy of the models tested:
