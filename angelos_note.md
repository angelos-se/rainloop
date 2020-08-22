This image is my very first attempt modifying a preexisting Dockerfile

This is intended to be used locally over a browser a replacement of desktop
mail client

cd into this dir and build:  
docker build . -t rainloop

Run:  
docker run -d -p 127.0.0.1:8888:8888 rainloop

Admin setup:
http://127.0.0.1:8888/?admin

User login:
http://127.0.0.1:8888
