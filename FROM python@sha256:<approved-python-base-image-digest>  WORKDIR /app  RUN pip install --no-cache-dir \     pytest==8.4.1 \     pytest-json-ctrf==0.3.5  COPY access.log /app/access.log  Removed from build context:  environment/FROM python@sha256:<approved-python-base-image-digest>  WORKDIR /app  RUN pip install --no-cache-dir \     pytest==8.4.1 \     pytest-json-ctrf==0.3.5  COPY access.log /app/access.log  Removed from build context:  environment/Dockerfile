FROM python@sha256:<approved-python-base-image-digest>

WORKDIR /app

RUN pip install --no-cache-dir \
    pytest==8.4.1 \
    pytest-json-ctrf==0.3.5

COPY access.log /app/access.log

Removed from build context:

environment/solution_hint.py
