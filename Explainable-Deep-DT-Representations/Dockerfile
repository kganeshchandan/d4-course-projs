FROM python:3.7

WORKDIR /d4
COPY . /d4

RUN pip install -r requirements.txt
RUN chmod +x /d4/entrypoint.sh

ENTRYPOINT /d4/entrypoint.sh
