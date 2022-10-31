# Docker project 1

## Sources for the first Docker project


Build/run: 


```cli
docker build --tag "javase" JavaSE/
docker run javase
```


```cli
docker build --tag "angularapp" Angular/
docker run -p 80:80 angularapp
```

----

Note: Nginx will listen on port 80 when running the Angular image, configurable from /Angular/nginx.conf
