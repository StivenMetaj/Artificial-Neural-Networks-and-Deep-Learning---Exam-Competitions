# Artificial Neural Networks and Deep Learning
## Kaggle Competitions about classification, segmentation and visual query answering
In this repository you can find the jupyter notebooks used to take part at the competitions created for the Artifical Neural Networks and Deep Learning exam at Politecnico di Milano.
***
The notebooks use tensorflow 2.0 and keras to create predictive models.
***
Remember that the notebooks have not the goal to be runned as they are here, but they were runned for the competitions and **partially** re-runned for producing this repository. If you want to run them, download the datasets and modify the code in order to set the right paths.
***
## Competition 1 - Image classification [[kaggle competition](https://www.kaggle.com/c/ann-and-dl-image-classification)][[dataset - 91 MB](https://www.kaggle.com/c/17346/download-all)]
- Image classification of 20 different classes (e.g. owls, wine-bottles, airplanes, calculators...).  
- Evaluation trhough MultiClass Accuracy.  
- 1554 images in total of different dimensions for training. 500 for testing.  
## Competition 2 - Semantic Segmentation [[kaggle competition](https://www.kaggle.com/c/ann-and-dl-image-segmentation)][[dataset - 1 GB](https://www.kaggle.com/c/17695/download-all)]
- Semantic Binary Segmentation of satellite building images.  
- Evalutation through Intersection over Union (IoU).  
- 7647 256x256 images for training. 1234 for testing.  
## Competition 3 - Visual Query Answering [[kaggle competition](https://www.kaggle.com/c/ann-and-dl-vqa)][[dataset - 13 GB](https://www.kaggle.com/c/17987/download-all)]
- Visual Query Answering on synthetic scenes composed by several objects (e.g. spheres or cubes) and corresponding questions about the existence of something in the scene (e.g., Is there a yellow cube?') or about counting (e.g., How many big spheres are there?').
- Possible answers: "yes", "no", "0", "1", ..., "10".
- Evaluation through Multiclass Accuracy.
- 69642 320x480 images and 259492 questions for training. 2754 images and 3000 question for testing.


