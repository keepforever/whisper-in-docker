# Whisper-API-in-Docker-Container

Whisper API built using FastAPI inside a Docker container.

## How to run

```bash
docker build -t whisper-api .docker build -t whisper-api .
```

```bash
docker run -p 8000:8000 whisper-api
```

## download a youtube video audio

```bash
yt-dlp -x --audio-format mp3 https://youtu.be/ILvNG1STUZU?si=uJGAW-_40ypnXiba
```
