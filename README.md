# FACE PAY: Pay with a Smile:)
Welcome to our payment app, the most innovative and secure way to make transactions on the go! Our app uses facial recognition technology to provide you with a seamless and efficient payment experience. With just a quick scan of your face, you can easily and securely make purchases at any participating merchant. Our advanced security measures ensure that your personal information and payment data are always protected. Say goodbye to the hassle of carrying cash or cards and hello to the future of payment technology with our app.

# TECHNOLOGY STACK AND DOCUMENTATION
This project is possible with:
•	Frontend: HTML, CSS, Bootstrap
•	Backend: Vanilla JavaScript, Node.js (Express)
•	Storing and Managing Data : Google Firebase
•	Machine Learning: face-api.js



# MACHINE LEARNING MODELS USED:-
•	Face-api.js
JavaScript API for face detection and face recognition in the browser implemented on top of the tensorflow.js core API (tensorflow/tfjs-core)
•	Face Detection
This application is using SSD (Single Shot Multibox Detector) based on Mobilenet V1 neural network for face detection. Such a network is trained to generate a very accurate and almost unique 68 points face-landmark detection vector, given that, the images of faces which are fed to the network are properly aligned and cropped.
•	Face Recognition
Then, for face recognition, a ResNet-34 like architecture is implemented to compute a face descriptor (a feature vector with 128 values) from any given face image, which is used to describe the characteristics of a person's face. It can determine the similarity of two arbitrary faces by comparing their face descriptors using Euclidean Distance or any other classifier.
# STEPS TO BE DONE TO COMPLETE THE PROCESS:-
1. Before using you need to register in the application by clicking the `Sign Up` button. And, then login.
2. Now, upload your profile picture. You can navigate there by clicking the round-shaped image aside of Log Out button.
2. Select the transaction type and fill the transaction details. Click the `Next` button.
3. The application will start loading the camera and the ML models.
4. Click `Start Verification` to verify and authenticate yourself.
5. If you were verified successfully then you will be ask for initiating payment. Click `Pay` button to initiate. Now, you will be seeing the SUCCESS message on the screen.
6. If you were not verified, the application will reject the payment and you will be seeing the FAILED message on the screen. 
# FACE LANDMARK DETECTION:-

 
# FACIAL EMOTION RECOGNITION:- 

 


