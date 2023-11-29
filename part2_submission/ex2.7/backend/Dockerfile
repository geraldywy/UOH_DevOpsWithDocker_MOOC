FROM python:3.13.0a2-slim

WORKDIR /src

COPY . .

RUN pip install --upgrade pip

RUN pip install --trusted-host pypi.python.org -r requirements.txt

CMD ["python", "-u", "app.py"]
