FROM python:3.14-rc-alpine3.20
WORKDIR /root
COPY train.py /root/train.py
COPY requirements.txt /root/requirements.txt
RUN pip install -r /root/requirements.txt
ENTRYPOINT ["python", "train.py"]