# Sample Python App for Docker
Sample Python App in  to run in Docker

Clone repo to local directory
Using a command line, browse to the directory

Build the docker image
 Command is 'docker build --tag=<insert some friendly name> .'
 Example: >docker build --tag=pyton_app .
  
Run the container
  Command is 'docker run -p <external port>:<internal port> <friendly name>
  Example>docker run -p 9000:80 python_app

Open browser and go to port you have chosen
  localhost:9000
  

