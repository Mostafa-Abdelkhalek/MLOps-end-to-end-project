FROM jupyter/pyspark-notebook:spark-3.4.0 
WORKDIR /deploy/
COPY requirements.txt /deploy/
RUN pip install -r requirements.txt
COPY . .
EXPOSE 5000
CMD ["python","app.py"] 

