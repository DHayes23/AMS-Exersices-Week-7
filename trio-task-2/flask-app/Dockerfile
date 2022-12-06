#Use Python 3.6 as a base image
FROM python:latest
WORKDIR /app
# Copy contents into image
COPY app.py .
COPY requirements.txt .
# install pip dependencies from requirements file
RUN pip install -r requirements.txt
# Expose correct port
EXPOSE 
# Create an entrypoint
ENTRYPOINT ["python", "app.py"]