# SwiftMLExploration
Arman Siddiqui

# Sources/Help:
- [Apple - CreateML](https://developer.apple.com/documentation/createml/creating-an-image-classifier-model)
- [Apple - CoreML](https://developer.apple.com/documentation/coreml)
- [Apple - Vision](https://developer.apple.com/documentation/vision)
- [Apple - Swift](https://developer.apple.com/swift/)
- [Apple - Recognize Objects in Live Capture](https://developer.apple.com/documentation/vision/recognizing_objects_in_live_capture)
- [Apple - Classifying Images with Vision and Core ML](https://developer.apple.com/documentation/vision/classifying_images_with_vision_and_core_ml)
- [AppConda - Swift Tutorial](https://www.appcoda.com/learnuikit/build-your-first-app.html)
- [Create with Swift - Object Detection Maching Learning Model in an iOS App](https://www.createwithswift.com/tutorial-core-ml-using-an-object-detection-machine-learning-model-in-an-ios-app/)

# Final Goal:
The goal of this assignment was to explore the use of Swift and its machine learning capabilities. This included the use of the CreateML, CoreML, and Vision frameworks. The goal of this assignment was to create a machine learning model that would be able to classify images. This would be done by using the CreateML framework to create a model that would be able to classify the images. Once the model was created, it would be used in an iOS app for said classification. The app would be able to classify the images in real time and display the results on the screen.

## Original Goal:
Develope a BERT question answering model that would be able to answer questions based on a given passage. This would be done by using the BERT model and the HuggingFace library. The model would be trained on the SQuAD dataset and then used to answer questions based on the given passage. The model would be able to answer questions based on the passage and display the results on the screen. However this did end up being the final project goal due to technical challenges.

## 2nd Goal:
Develop a machine learning model to find and classifiy Arman's face versus the faces of others within a still image. This would be done by using the CreateML framework to create a model that would be able to classify the images. Once the model was created, it would be used in an iOS app for said classification. The app would be able to classify the images taken from the camera and display the results as a window on the screen. This did not end up becoming the final goal due to too much inherent bias in the model. The model was not able to classify Arman's face versus the faces of others and instead said that everyone was Arman.

# Projects Present:
- ClassifyingImagesWithVisionAndCoreML - This project was a boiler plate app from Apple that allowed the use of the ImageNet model to classify images taken with the iphone camera of from the iphone photo library. This was used as a starting point for the final project where the ArmanNotArman model was then tried and without success. Please find this project linked at my public folder [here](https://1drv.ms/u/s!Al15pC5iYlRmhNYu-jlD_vy3_pQj5g?e=U6zhMM). Due to the size I was not able to upload the project to GitHub. I will try to fix this is time provides.
- RecognizingObjectsInLiveCapture - THis project was a boiler plate app from Apple that allowed for the use of a machine learning model to classify fruits in real time. This was used as a starting point for the final project where the ArmanNotArman model was then tried once more and without success due to the nature of the model being an image classification model as opposed to a full neural network as the boiler plate app used. Please find this project linked at my public folder [here](https://1drv.ms/u/s!Al15pC5iYlRmhNYu-jlD_vy3_pQj5g?e=U6zhMM). Due to the size I was not able to upload the project to GitHub. I will try to fix this is time provides.

# CreateML Machine Learning Model:
To create your very own machine learning model use with these boiler plate apps above, all you need is a Mac with CreateML installed. I followed the link found [here](https://developer.apple.com/documentation/createml/creating-an-image-classifier-model) to get started. You'll notice that for this tutorial, it is found within the greater CreateML documentation linked in the Sources section. Following this tutorial allowed me to explore the ease of creating advanced machine learning models with no coding needed. For a similar result via coding, the work being done would have been far greater. The tutorial is very easy to follow and the results are very impressive. The model created was able to classify images of Arman versus not Arman with a ~80% accuracy. This was done with only 20 images of Arman and 20 images of not Arman. This is a very impressive result and shows the power of machine learning. The model was then used in the boiler plate apps to classify images of Arman versus not Arman. The results here were not as impressive as the ~80% accuracy of the model. The results were more like ~50% accurate at best. This was due to the inherent bias in the model. The model was not able to classify Arman's face versus the faces of others and instead said that everyone was Arman. I highly encourage you to view the YouTube video found [here](https://www.youtube.com/watch?v=-xXgYEuLU7c) explaining the process of creating the model and the results of the model. The video is very informative and lots of time was spent on it to ensure that it was as informative as possible. I opted to use a video based format to interact with the audience as opposed to a written format. I believe that the video format is more engaging and allows for a more in depth explanation of the process. The video is also a great way to show the results of the model and the results of the boiler plate apps. I highly encourage you to view the video and I hope that you enjoy it.

# Accomplishments:
1. A model was built using the CreateML framework that was able to classify images of Arman versus not Arman with a ~80% accuracy.
2. An iOS app was used as a boiler plate to create a simple app that would be able to classify images based on the model passed into it.
3. The goal to explore app development in Swift was accomplished in addition to exploring the ease of use when it comes to integrating machine learning models into Swift.
4. The goal to understand the start to finish of integrating different proprietary frameworks into a project was accomplished. This included the use of the CreateML, CoreML, and Vision frameworks.

# Future Steps:
1. Return to the machine learning development and attempt to correct the inherent bias in the model. This would help to improve the accuracy of the model and allow for the model to be used in a more practical manner as opposed to just for specific images. 
2. Continue to explore the use of Swift and its machine learning capabilities. This would include the use of the CreateML, CoreML, and Vision frameworks. 
3. Attempt to begin building my own app outside of the boiler plate app approach taken. This would allow for a more in depth understanding of the app development process and the use of Swift. It's important to note that Swift is not a small programming language and to learn it, it would be best to start with a simple app and then build from there as opposed to attempting to jump the gun and build a complex app from the start as done with this project.