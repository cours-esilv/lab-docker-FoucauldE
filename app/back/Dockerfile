FROM python:3.11-bookworm

WORKDIR /app

COPY . /app

# During the build time of the Docker image
RUN pip install -r requirements.txt

EXPOSE 5000

# During run time (ie when starting the Flask app)
CMD python3 -m flask run --host=0.0.0.0