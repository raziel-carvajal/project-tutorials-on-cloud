# this image relies on the nodejs image
from node:alpine
# your workspace
workdir /usr/src/scapp-front-end
# copy the configuration file into the workspace
copy package.json .
# install dependencies
run npm install
# copy the source code as well
copy public public
copy src src
# deploy the front end
cmd npm start
