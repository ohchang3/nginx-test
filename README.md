# nginx-test

$ docker build -t ohchang3/nginx-test .
Sending build context to Docker daemon  56.83kB
Step 1/2 : FROM ubuntu
 ---> 74435f89ab78
Step 2/2 : RUN apt update -y
 ---> Running in 35bd850c8603

WARNING: apt does not have a stable CLI interface. Use with caution in scripts.

Get:1 http://archive.ubuntu.com/ubuntu focal InRelease [265 kB]
Get:2 http://security.ubuntu.com/ubuntu focal-security InRelease [107 kB]
Get:3 http://security.ubuntu.com/ubuntu focal-security/universe amd64 Packages [42.3 kB]
Get:4 http://security.ubuntu.com/ubuntu focal-security/restricted amd64 Packages [13.4 kB]
Get:5 http://security.ubuntu.com/ubuntu focal-security/main amd64 Packages [138 kB]
Get:6 http://archive.ubuntu.com/ubuntu focal-updates InRelease [107 kB]
Get:7 http://security.ubuntu.com/ubuntu focal-security/multiverse amd64 Packages [1077 B]
Get:8 http://archive.ubuntu.com/ubuntu focal-backports InRelease [98.3 kB]
Get:9 http://archive.ubuntu.com/ubuntu focal/multiverse amd64 Packages [177 kB]
Get:10 http://archive.ubuntu.com/ubuntu focal/restricted amd64 Packages [33.4 kB]
Get:11 http://archive.ubuntu.com/ubuntu focal/main amd64 Packages [1275 kB]
Get:12 http://archive.ubuntu.com/ubuntu focal/universe amd64 Packages [11.3 MB]
Get:13 http://archive.ubuntu.com/ubuntu focal-updates/multiverse amd64 Packages [1077 B]
Get:14 http://archive.ubuntu.com/ubuntu focal-updates/restricted amd64 Packages [16.4 kB]
Get:15 http://archive.ubuntu.com/ubuntu focal-updates/main amd64 Packages [270 kB]
Get:16 http://archive.ubuntu.com/ubuntu focal-updates/universe amd64 Packages [143 kB]
Get:17 http://archive.ubuntu.com/ubuntu focal-backports/universe amd64 Packages [2900 B]
Fetched 14.0 MB in 1min 1s (229 kB/s)
Reading package lists...
Building dependency tree...
Reading state information...
All packages are up to date.
Removing intermediate container 35bd850c8603
 ---> 8f1955656ea1
Successfully built 8f1955656ea1
Successfully tagged ohchang3/nginx-test:latest
SECURITY WARNING: You are building a Docker image from Windows against a non-Windows Docker host. All files and directories added to build context will have '-rwxr-xr-x' permissions. It is recommended to double check and reset permissions for sensitive files and directories.
