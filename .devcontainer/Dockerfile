ARG VARIANT=3.13
FROM mcr.microsoft.com/devcontainers/python:${VARIANT}

RUN pip3 install poetry pre-commit
RUN poetry config virtualenvs.in-project true
