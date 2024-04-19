# sem03-v24
Filer for Seminar III i IS-105 våren 2024 ved UiA.

Ser på Docker Compose V2. 

docker compose 
docker-compose

services:
  webjteneste:
    image: nginx
    port:
      - "8080:80"
    restart: always
