# CPUsimulator
CPU Simulator, Progra3 project 

pipenv install --ignore-pipfile

docker run -it --network="host" 

docker run -it --network="host" cpusimulator:0.0

docker run -it -p 5000:5000 cpusimulator:0.0
docker run --name web -d -p 5001:80 webcpu:0.0
docker run -it -d -p 5001:80 webcpu:0.0

docker-compose up -d
docker-compose down -v

docker ps

docker-compose up --build