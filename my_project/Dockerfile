FROM python:3.9.13-alpine3.15

WORKDIR /mydir

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY . /mydir

EXPOSE 8000

CMD ["python" , "manage.py", "runserver", "0.0.0.0:8000"]