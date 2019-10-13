# devops-microservices
Microservices is hard... and devops within microservices is harder...




## Project description 
+ Implementation of different methods towards DevOps - within microservice architecture 



+ Parse-server : 
    + image built in docker container - kubernetes as orchestration tool 
    + deploy the parse- server to kubernetes cluser (of course with already configured kubernetes)
    + Redis service 
        + Create a kubernetes service 


## Ref : 
https://github.com/parse-community/parse-server




docker push ${DOCKER_USER}/parse-server


## AWS 



## Google cloud platform 
+ gcloud init 
+ CD/CI 
    + CI 
        + Code commit on Github 
        + CI server pools repo, run test 
        + CI server sends notification - feedback of the integration test 
        (script = CI server )
    + CD 
        + Branches 
        + Unit test 
        + Automatic test 
        + Code promotion 
+ Docker - Kubernetes 
    + Google compute engine 
    + Create Kubernetes cluster 
        + Cluster is ready -> get credentials 
