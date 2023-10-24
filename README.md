# REDIS FROM BLAZOR APP DEMO

1. Get Redis from docker hub
> docker run --name my-redis -p 7002:6379 -d redis

2. Optional; open external console for shell
> docker run --name my-redis -p 7002:6379 -d redis

3. Local Redis is running on 7002 port
> localhost:7002

4. If you want to change to redis for azure, redis for AWS or redis on cloud, only change de ConnectionString in appsettings.json