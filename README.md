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

## Reports + Slides
- [Slide](https://goo.gl/x7zzk9)
- [Report - CongTH](https://goo.gl/tay3to)
- [Report - ThienNK](https://docs.google.com/document/d/1fafzN1MGgEwZXqbPD9t0VopTRsfvh-Rf6gXJ-1sdEHc)
- [Report - CamVT](https://goo.gl/cLy2ek)
