# WebCam_transfer_learning
Make a classification through MobileNet

This is a custom image classifier that you can train on the fly in the browser using tensorFlow.js, a powerful and flexible machine learning library for Javascript.
We'll use a module called a "K-Nearest Neighbors Classifier", which effectively lets us put webcam images (actually, their MobileNet activations) into different categories (or "classes"), and when the user asks to make a prediction we simply choose the class that has the most similar activation to the one we are making a prediction for. <br/>
<br/>
Good Example of a technique called <b>"transfer learning"</b> , which bootstraps our training with the pre-trained MobileNet model and customizes it to train for your application.

```
$ git - clone this repo
$ run index.html file in your browser
```
