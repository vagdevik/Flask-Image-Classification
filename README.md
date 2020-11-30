# Flask-Image-Classification

This is a web app built to show the top 3 classes as predicted by a pretrained image classification model which was trained on 1000 image classes.

## How to run this app?

- Download this repo and switch to the directory `Image-Classification-App` using `cd Image-Classification-App`.

- Create a virtual environment and activate it by using the following commands:

```
virtualenv Img-Class-Env

source Img-Class-Env/bin/activate
```

- Install the necessary packages by using: 

```pip install -r requirements.txt```

- Run the web app by executing:

```python app.py```

- Open the link the browser, the app appears to be running.

## Things to Remember:

- The model is trained on 1000 classes. 

- You could use `cat 1000_imagenet_classes_file.txt` to see those 1000 classes.

- When asked to upload an image to predict the class, upload the image of one of the classes mentioned in the `1000_imagenet_classes_file.txt`.
