# Pull latest alpine image
FROM alpine
# test running command
RUN mkdir hello-world ; touch ./hello-world/hello-world-file
# copy file from workdir to container
COPY . /src
WORKDIR /src 
ENTRYPOINT /bin/bash

