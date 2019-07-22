## Private Docker Repository ##
---

To build the Image.

```docker
docker-compose build
```

To run the cointainer use

```docker
docker-compose up
```
---

## How it works

### Repository sits on port 5000 
### The UI image browser sits on port 8080

To pull image

```Docker
docker pull hostUrl/fromUser/imagename:tag
```

To push image

```Docker
docker push hostUrl/fromUser/imagename:tag
```

To tag your local image

```docker
docker tag localimage:tag hostUrl/fromUser/imagename:tag
```
