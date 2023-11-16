FROM python:3.8-slim-buster
COPY . /app
WORKDIR /app
RUN pip install -r requirements.txt
ENTRYPOINT [ "python" ]
CMD [ "app.py" ]
ENV PYTHONPATH /usr/src/app/venv/lib/python3.10/site-packages