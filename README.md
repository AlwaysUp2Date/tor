# Docker image for Tor

## About AlwaysUp2Date
AlwaysUp2Date is an organization that creates trusted Docker images for a variety of different programs that don't provide official images. All Docker images from `AlwaysUp2Date` updated automatically (so that you can get your security patches asap) and built directly on Docker Hub servers for maximum trust and transparency. You can verify the exact Dockerfiles that have been used for each build directly on Docker Hub. 

## Examples 

### docker:

```
docker run -p 9150:9150 alwaysup2date/tor
```

### docker-compose:

```
version: '3'
services:
    tor:
        image: alwaysup2date/tor
        ports:
            - '9150:9150'
```
