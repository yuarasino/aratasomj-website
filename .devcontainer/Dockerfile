FROM mcr.microsoft.com/devcontainers/python:0-3

ENV \
  LANG=C.UTF-8 \
  TZ=Asia/Tokyo

ENV \
  NPM_CONFIG_UPDATE_NOTIFIER=false \
  WATCHPACK_POLLING=true

ENV \
  PYTHONDONTWRITEBYTECODE=1 \
  PYTHONUNBUFFERED=1 \
  PIP_DISABLE_PIP_VERSION_CHECK=on \
  POETRY_VIRTUALENVS_IN_PROJECT=true

RUN \
  pipx install poetry && \
  poetry self add poethepoet[poetry_plugin]
