## Follow Below instructions



# build the image
docker build -t go-helloworld .

# run the image
docker run -d -p 5000:6111 go-helloworld

# tag the image
docker tag go-helloworld kelly/go-helloworld:v1.0.0

# push the image
docker push kelly/go-helloworld:v1.0.0

# login into DockerHub
docker login
