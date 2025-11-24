# BackendKPI-Lab1

## Local run:
`flask --app app:app run --host 0.0.0.0 --port 8080`

## Docker run:
```
docker build . -t lab1:latest
docker run -it --rm --network=host -e PORT=8080 lab1:latest 
```

or using docker-compose

```
docker-compose build
docker-compose up
```

## Endpoint:

/healthcheck