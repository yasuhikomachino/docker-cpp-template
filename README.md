# docker-cpp-template

A template to quickly build a c++ development environment.

## Environment

- Docker 19.03.12
- docker-compose 1.26.2

## Stack

- g++ 10.2.0

## Setup

```
$ docker-compose build
```

## Run cpp container 

```
$ docker-compose run --rm cpp bash
```

```
# g++ --version
g++ (Ubuntu 10.2.0-13ubuntu1) 10.2.0 

# g++ -o sample sample.cpp  
# ./sample
Hello! World!
```
