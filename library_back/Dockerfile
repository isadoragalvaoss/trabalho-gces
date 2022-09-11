FROM python:3
ENV PYTHONUNBUFFERED=1
WORKDIR /docker/gces
COPY ./requirements.txt /docker/gces/
RUN python3 -m venv env
RUN . env/bin/activate
RUN pip install -r ./requirements.txt
COPY . /docker/gces/