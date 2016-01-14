# docker-nginx-src
A nginx Dockerfile which compile by source (based image from [sameersbn](https://github.com/sameersbn/docker-nginx))

### Enable nginx module ###
* rtmp module
* pagespeed module
* ldap auth module

### How to use
Build image

    $ git clone https://github.com/engineerball/docker-nginx-src.git
    $ cd docker-nginx-src
    $ docker build -t engineerball/docker-nginx-src .

Run image

    $ docker run -i -t -p 80:80 -p 443:443 -p 1935:1935 engineerball/docker-nginx-src

Pull image from dockerhub

    $ docker pull engineerball/docker-nginx-src

