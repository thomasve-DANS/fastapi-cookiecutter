FROM thomasve/fastapi-cookiecutter-base:3.9

WORKDIR {{cookiecutter.application_folder_name}}
COPY {{cookiecutter.application_folder_name}}/ .
COPY pyproject.toml ./stub.toml

EXPOSE 7070
RUN pip install uvicorn
