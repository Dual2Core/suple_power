# Projekt Suple-Power

## Requirements
* Docker 17.06.2
* Docker-compose 1.15.0

## Usage

At first, pelase check your tools:
```bash
user@ubuntu:~$ docker -v
Docker version 17.06.2-ce, build cec0b72
user@ubuntu:~$ docker-compose -v
docker-compose version 1.15.0, build e12f3b9
```
Clone this repository:
```bash
git clone https://github.com/Dual2Core/suple_power.git
```
Then get into the directory:
```bash
cd suple_power
```
Now you can run the docker-compose.yml configuration file:
```bash
docker-compose up # Creates two containers, read docker-compose.yml for more info
```
After running these commands your can successfully access the magento framework at:
```bash
http://localhost/
```