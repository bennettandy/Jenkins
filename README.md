# Jenkins with Docker Support

Builds a Docker Image from the latest jenkins/jenkins image and include docker support.
This is useful when running containerised builds such as Android builds.

[Imgur](https://i.imgur.com/EVEoEwE.png)

```
 cd build/centos
 docker build -t avsoftware/jenkins:latest .
 docker push avsoftware/jenkins:latest
 ```
