Add postgresql config:

```
volumes:
    - ./postgresql/postgresql.conf:/var/lib/postgresql/data/pgdata/postgresql.conf
```


Add redis conf and persistent storage:

```
volumes:
    - ./redis/data:/data
    - ./redis/redis.conf:/usr/local/etc/redis/redis.conf
```

