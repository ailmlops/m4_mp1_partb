FROM python:3.10
ADD . .
RUN pip install --upgrade pip
RUN pip install -r requirements.txt
RUN pip install bikeshare_model
#CMD ["python", "bikeshare_model/train_pipeline.py"]
RUN pip install fastapi uvicorn
EXPOSE 8001
CMD ["python", "app/main.py"]