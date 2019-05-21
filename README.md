inetsim-docker

docker build -t [name] .

docker run -it -d --name inetsim [name]

docker ps

docker exec -i -t inetsim /bin/bash

Start InetSim

$ inetsim > ./inetsim.log &



root@7155e770f5b3:/# netstat -anp
Active Internet connections (servers and established)
Proto Recv-Q Send-Q Local Address           Foreign Address         State       PID/Program name    
tcp        0      0 127.0.0.1:990           0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:1             0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:995           0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:37            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:7             0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:9             0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:6667          0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:13            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:110           0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:79            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:80            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:465           0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:17            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:113           0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:19            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:21            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:53            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:25            0.0.0.0:*               LISTEN      -                   
tcp        0      0 127.0.0.1:443           0.0.0.0:*               LISTEN      -                   
udp        0      0 127.0.0.1:1             0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:7             0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:9             0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:13            0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:17            0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:19            0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:37            0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:53            0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:69            0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:123           0.0.0.0:*                           -                   
udp        0      0 127.0.0.1:514           0.0.0.0:*                           -                   
Active UNIX domain sockets (servers and established)
Proto RefCnt Flags       Type       State         I-Node   PID/Program name     Path


