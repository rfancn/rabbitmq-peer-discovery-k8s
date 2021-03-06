# RabbitMQ Peer Discovery Kubernetes

This is an K8s-based implementation of RabbitMQ [peer discovery interface](https://github.com/rabbitmq/rabbitmq-common/blob/master/src/rabbit_peer_discovery_backend.erl)
(new in 3.7.0, previously available in the [rabbitmq-autocluster plugin](https://github.com/rabbitmq/rabbitmq-autocluster)
by Gavin Roy).


## Supported RabbitMQ Versions

This plugin requires RabbitMQ 3.7.0 or later.

For a K8s-based peer discovery and cluster formation
mechanism that supports 3.6.x, see [rabbitmq-autocluster](https://github.com/rabbitmq/rabbitmq-autocluster).


## Documentation

See [RabbitMQ Cluster Formation guide](http://www.rabbitmq.com/cluster-formation.html).


## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md) and our [development process overview](http://www.rabbitmq.com/github.html).


## License

[Licensed under the MPL](LICENSE-MPL-RabbitMQ), same as RabbitMQ server.


## Copyright

(c) Pivotal Software Inc., 2007-2017.
