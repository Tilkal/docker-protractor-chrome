# docker-protractor-chrome
Node 14 based image with protractor and google chrome headless installed

# build

docker build --tag node-protractor-chrome .

# run

docker run -it --volume /path/to/my/node/app:/src/app node-protractor-chrome bash  
