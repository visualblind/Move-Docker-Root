# Move-Docker-Root
Shell script to move the Docker Root directory on Ubuntu 16.04 Xenial.

To use this script simply edit the line <code>/dockerdir_new='/docker/var/'</code> to reflect your intended new Docker Root location and <code>chmod +x move-docker-root.sh</code>, then run with <code>./move-docker-root.sh</code>.

Tested working on:

Client:
 Version:      17.05.0-ce
 API version:  1.29
 Go version:   go1.7.5
 Git commit:   89658be
 Built:        Thu May  4 22:10:54 2017
 OS/Arch:      linux/amd64

Server:
 Version:      17.05.0-ce
 API version:  1.29 (minimum version 1.12)
 Go version:   go1.7.5
 Git commit:   89658be
 Built:        Thu May  4 22:10:54 2017
 OS/Arch:      linux/amd64
 Experimental: false
