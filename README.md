# sdqube_docker
Docker dependencies for the project including Dependent tools and deployment of services


### Command
**- Run All Tools for services**

```
docker-compose -f docker-compose.yml up -d 

OR 

docker-compose run
```

**- Run selective tools onlu**

`docker-compose run kafdrop kafka`



### Consul service discovery

```docker run -p 8400:8400 -p 8500:8500 -p 8600:53/udp -h node1 progrium/consul -server -bootstrap -ui-dir /ui```