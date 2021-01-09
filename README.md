# Checkout

## Requirements
* Docker

## Setup steps
#### Build the docker image
```
docker build -t checkout .
```

#### Run the image exposing a port
```
docker run --name checkout -d -p 8080:80 checkout
```

## Dev tools
```
if you are using VSCode please install the following extension: stylelint
```