The enviroment for baota systems
--------------------------

This works with https://hub.docker.com/repository/docker/xros/baota

Create a docker volume first `docker create volumne baota`

Unzip the _data.tar.gz file to your mapped volume in `/var/lib/docker/volumes/baota/_data` 

Then get into your container instance and start all services with `. /etc/rc.local`
