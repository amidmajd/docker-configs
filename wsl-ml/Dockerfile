FROM nvcr.io/nvidia/pytorch:23.01-py3

WORKDIR /src

COPY ./requirements.txt requirements.txt
RUN pip install -r requirements.txt

EXPOSE 8888

ENTRYPOINT ["jupyter", "lab", "--ip=0.0.0.0", "--allow-root", "--no-browser", "--NotebookApp.token='token'"]
