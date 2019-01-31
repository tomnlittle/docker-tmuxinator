# Tmuxinator in Docker

Simple tmuxinator docker image based on alpine

## Getting Started

These instructions will cover usage information and for the docker container

### Prerequisities

In order to run this container you'll need docker installed.

* [Windows](https://docs.docker.com/windows/started)
* [OS X](https://docs.docker.com/mac/started/)
* [Linux](https://docs.docker.com/linux/started/)

### Usage

#### Importing a tmuxinator file

If you have a local tmuxintaor file you can use the example command below to import
and execute tmuxinator local.

```shell
docker run \
  -it \
  -v $PWD:/app \
  -w /app \
  tomnlittle/tmuxinator \
  tmuxinator local
```

## Find Us

* [GitHub](https://github.com/tomnlittle/docker-tmuxinator)
* [Dockerhub](https://cloud.docker.com/u/tomnlittle/repository/docker/tomnlittle/tmuxinator)

## Authors

* **Thomas Northall-Little**

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
