Configuration files from [https://github.com/geoffroya/BzhCmp2016](https://github.com/geoffroya/BzhCmp2016)

# Launch
````bash
docker-compose up
````

# Access
Kibana: [http://localhost:5601](http://localhost:5601)

# Add logs
Logstash accept content via tcp on port 5514
```bash
$ nc localhost 5514 < /path/to/logfile.log
```
