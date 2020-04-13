# devops-microservices
DevOps in distributed system 


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
        + Deploy 
        + Config load balancer 
        + K8 UI 
            + IAM 
+ Jenkins 
    + Google Kubernetes engine 
    + Jenkins in the cluster 
    + Google Cloud Container Registry and Google Cloud Storage
    + Get credentials : gcloud container clusters get-credentials --zone us-east1-b jenkins-cd
    + Jenkins architecture : Master - Slave -> scale the job 
        + 2 nodes 
        + Config Jenkins : 
        + Create jenkins service 
            + Jenkins UI 
            + Jenkins discovery 



+ Google App Engine 
    + Google source repository 
    + Start up / reboot script 
    + Create and config GCE instance 
    + Host on GAE 
    + Host on Kubernetes Engine 
    + Host on Google Cloud function 
    + Deploy the application 
        + Create and configure GCE instance 
    + App Engine resource and integration 
        + Data storage, Memcache, Cloud storage, Mail, Scheduled task, Task queue.
        + Push - Pull queues 

+ Database : 
    + 





## Microservices Devops 
+ Build Docker image 
+ Deploy docker image to K8 
    + yml file - and deployment file 




## Microservices testing 
+ Arquillian 
+ Selenium : Java UI test 
+ Cucumber : automation integration test 
+ Robot framework 



## Tech stack 
- Java EE 
- OpenShift 
- Ansible 
- Jenkins
- Puppet 

- IaC 



## Resource 
- https://searchstorage.techtarget.com/definition/InfiniBand


