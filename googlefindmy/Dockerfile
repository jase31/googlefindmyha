FROM ghcr.io/txitxo0/googlefindmytools-homeassistant:latest
WORKDIR /app
COPY publish_mqtt.py .
COPY auth/ ./auth/
CMD ["python", "publish_mqtt.py"]
