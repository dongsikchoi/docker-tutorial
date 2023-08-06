# docker-tutorial

- pip install fastapi
- pip install uvicorn==0.23.1
</br>

- docker build -t fastapi-image .
- docker run --name fastapi-container -p 80:80 fastapi-image
- docker images
- docker ps -a
- docker run --name fastapi-container -p 80:80 -d -v ${pwd}:/code fastapi-image  | *windows*
