docker build -t eureka-server:v1 .
&& docker run
-p 8000:8000
--name eureka-server
-d
eureka-server:v1 