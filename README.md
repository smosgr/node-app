> Reference project to familiarise with technologies and concepts.


# Involved technogogies 
- NODE JS APP
- AWS
- DOCKER
- K8S
- AWS CodePipeline/CodeDeploy or Gitlab CI


# Instructions
- git clone git@github.com:smosgr/node-app.git
- cd node-app/
- node index.js
- curl or browse to localhost:3000


# Project Docker cheatsheet  

- docker build -t simple-http .
- docker run --name server-container -p 3000:3000 -d simple-http
- docker stop server-container .
- docker rm -f $(docker ps -a -q)


# References
- Tutorials
https://medium.com/@jandavid.staerk/why-kubernetes-is-awesome-9f7ff0186996
https://medium.com/containermind/how-to-create-a-kubernetes-cluster-on-aws-in-few-minutes-89dda10354f4

- K8s
https://aws.amazon.com/kubernetes/
https://github.com/kubernetes/kops
https://aws.amazon.com/eks/
https://docs.aws.amazon.com/eks/latest/userguide/fargate.html

- Docker
https://www.docker.com/sites/default/files/d8/2019-09/docker-cheat-sheet.pdf

- Other
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet