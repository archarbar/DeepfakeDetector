# DeepfakeDetector

Have you ever been on https://www.thispersondoesnotexist.com/? Yes. That's right. That image is not a real person. How is it possible to detect such deepfake pictures, where even us real humans can't distiguish them? Well, lucky for us, this app can! Simply upload an image and this web app will tell you if the image is real or fake.

## Prerequisites

Install necessary python packages

`pip install -r requirements.txt`

## Running the Flask Application 

Run the **app.py** file from the **root** directory. 

`python app.py` 

Go to **localhost:5000** to access the application from the browser of your choice.

## Structure of the repository

```
├── README.md
├── app.py                      # Main code to run the flask app
├── predictor.py                # Contains the predictor class
├── model
│   ├── model.json              # Contains the model in json format
│   ├── model.h5                # Contains the model weights
│   └── DeepfakeDetector.ipynb  # Cntains the complete Jupyter notebook for training and saving the model
├── requirements.txt            # File containing packages needed to run the code
├── static
│   ├── css
│   │   └── main.css            # Style sheet to make the front-end prettier
│   └── js
│       └── main.js             # Javascript file handling front-end actions
└── templates
    └── index.html              # HTML file that Flask renders
```
