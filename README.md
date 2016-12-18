# raspberry home energy monitor project

(!) This is experimental work in progress

## Requirements
Raspberry pi
docker-engine
docker-compose

## Source code checkout
git clone git@github.com:b00lduck/raspberry-datalogger.git
git submodule update --init --recursive

## Build docker images
cd raspberry-datalogger-compose
./build-all.sh

## Run
create grafana config in /opt/grafana/etc
docker-compose up -d

