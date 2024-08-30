# docker-application-template

## Build and push your Docker image
This step will walk you through building and pushing your Docker image to your container registry. This is useful to building custom images for your use case.

1. Clone the [docker-application-template](https://github.com/swanchain/docker-application-template):
```
git clone https://github.com/swanchain/docker-application-template.git
```
2. Navigate to the root of the cloned repo:
```
cd docker-application-template
```
3. Build the Docker image (example: filswan/helloworld:v1.0):
```
docker build --platform linux/amd64 --tag <username>/<repo>:<tag> .
```
4. Push your container registry:
```
docker push <username>/<repo>:<tag>
```

> [!NOTE]
> - After completing the above process, you can view the image information on the [docker hub](https://hub.docker.com/repository/docker/filswan/helloworld/general), as shown below:

![img](https://github.com/user-attachments/assets/188d1415-747f-4c0e-a053-43ea587ea5fd)
