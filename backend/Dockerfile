FROM python:3.10-slim

# Define label
LABEL maintainer="NamNT"

# Define workdir
WORKDIR /learn_deploy

COPY requirements.txt /learn_deploy/requirements.txt

COPY . /learn_deploy/


RUN apt-get update -y
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8000

ENTRYPOINT ["uvicorn"]
CMD ["main:app", "--host", "0.0.0.0", "--port", "8000" ,"--reload"]