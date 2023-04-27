# Redis Cluster with Docker Compose

This is a simple project that sets up a Redis cluster using Docker Compose. The Redis cluster will consist of 6 nodes with the following addresses:

- 173.18.0.2:6379
- 173.18.0.3:6379
- 173.18.0.4:6379
- 173.18.0.5:6379
- 173.18.0.6:6379
- 173.18.0.7:6379

## Prerequisites

Before running this project, you must have the following installed on your system:

- Docker
- Docker Compose

## Running the Redis Cluster

To run the Redis cluster, simply run the following command:

```bash
docker-compose up
```

This will start the Redis cluster and output the logs to the console. If you want to run the cluster in the background, use the `-d` flag:

```bash
docker-compose up -d
```

## Redis Commander

This project also includes Redis Commander, a web-based tool for managing Redis, which will be running on port 7099. You can access it by visiting http://localhost:7099 in your web browser.

Redis Commander provides an easy-to-use interface for managing the Redis cluster, including viewing keys, inspecting data, and executing commands across all nodes in the cluster.

## Connecting to the Redis Cluster

Once the Redis cluster is running, you can connect to it using any Redis client library or tool. Use the IP addresses and port numbers listed above to connect to each of the nodes in the cluster.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
