# Scala, sbt and AWS CLI Dockerfile

[![Docker Build Statu](https://img.shields.io/docker/build/toolsplus/scala-sbt-aws.svg)]()

This repository contains **Dockerfile** based on [scala-sbt](https://github.com/hseeberger/scala-sbt)
adding the AWS CLI.


## Base Docker Image ##

* [scala-sbt](https://github.com/hseeberger/scala-sbt)


## Installation ##

1. Install [Docker](https://www.docker.com)
2. Pull [automated build](https://registry.hub.docker.com/u/toolsplus/scala-sbt-aws) from public [Docker Hub Registry](https://registry.hub.docker.com):
```
docker pull toolsplus/scala-sbt-aws
```
Alternatively, you can build an image from Dockerfile:
```
docker build -t toolsplus/scala-sbt-aws github.com/toolsplus/scala-sbt-aws
```


## Usage ##

```
docker run -it --rm toolsplus/scala-sbt-aws
```


## Contribution policy ##

Contributions via GitHub pull requests are gladly accepted from their original author. Along with any pull requests, please state that the contribution is your original work and that you license the work to the project under the project's open source license. Whether or not you state this explicitly, by submitting any copyrighted material via pull request, email, or other means you agree to license the material under the project's open source license and warrant that you have the legal authority to do so.


## License ##

This code is open source software licensed under the [Apache 2.0 License]("http://www.apache.org/licenses/LICENSE-2.0.html").