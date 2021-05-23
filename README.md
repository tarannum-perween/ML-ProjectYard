# Android app with Deep Learning Model

- This is a deployment of Keras model on android app.

- In the first step, we have to make a model like in this model we have created a cat dog classifier using deep Learning.

- In the Second step, we used **TensorFlow Lite converter** The TensorFlow Lite converter takes a TensorFlow model and generates a TensorFlow Lite model (an optimized [FlatBuffer](https://google.github.io/flatbuffers/) format identified by the `.tflite` file extension). You have the following two options for using the converter:

1. [Python API](https://www.tensorflow.org/lite/convert/#python_api) (***recommended\***): This makes it easier to convert models as part of the model development pipeline, apply optimizations, add metadata and has many more features.
2. [Command line](https://www.tensorflow.org/lite/convert/#cmdline): This only supports basic model conversion.

- After all these steps we will create a new project in [Android Studio](https://developer.android.com/studio?gclid=CjwKCAjw-qeFBhAsEiwA2G7NlzoCrCsoRNbFr__OUJ7J0zVRQ95jMWl0NdIE3jCxwzmIK5RyZCbV8xoCvxQQAvD_BwE&gclsrc=aw.ds#downloads) and the language we are going to use in Java.

- As the project open you'll get two files **activity_main.xml** and **MainActivity.java**. In simple words activity_main.xml is GUI part and the MainActivity.java is backend part.

Now, Make the GUI then then write code in the MainActivity.java.

*Tips:* *If you are getting red error in writing the code then press alt + enter to get rid of it.*

**official tf guide to convert model to tflite model** : https://www.tensorflow.org/lite/convert/

- In the Last step, after writing the code  try to run it using the play button present on the upper right side of the screen.

*Note: If you can't connect to the virtual device then can connect your device through usb cable and then after downloading the app You can run it.*
