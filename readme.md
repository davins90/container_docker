# Info

The goal of this image is to create a Jupyter environment useful to perform analysis related to the world of data science and (eventually) build a web app using the framework proposed by Streamlit

Repo containing files useful to launch a docker image with two containers inside. These are:
- container 1: jupyter lab based on data science e python 3.9.2 images --> porta:8080
- container 2: demo streamlit --> porta:8501

# Comandi
- docker-compose up -d --build = builds the image for the first time by installing the libraries. Use it on first launch and every time the requirements file is changed.
- docker-compose up = upload the image (if no changes have been made to the other files)
- docker-compose down = turn off the image.

## Notes
The name of the streamlit application **must** be "app.py".

Aggiornamento: 15/3/22