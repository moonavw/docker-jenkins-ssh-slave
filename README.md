# jenkins-ssh-slave
docker jenkins ssh slave with docker installed

based on jenkinsci/ssh-slave

## BUILD
    docker build -t jenkins-ssh-slave .

## RUN
    docker run -d jenkins-ssh-slave "<public key>"
