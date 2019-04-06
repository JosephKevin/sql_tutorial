# SQL Tutorial
  Repo to build a docker image for sql tutorial at ``` ``` 

# Steps:
1. Make sure you are in the directory which contains the Dockerfile
2. Build the docker image
    
        docker build --rm --tag jkm2155/sqltutorial:1.0.0 .
3. Login to docker hub
        
        docker login
4. Push the build docker image to docker hub
        
        docker push jkm2155/sqltutorial:1.0.0
                    
