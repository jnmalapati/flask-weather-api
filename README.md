
###Build Docker Image
`docker build . -t flask-api`


###Running the Application
`docker run -dit --rm -p 5000:5000 --name flask-api flask-api:latest`


###OR Run 
`docker-compose up --build`# flask-weather-api
