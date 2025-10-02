# Projeto conversão de temperatura

### Sobre o projeto
O projeto conversão de temperatura é um projeto desenvolvido em NodeJS. O projeto tem como objetivo ser um exemplo para a criação de ambiente com containers usando NodeJS.

### Observações do projeto
A aplicação é exposta usando a porta 8080

### DockerFile

`docker build -t namespaceGenerico-ubuntu-curl -f Dockerfile .`

docker build
This is the Docker command to build a new image from a Dockerfile.

The -t flag tags the image with a name. Here, the image name is namespaceGenerico-ubuntu-curl.


-f Dockerfile
Specifies the Dockerfile to use for the build. If omitted, Docker defaults to a file named Dockerfile in the build context.

.
The dot at the end specifies the build context – typically the directory containing the Dockerfile and any files you want to copy into the image.