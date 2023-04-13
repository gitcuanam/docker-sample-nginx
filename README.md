# docker-sample-nginx
a sample nginx container to display container name

# build the image
```bash
docker build -t sample-nginx .
```
# run container
```bash
docker run -d -p 80:80 --name sample-nginx sample-nginx
```