fake-s3
=======

Dockerfile for
[ashkop/fake-s3](https://registry.hub.docker.com/u/ashkop/fake-s3/)
on [Docker Hub](https://registry.hub.docker.com). Forked from [lphoward/fake-s3](https://registry.hub.docker.com/u/lphoward/fake-s3/)

Deploys [fake-s3](https://github.com/ashkop/fake-s3) in a Docker container.

To create a deployment:

        docker run --name my_s3 -d ashkop/fake-s3

Service exposed on port 4569.  Credentials are ignored.
See [fake-s3](https://github.com/jubos/fake-s3) README for details/limitations.

If you want fake-s3 to be exposed on your Docker host on port 4569, then

        docker run --name my_s3 -p 4569:4569 -d ashkop/fake-s3

