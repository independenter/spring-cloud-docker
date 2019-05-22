docker build -t config-server:v1 .
&& docker run
-p 9000:9000
--name config-server
-d
config-server:v1 