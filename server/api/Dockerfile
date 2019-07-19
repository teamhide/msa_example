FROM python:3.7.3

COPY . /home
WORKDIR /home
RUN pip install pipenv
RUN pipenv install --system
EXPOSE 8000
CMD python3 /home/main.py