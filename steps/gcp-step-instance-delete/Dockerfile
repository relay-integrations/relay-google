FROM relaysh/core:latest-python
RUN pip --no-cache-dir install google-api-python-client
COPY "./step.py" "/step.py"
ENTRYPOINT []
CMD ["python3", "/step.py"]

LABEL "org.opencontainers.image.title"="Delete GCP instances"
LABEL "org.opencontainers.image.description"="This task deletes instances in GCP"
LABEL "com.puppet.nebula.sdk.version"="v1"
