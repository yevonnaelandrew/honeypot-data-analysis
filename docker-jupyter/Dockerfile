# Use the specific Jupyter scipy-notebook image as the base
FROM jupyter/scipy-notebook:2023-08-03

# Dependencies
USER root

RUN apt-get update

USER jovyan

# If you have additional steps such as installing more packages or copying files, you can add them here.
# Example: 
# COPY ./some_local_directory_or_file /path/in/container/
# RUN pip install some_additional_package
RUN pip install pymongo
RUN pip install wordcloud
RUN pip install bashlex==0.15
RUN pip install joblib>=1.1.1
RUN pip install threadpoolctl==2.2.0
