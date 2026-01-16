#crear un entorno donde podamos correrlo con uv
FROM python 
COPY --from=ghcr.io/astral-sh/uv:latest /uv /bin/

VOLUME /code
WORKDIR /code
# ENTRYPOINT ["python", "pipeline.py", "emi"]