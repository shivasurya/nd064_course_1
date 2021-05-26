FROM python:2.7
WORKDIR /app
COPY ./techtrends .
EXPOSE 3111
RUN pip install -r requirements.txt
RUN python init_db.py
CMD ["python", "app.py"]
