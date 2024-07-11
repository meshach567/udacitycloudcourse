FROM python:3.12.4
LABEL maintainer="Meshach Arinze"

COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt

# command to run on container start
CMD [ "python", "app.py" ]