docker build -t config-client:v1 .
&& docker run
-p 9001:9001
--name config-client
-d
config-client:v1 