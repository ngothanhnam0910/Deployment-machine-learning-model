FROM python:3.10-slim

# Define label
LABEL maintainer="NamNT"

# Define workdir
WORKDIR /learn_deploy

# Copy file requirement and source code
COPY requirements.txt /learn_deploy/requirements.txt
COPY . /learn_deploy/

# Install library
RUN apt-get update -y
RUN pip install --no-cache-dir -r requirements.txt

EXPOSE 8501

ENTRYPOINT ["streamlit","run"]

CMD ["streamlit_app.py"]