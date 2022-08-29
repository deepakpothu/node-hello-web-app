# Node Hello World
Simple node.js app that servers "hello world"
Great for testing simple deployments to the cloud

## Run It
`npm start`

FOR DOCKER 
Added dockerfile so use docker build command and docker run command to deploy it in container

docker build -t hello_node:1 .

docker run --name hello_node_app -d -p 9000:3000 hello_node:1
