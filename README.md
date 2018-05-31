# Docker for ngx_pagespeed
  pagespeed：1.13.35.2  

  nginx：1.14  

  Centos：7


## Using the Dockerfile

### Use docker build command to build an image from dockerfile:
  $ docker build -t <image_tag> -f <dockerfile_path> .
 Refer this for additional options.

### Run this container as an independent service(80 or 443):
  $ docker run -d -p 80:80 <image_tag>
    or
  $ docker run -d -p 443:443 <image_tag> 
