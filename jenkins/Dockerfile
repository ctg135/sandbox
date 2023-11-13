FROM python:3.11-slim

ENV PYTHONDONTWRITEBYTECODE=1

WORKDIR /app
COPY /src /app

COPY requirements.txt .
RUN python -m pip install -r requirements.txt

# команда, выполняемая при запуске контейнера
CMD [ "python", "/app/main.py" ]