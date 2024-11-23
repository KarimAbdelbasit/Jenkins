### Jenkins
###### Install jenkins in Docker
###### open power shell
###### Do container jenkins by run the command :
```
docker run -d -p 8080:8080 -p 50000:50000 --name jenkins jenkins/jenkins:lts 
```
open the browser
 ```
http://localhost:8080
```
The browser will ask you for your password to know that run the command :
```
docker exec jenkins cat /var/jenkins_home/secrets/initialAdminPassword
```

