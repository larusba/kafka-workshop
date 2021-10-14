# Apache Kafka and Neo4j Streams Workshop

This is the repository for the Apache Kafka and Neo4j Streams Workshop.

## How to run

Be sure to have Docker installed and set Docker memory to a minimum of 4GB. 

In order to prevent conflicts with existent Docker containers i kindly suggest to run the following two commands:

```
docker stop $(docker ps -a -q)
docker rm $(docker ps -a -q)
```

Then run the following command from the repository root directory:

```
docker-compose up -d
```

It will take some time to download all the Docker images. 

Once it's started please visit [localhost:8080](http://localhost:8080) to view the Zeppelin interface and start playing with the notebooks!

---

Note that **this is not definitive version**. This repository is getting constantly updated and we highly suggest you to pull the new version the day of the workshop!

If you have any problem please open an issue on this repository.
