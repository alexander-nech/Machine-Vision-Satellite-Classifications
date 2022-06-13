# Machine-Vision-Satellite-Classifications

## Introduction
Marine vessels have been one of the most effective and trusted methods of shipping for centuries.
With the advent of mass remote ordering and a general increase in import and export demands, it is vital that boat shipping companies and port
authorities have accurate information on vessels. This helps to efficiently route ships to their destination, ensure that supply chains run swiftly, and
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

<img width="346" alt="Screen Shot 2022-06-13 at 11 53 31 AM" src="https://user-images.githubusercontent.com/34041631/173395700-7b4641e3-31ed-41fe-84df-fb89803b16f7.png">

R-CFN image classifications of vessels examples:


<img width="470" alt="Screen Shot 2022-06-13 at 12 03 31 PM" src="https://user-images.githubusercontent.com/34041631/173396230-d9baec2c-1996-4d4d-bee5-8c933837e693.png">
<img width="487" alt="Screen Shot 2022-06-13 at 12 03 40 PM" src="https://user-images.githubusercontent.com/34041631/173396234-27314e8f-b6be-431c-9542-c445d51ae356.png">
<img width="467" alt="Screen Shot 2022-06-13 at 12 03 48 PM" src="https://user-images.githubusercontent.com/34041631/173396236-7c31d446-4984-4f78-85ce-82f71194f2e7.png">
