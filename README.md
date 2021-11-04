# DockerDLNA
Server DLNA



#### Mount volume TimeCapsule

`mount.cifs --verbose //IP_YOUR_TIMECAPSULE/Data /PATH/LOCAL -o user=YOUR_USER_TC,password=YOUR_PASS_TC,sec=ntlm,uid=$USER,vers=1.0`

Package required
- cifs-util

#### Deploy

`docker-compose up -d`
