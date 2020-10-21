# Company-Logo-detection
Watched OpenCV tutorials for beginners https://www.youtube.com/watch?v=kdLM6AOd2vc&list=PLS1QulWo1RIa7D1O6skqDQ-JZ1GGHKK-K
🤗What is YOLO?
You Only Look Once is an object detection algorithm in which only a single convolutional network predicts the bounding boxes and their corresponding class probabilities. 
Blogs: 
https://medium.com/analytics-vidhya/everything-you-need-to-know-to-train-your-custom-object-detector-model-using-yolov3-1bf0640b0905
https://medium.com/@akarshzingade/logo-detection-using-yolov2-8cda5a68740e

Read this blog and implemented the same on my system.
Link: https://towardsdatascience.com/yolo-object-detection-with-opencv-and-python-21e50ac599e9
My implemention provided above.

✨Implemented a small object detection model on coursera 
Course link: https://www.coursera.org/projects/real-time-object-detection-yolo
Certificate: https://coursera.org/share/fa3ded4fcd97b5032653d2dd77bee9ee

Gone through this blog for video processing
https://towardsdatascience.com/yolov3-pytorch-on-google-colab-c4a79eeecdea

Steps required to implement object-detection model:
1. Collecting the dataset
2. Pre-processing and Augmentation
3. Annotation
4. Training our model
5. Obtain the weights

Started implementing the above in roboflow
https://blog.roboflow.com/training-a-yolov3-object-detection-model-with-a-custom-dataset/

For Preprocessing and Augmentation: https://blog.roboflow.com/why-preprocess-augment/                                 
Augmentation basically creates new training images from the existing images. This task is done using roboflow itself.

Studied about overfitting and underfitting: https://www.kaggle.com/dansbecker/underfitting-and-overfitting

Read about batch and epoch which i came across while training in colab.
https://machinelearningmastery.com/difference-between-a-batch-and-an-epoch/

Images are annotated in roboflow and then trained using google colab .
Colab link : https://colab.research.google.com/drive/1D4X949Ol3LDQtj2mfZPuKesR4k1fjZho

This model doesn't works fine so first tried to implement on just two classes in colab.
Colab : https://colab.research.google.com/drive/1Kc7u6SNvIc5D4ZyjjK_d5IMSGe3a-3yA


