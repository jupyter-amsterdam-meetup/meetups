FROM python:3.6
ADD . /
RUN apt update && apt-get install -y apt-utils
RUN apt install graphviz -y
RUN pip install -r requirements.txt
WORKDIR /tutorial
CMD jupyter notebook --ip=0.0.0.0 --port 8888 --allow-root --NotebookApp.token='' --NotebookApp.password=''