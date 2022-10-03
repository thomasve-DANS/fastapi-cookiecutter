FROM python:3.9-slim

WORKDIR {{cookiecutter.application_folder_name}}

RUN pip install poetry

COPY pyproject.toml .

RUN poetry config virtualenvs.create false

RUN poetry install

EXPOSE {{cookiecutter.port}}

RUN pip install uvicorn
