- https://fullstackopen.com/en/part12/building_and_configuring_environments
- docker container list -a
- docker container cp ./index.js ./index.js
- docker container run -it --name hello-node node:20 bash   
- docker container -rm `containerID`


- docker image list -a

- docker run -it `imagename`
- docker run -p 3132:3000 `imagename`
- docker kill `containerid`

- docker build -t `imagename`


## Can put commands above in docker-compose.yml
- docker compose up --build -d
- docker compose down