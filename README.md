# Classification of Covid19 using X-ray Images in Keras

View the notebook online: 
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/mihaijulien/covid19/blob/main/Covid19_detection_using_X_ray_images.ipynb)

An image classifier using a CNN to differentiate between chest x rays images with a COVID 19 infections versus without. The dataset contains the lungs X-ray images of both groups.

![dataset](dataset.png)

## Run

With **[Docker](https://www.docker.com)**, you can quickly build and run the entire application in minutes :whale:

```shell
# 1. First, clone the repo
$ git clone https://github.com/mihaijulien/covid19.git
$ cd covid19

# 2. Build Docker image
$ docker build -t covid19 .

# 3. Run!
$ docker run -it --rm -p 5000:5000 covid19
```
Open http://localhost:5000 and wait till the webpage is loaded.

See [keras-flask-deploy-webapp ](https://github.com/mtobeiyf/keras-flask-deploy-webapp)
