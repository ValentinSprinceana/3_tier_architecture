FROM python:3.6
WORKDIR /app
COPY requirements.txt ./
COPY back.py ./
RUN pip install -r requirements.txt
EXPOSE 3000
CMD python back.py
