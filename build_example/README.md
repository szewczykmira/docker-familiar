To run build:
```sh
cd node-bulletin-board/bulletin-board-app
docker build --tag bulletin:latest .
```

Run image as a container:
```sh
cd node-bulletin-board/bulletin-board-app
docker run --publish 8000:8080 --detach --name bb bulletin:latest
```