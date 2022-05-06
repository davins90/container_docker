# Info

The goal of this image is to create a Jupyter environment useful to perform analysis related to the world of data science and (eventually) build a web app using the framework proposed by Streamlit

Repo containing files useful to launch a docker image with two containers inside. These are:
- container 1: jupyter lab based on data science e python 3.9.2 images --> porta:8080
- container 2: demo streamlit --> porta:8501

# Comandi
- docker-compose build = builds the image for the first time by installing the libraries. Use it on every first launch 
- docker-compose up = turn on the image 
- docker-compose down = turn off the image.

## Notes
The name of the streamlit application **must** be "app.py". How to create empty python file inside docker-compose?!

Aggiornamento: 06/05/22