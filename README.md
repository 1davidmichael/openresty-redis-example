# Example OpenResty with Redis proxy

This is an example of using OpenResty to proxy content to a predefined backend if the uri matches a key stored in Redis. 
Vagrant VM listens on port 8081.

## Setup
```
git clone git@github.com:1davidmichael/openresty-redis-example.git
cd openresty-redis-example
vagrant up
vagrant ssh
redis-cli set /foo/ true
```
