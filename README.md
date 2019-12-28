# docker

docker images

## ASP.NET Core Images

with asp.net core alpine images, you can not access sql server with any culture. simply because there are too many cultures and alpine is tiny.
so i made a few modification on alpine images and posted them in my [docker hub images](hub.docker.com/peymanpn)

[ASP.NET Core Images](https://hub.docker.com/repository/docker/peymanpn/aspnet)

* ASP.NET Core 3.0.1 alpine 3.10 

      docker pull peymanpn/aspnet:3.0.1-alpine3.10
* ASP.NET Core 3.1.0 alpine 3.10

      docker pull peymanpn/aspnet:3.1.0-alpine3.10
