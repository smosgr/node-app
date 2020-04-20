# Instructions
- git clone <project>
- cd node-app/
- node index.js
- curl or browse to localhost:3000


# Project Docker cheatsheet  
- docker run --name server-container -p 3000:3000 -d stel/simple-http
- docker stop server-container .
- docker rm -f $(docker ps -a -q)


Source: https://medium.com/@jandavid.staerk/why-kubernetes-is-awesome-9f7ff0186996