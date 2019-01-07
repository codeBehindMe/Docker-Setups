from tensorflow/tensorflow:latest-gpu-py3
RUN apt-get update && apt-get install -y libsm6 libxext6 libxrender-dev 
RUN pip install --trusted-host pypi.python.org -r requirements.txt
EXPOSE 8888
