FROM registry.access.redhat.com/ubi9/python-312:latest
USER root
COPY requirements.txt /tmp
RUN pip install --no-cache-dir -r /tmp/requirements.txt && rm -f /tmp/requirements.txt
USER 1001
WORKDIR /tmp
