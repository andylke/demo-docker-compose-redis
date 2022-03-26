`docker-compose up -d`

```
[+] Running 7/7
 - redis Pulled                                                                   13.1s
   - 3aa4d0bbde19 Pull complete                                                    2.0s
   - b55ed66edac5 Pull complete                                                    2.2s
   - 114d91d0ac85 Pull complete                                                    3.0s
   - c31c4de88916 Pull complete                                                    4.2s
   - 067b317febb5 Pull complete                                                    4.4s
   - 1ec6fa78e12c Pull complete                                                    4.6s
[+] Running 2/2
 - Network demo-docker-compose-redis_default    Created                            0.2s
 - Container demo-docker-compose-redis-redis-1  Started                            2.0s
```

`docker-compose down`

```
[+] Running 2/2
 - Container demo-docker-compose-redis-redis-1  Removed                            0.9s
 - Network demo-docker-compose-redis_default    Removed                            0.3s
```
