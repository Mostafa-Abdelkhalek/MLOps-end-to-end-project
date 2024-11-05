FROM python:3.7-slim 
WORKDIR /app/
EXPOSE 8501
COPY requirements.txt /app/
RUN pip install -r requirements.txt
COPY . /app/
CMD ["streamlit","run","webapp.py"] 

