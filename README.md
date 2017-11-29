# glype-docker

## Acks
This work uses the following works from *Creative Commons*

1. `APACHE 2`
2. `NGINX 1.13`
3. `PHP 7.12`
4. `PHP docker project`
5. [`Glype`](https://sourceforge.net/projects/glypeproxy/)


## hows

if you just want to try, use this

1. first check out this repo and cd into it

    git clone https://github.com/cinqs/glype-docker.git && cd glype-docker

2. second you have to build it first

    docker build -t cinqs/glype .

3. then you run it

    docker run -it --rm --name glype -p 9000:80 cinqs/glype
    
you may need to open a browser to address to *http://ip-address-of-your-docker-host:9000*
