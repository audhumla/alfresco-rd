# alfresco-rd

Just a repo to start alfresco and play with it

## Start

Preferred use is to start it via docker-compose:
```bash
docker-compose up -d
```

Then type:
```bash
docker logs -f alfresco-rd_alfresco_1
```
And wait for the log:

```
INFO [main] org.apache.catalina.startup.Catalina.start Server startup in 102716 ms
```

After the log appeared, you can connect to Alfresco visiting the page: [http://localhost:8080/alfresco/](http://localhost:8080/alfresco/)


When you're done, execute:

```
docker-compose down --rmi
```
