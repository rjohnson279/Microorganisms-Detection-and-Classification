# Microorganisms-Detection-and-Classification
### The Application of Computer Vision and Deep Learning for Microorganism Detection  and Classification

 **Ryan T. Johnson**
 
 In the world of freshwater microbiology, a single drop of water can potentially contain a
 large ecosystem on a microscopic scale. By creating an identification system for
 freshwater microorganisms, people can understand the particular microorganism and
 their crucial role in the ecosystem, allowing life to flourish. This research delves into how
 computer vision, a field of artificial intelligence and deep learning, is used to classify
 objects within images and identify what an image represents based on different
 classes/labels. Given the staggering diversity of microorganisms, our research focused
 on a select few to create models capable of effective detection and classification. The
 six microscopic organisms are Paramecium, an unidentified Protozoa, Rotifer,
 Spirostomum, Stentor, and Vorticella. They were chosen with precision and care,
 ensuring the models' accuracy and reliability. The object detection model contains a
 dataset of 1152 images, and the image classification model contains a dataset of 1968
 images. These distinct model datasets originated from videos and images taken from a
 microscope where the samples originated from a freshwater retention pond.

 Through the training process of the object detection model, the Yolov8 (You Only Look
 Once Version 8) algorithm was employed on the dataset to determine the precise
 location of the microorganisms within the image. Similarly, for the training process of the
 image classification model, a convolutional neural network (CNN) was deployed on the
 dataset in which an image is classified based on the entire image. Augmented data
 images were added to the existing microorganism images in the datasets to enhance
 these models' overall accuracy. The different images have related conditions, which
 improve the model's overall efficiency. Some of the properties included changing the
 pixelation, brightness, and zooming. With these additions, each of the accuracies for the
 object detection model improved to 92%, and the image classification model improved
 to 100%. With these promising accuracies, the research illustrates the promising role in
 which computer vision can provide insights into how various fields can use this tool to
 increase their understanding of different microorganisms in the ecosystems.
