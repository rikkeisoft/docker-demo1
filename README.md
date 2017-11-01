# Docker-rails

## Clone source

* Clone with SSH: <br>
```
git clone git@github.com:rikkeisoft/docker-demo1.git /path/to/docker-demo1
```
* Clone with HTTPS: <br>
```
git clone https://github.com/rikkeisoft/docker-demo1.git /path/to/docker-demo1
```

## Create new rails app

* Nếu máy bạn cài sẵn rails
```
cd /path/to/docker-demo1 && rails new rails_app
```

* Nếu máy bạn không cài rails
```
cd /path/to/docker-demo1 && git checkout app_exist
```

## Build image demo

```
docker build -t demo .
```
## Run a new container with name is hello

```
docker run -it --name hello -p 3000:3000 demo
```
