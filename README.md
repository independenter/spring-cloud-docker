1.http请求地址和资源文件映射如下:
  /{application}/{profile}[/{label}]
  /{application}-{profile}.yml
  /{label}/{application}-{profile}.yml
  /{application}-{profile}.properties
  /{label}/{application}-{profile}.properties

2.访问github资源
http://localhost:9000/config-client-dev.properties
http://localhost:9000/config-server-dev.properties
http://localhost:9000/config-client-dev.yml
http://localhost:9000/config-server-dev.yml
http://localhost:9000/config-client-dev/foo
http://localhost:9000/config-server-dev/foo
#无价值
http://localhost:9000/foo/config-client-dev
http://localhost:9000/foo/config-server-dev