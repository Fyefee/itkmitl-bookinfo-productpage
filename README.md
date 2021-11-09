# How to run product page

## Prerequisite

* Python 3.8

```bash
pip install -r requirements.txt
python productpage.py 9080
```

## How to run with Docker

```bash
# Build Docker Image for product page
docker build -t productpage .

# Run product page service on port 8081
docker run -d --name productpage -p 8083:8083 productpage
```

## How to run with Docker Compose

```bash
docker-compose up -d
```

``` 
You can test with path '/' or '/index.html'
```

## How to run with Kubernetes

```bash
# Create deployment resource
kubectl apply -f k8s/
```
