FROM ubuntu

WORKDIR opt/testProject
RUN apt-get update -y
RUN apt-get install -y \
    python2.7 \
    python-bs4

COPY . .
RUN chmod +x weeman.py
CMD ["python", "weeman.py"]

