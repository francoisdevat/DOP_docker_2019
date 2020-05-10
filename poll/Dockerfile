FROM python:latest
RUN mkdir -p /app
WORKDIR /app
COPY . /app/
RUN pip install -rrequirements.txt
CMD [ "flask", "run", "--host=0.0.0.0", "--port=80" ]
