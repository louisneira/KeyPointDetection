# KeyPointDetection
CNN to learn to identify keypoints for facial recognition in images

The goal of this project is to create a convolutional neural network (CNN) to detect faces in images or in video frames. 

This project proposes to detect faces by finding keypoints within a photo that are typically found in faces. Keypoints, sometimes called landmarks, are used in computer vision to track unique objects in images as the image is rotated, shifted, or shown in a different scale (e.g., when an object is photographed at different distances). A robust set of keypoints is a set of keypoints that are invariant to scale, changes in image intensity, image rotation, and image shift. 

When a good set of keypoints is defined for an object, that object can be tracked in subsequent photos or video frames. 

This project proposes to approach the facial detection problem using a CNN trained on a set of images with pre-labeled keypoint data. The CNN trained on this will then be able to find faces in subsequent images by passing the unlabeled image through the CNN and finding keypoints located within the image. 

A final step is to use a Haar cascade classifier to isolate faces once keypoints have been found.
