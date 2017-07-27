# tracker_db
Database used with Tracker App

## Prerequisites
1. Install docker
2. Install Git

## Setup data for db
1. git clone repository
2. mkdir ~/data
3. cd repository
4. cp data.tar.Z ~/data
5. uncompress data.tar.Z
6. tar -xvf data.tar

## Start docker container
```http
sudo docker run -d -p 27017:27017 -v ~/data:/data/db mongo
```