# Tmuxinator in Docker

Simple tmuxinator docker image based on alpine

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
