FROM python:3.7

WORKDIR /src
COPY . .
RUN pip install -r requirements.txt --no-cache-dir
RUN chmod +x /src/server.py
CMD ["/src/server.py"]