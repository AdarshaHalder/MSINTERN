# MSINTERN
ITS FACE RECOGNITION BASED PROJECT WHICH IS MADE BY JS,NODE.ITS HAVE MULTIPLE OPTION TO DETECT FACE.IT CAN BE USED FOR SECURITY PURPOSE.HERE I AM USING FACE-API.JS API.ITS HAVE SO MANY OPTION. 


Running the Nodejs Examples------- 
cd examples/examples-browser
npm install
npm start 



face-api.js for the Browser Simply include the latest script from dist/face-api.js.  Or install it via npm:  npm i face-api.js  Loading the Models All global neural network instances are exported via faceapi.nets:  console.log(faceapi.nets) // ageGenderNet // faceExpressionNet // faceLandmark68Net // faceLandmark68TinyNet // faceRecognitionNet // ssdMobilenetv1 // tinyFaceDetector // tinyYolov2  Face Expression Recognition Model The face expression recognition model is lightweight, fast and provides reasonable accuracy. The model has a size of roughly 310kb and it employs depthwise separable convolutions and densely connected blocks. It has been trained on a variety of images from publicly available datasets as well as images scraped from the web. Note, that wearing glasses might decrease the accuracy of the prediction results.  





Test results for each database The - indicates, that there are no gender labels available for these databases.  Database UTK FGNET Chalearn Wiki IMDB* CACD* MegaAge MegaAge-Asian MAE 5.25 4.23 6.24 6.54 3.63 3.20 6.23 4.21 Gender Accuracy 0.93 - 0.94 0.95 - 0.97 - - Test results for different age category groups Age Range 0 - 3 4 - 8 9 - 18 19 - 28 29 - 40 41 - 60 60 - 80 80+ MAE 1.52 3.06 4.82 4.99 5.43 4.94 6.17 9.91 Gender Accuracy 0.69 0.80 0.88 0.96 0.97 0.97 0.96 0.9
