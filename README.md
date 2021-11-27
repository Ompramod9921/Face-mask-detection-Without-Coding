
# Face mask detection Without Coding

Google Teachable Machine is Google’s free no-code deep learning model creation web platform. You can build models to classify images, audios or even poses. After doing the same, you can download the trained model and use it for your applications.

It is very intuitive and does a really good job.The magic behind Teachable Machine is based on a popular deep learning technique called transfer learning.

[![SC2 Video](https://i.postimg.cc/rFhNd5gk/downloadmm.jpg)](https://youtu.be/T2qQGqZxkD0)

In this article, I’m going to walk you through making a no code machine learning model to detect face mask using Google Teachable Machine. It is a basic image classification problem.

Let us take a tour of it. Go to https://teachablemachine.withgoogle.com/ .It would look something like this:

![App Screenshot](https://i.postimg.cc/nrXSrT7C/Whats-App-Image-2021-11-27-at-12-18-24-PM.jpg)

Click on Get Started. In-order to create a new project we have three options i.e. Image Project, Audio Project, or Pose Project.

![App Screenshot](https://i.postimg.cc/MGRQ6Bvq/Whats-App-Image-2021-11-27-at-12-24-36-PM.jpg)

For now, pick “Image Project” since we are dealing with image classification. After clicking on Image Project, the below web page will be displayed.

![App Screenshot](https://i.postimg.cc/rybMJPfZ/Whats-App-Image-2021-11-27-at-12-29-10-PM.jpg)

There are three steps involved in training a model with Teachable Machine at a high level – gathering the samples, training the model, testing, and improving the model.

To start training the machine, we first have to create different categories, or classes, to teach it with. I’m going to make two classes here. Rename “Class 1” and “Class 2” to “mask” and “no mask" .

![App Screenshot](https://i.postimg.cc/5t0fpWWG/Whats-App-Image-2021-11-27-at-1-01-37-PM.jpg)

Now that I have my classes, I’m going to give each class samples to learn from. So will be adding the dataset to the respective classes.
We will be making a face mask classifier of our own. Gathering the sample feeds the algorithm with enough data for the training.

Next, turn on your webcam for each class and click “Hold to Record” until you have a few hundred image samples recorded. You want to take as many pictures and capture as many angles, positions, etc. as you possibly can. The more data you have, the better your model will learn the difference between the two sets of data.
Machine learning is as good as the data input. For this reason, upload as many images per class as possible

Try to record the photos of the head poses from different depths and positions with respect to the camera so that you don’t overfit the data which will later lead to poor predictions.
Be certain that the images and class names correspond and are correct.

You can also upload the images to the respective class from your local device.

![App Screenshot](https://i.postimg.cc/KvGc4Msx/Whats-App-Image-2021-11-27-at-1-14-10-PM.jpg)

Once you feel you’ve recorded enough samples, click on “Train Model”. Teachable Machine will train a model based on the examples you provided. There is no need to do any smoothing or pre-processing.

![App Screenshot](https://i.postimg.cc/V6fZXzyr/Whats-App-Image-2021-11-27-at-1-19-34-PM.jpg)

After successfully training the model, we can test the model from the preview pane. In the preview pane, there are two options to predict the image class like by using the file or a webcam.

So in this example, we will choose as a file and try to make the predictions.
Now testing how good the model really is.
We can set the input to be off if we don’t want it to predict from the live webcam.

Default webcam input is on. You can also add an image for it to predict.
Change the option from webcam to file in the drop-down list.
Here’s what mine looks like:

![App Screenshot](https://i.postimg.cc/NFh4ptSk/Whats-App-Image-2021-11-27-at-1-35-10-PM.jpg)

As we can see in the above figures model is performing very well
Play with your model on the site to see how it performs. Not to your liking? Tweak the examples and see how it does.

We can also export our trained model for our projects: websites, Application, and more. We can download our trained model or host it online for free from this.
Click on Export Model to download the model or generate a shareable public link for the model.
You can also save your project to Google Drive so you can pick up where you left off.

![App Screenshot](https://i.postimg.cc/dDPxkrJv/Whats-App-Image-2021-11-27-at-1-39-34-PM.jpg)

As shown in the above image there are main three options like Tensorflow.js, Tensorflow, and Tensorflow Lite. So we can export or download our model based on our requirements.
For example, I exported this model and made this website that detects face mask on Glitch. You can try out if you like...

https://grateful-sweltering-scent.glitch.me/

Ready to dive in?
You have now developed a skill in image classification. This is vital in any role that involves the development of computer vision-based applications or services. 

To further build on this guide, explore Teachable Machine for audio and pose classification.

In this way, one can easily develop machine learning and deep learning supervised models using Google’s Teachable Machine.
