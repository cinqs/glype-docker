# glype-docker

## Acks
This work uses the following works from *Creative Commons*

1. `APACHE 2`
2. `PHP 7.12`
3. `PHP docker project`
4. [`Glype`](https://sourceforge.net/projects/glypeproxy/)

## contacts the author

* **Email**: [ci.song@aliyun.com](mailto:Ci Song<ci.song@aliyun.com>)
* **Website**: https://cinqs.cn https://cinqs.me


## hows

if you want to use docker [hub repo](https://hub.docker.com/u/cinqsoong/glype/):

    docker run -it --rm --name glype -p 9000:80 cinqs/glype:latest

if you just want to try try this repo, use this

1. first check out this repo and cd into it

       git clone https://github.com/cinqs/glype-docker.git && cd glype-docker

2. second you have to build it first

       docker build -t cinqs/glype .

3. then you run it

       docker run -it --rm --name glype -p 9000:80 cinqs/glype
    
you may need to open a browser to address to *http://ip-address-of-your-docker-host:9000*

## argues

what is wrong with this [repo](https://hub.docker.com/r/frankzhang/glype/)

* old and out-of-date
* mysteries of source
* not-maintant any more
