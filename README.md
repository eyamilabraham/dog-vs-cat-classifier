# dog-vs-cat-classifier

- This source code is used as a dog and cat classifier applying Python and TensorFlow.


# Image classification (dogs and cats)

- This code represents the website, once the artificial intelligence model is created and trained with Python and Tensorflow, which is exported to "json" and "bin" files. It can be used on the smartphone, just focus on your smarthpone's camera at the dog or cat you want to classify (it can be a computer image, a photo, or a real one), it does it all in the browser using Tensorflow.js.

# Want to try it on your own? 

- This project uses a Tensorflow.js model, which to load requires access via http/https. For that you can use any server, but here is a way to do it:

  1. Download Python to your computer
  2. Open a command line or terminal
  3. Navigate to the folder where you downloaded the repository
  4. Run the command python -m http.server 8000
  5. Open a browser and go to http://localhost:8000


# How to test it from the smarthphone?

- If you want to open it on your smartphone, you can't just put your computer's local IP and port, since HTTPS is required to use the smartphone's camera. You can create an HTTPS tunnel by following these steps:

  1. Download ngrok to your computer, and unzip it
  2. Open a command line or terminal
  3. Navigate to the folder where you downloaded ngrok
  4. Run the command ngrok http 8000
  5. It is important to have both active: The python server, and the ngrok tunnel
  6. An HTTPS link will appear in the command line. You can log in there with your smartphone, it doesn't matter if you are not on the local network
  7. The tunnel expires aprroximately 2 hours after it has been started, in that case just restart ngrok
  8. Open a browser on your smartphone and go to the HTTPS link indicated

# APP

- You can click on the "Change camera" button to use the front or rear camera of your phone. Just focus on the camera at a dog or cat, and the prediction will appear below. It's not the future sorter either so if it doesn't sort perfect, oops.
