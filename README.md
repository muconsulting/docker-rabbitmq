# RabbitMQ Dockerfile

A Dockerfile that produces a Docker Image for [RabbitMQ](http://www.rabbitmq.com/).

## Usage

### Build the image

To create the image `muconsulting/rabbitmq`, execute the following command on the `docker-rabbitmq` folder:

```
$ docker build -t muconsulting/rabbitmq .
```

### Run the image

To run the image:

```
$ docker run -ti --rm --name rabbitmq muconsulting/rabbitmq
```

## Copyright

Copyright (c) 2015 Sylvain Gibier. See [LICENSE](https://github.com/muconsulting/docker-rabbitmq/blob/master/LICENSE) for details.
