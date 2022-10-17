# Cookiecutter for FastAPI Docker container

A simple cookiecutter to allow for fast development of FastAPI based containers. FastAPI documentation: https://fastapi.tiangolo.com/

# How to use

1. Install cookiecutter (`pip install cookiecutter`)
2. `cookiecutter https://github.com/thomasve-DANS/fastapi-cookiecutter`
3. Fill in variables
4. You now have a set up version that will build to a FastAPI container.

To make your project:

- Add dependencies to container using Makefile
- Perform your function in `main.py` file.
- Enjoy as your stuff builds to a Docker file on pipeline.

# Testing

Testing can be done with Pytest; requests is also installed.

# Pipeline

A pipeline is included, disabled by default. Instructions for enabling this are in the pipeline file; this runs Pytest to cover your test cases and builds into a Docker image.
