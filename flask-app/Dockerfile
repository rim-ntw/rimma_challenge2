#Use Python Image
FROM python:3.7

#Install apt dependencies
WORKDIR /flask-app

# Copy contents into image
COPY app.py .
 
# run pip dependencies
RUN pip install Flask
 
# Expose correct port
EXPOSE 5000

# Create an entrypoint
ENTRYPOINT ["python", "app.py"]
