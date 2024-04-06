# Phase 1
Create EC2 instances for the following
- JENKINS (INstall docker , java, jenkins) -> run on port 8080 by default
- SonarQube (install Docker, install sonarQube) -> sudo docker run -d -p 9000:9000 sonarqube:lts-community
- Nexus (install docker, nexus) -> sudo docker -d -p 8081:8081 sonatype/nexus3
- Kubernetes (1 master, 2 slave servers )(docker, kubernetes)
All installation command with guidelines are provided in the same repo please read it carefully.

# Phase 2
- Install plugins
- Configure Tools
- Connet Tools
- Create pipeline
All these stpes are explained in 'CICD Plugins and Code.md' file, fololow the steps to create the pipeline.

# Phase 3
After the successfull creation of the pipeline, go to the console output in jenkins it will provide you the port number in which the application is running.
Copy the ip address of slave 1 and paste it like (eg. 1.1.1.1:31623)
