# gitlab-springboot

currently 2-layer not suited

## Spring Boot API deployment using GitLab CI/CD and Docker
```
https://boottechnologies-ci.medium.com/spring-boot-api-deployment-using-gitlab-ci-cd-and-docker-e2ebd88eb8af
```

# Troubleshoot LINks

Vaadin-14-Docker-Image - Parent Image for Vaadin 14
```
https://github.com/felix-seifert/Vaadin-14-Docker-Image/blob/master/README.md
```

Docker: failed to export image: failed to create image: failed to get layer
```
https://stackoverflow.com/questions/51115856/docker-failed-to-export-image-failed-to-create-image-failed-to-get-layer
```

Docker build fails "COPY failed: no source files were specified"
```
https://stackoverflow.com/questions/59747862/docker-build-fails-copy-failed-no-source-files-were-specified
```

Docker: failed to export image: failed to create image: failed to get layer
```
https://stackoverflow.com/questions/51115856/docker-failed-to-export-image-failed-to-create-image-failed-to-get-layer
```

Spring Boot API deployment using GitLab CI/CD and Docker
```
https://boottechnologies-ci.medium.com/spring-boot-api-deployment-using-gitlab-ci-cd-and-docker-e2ebd88eb8af
```

Beginners guide to setting up Gitlab CI/CD with Docker for Spring Boot
```
https://medium.com/@theanilpaudel/beginners-guide-to-setting-up-gitlab-ci-cd-with-docker-for-spring-boot-7b69e8390aec
```

Using spring-boot:build-image in Gitlab-ci.yaml Pipeline to create a docker image
```
https://stackoverflow.com/questions/71295726/using-spring-bootbuild-image-in-gitlab-ci-yaml-pipeline-to-create-a-docker-imag
```

## Cannot connect to the Docker daemon at tcp://localhost:2375/. Is the docker daemon running. On GitLab
```
https://stackoverflow.com/questions/61105333/cannot-connect-to-the-docker-daemon-at-tcp-localhost2375-is-the-docker-daem
```

Use Docker to build Docker images 
Use Docker-in-Docker
You can now use docker in the job script. You should include the docker:20.10.16-dind service:
```
https://docs.gitlab.com/ee/ci/docker/using_docker_build.html
```

## docker build exits successfully but no built image show up in the docker images
```
https://github.com/docker/cli/issues/2686
```
![image](https://github.com/caelumpirata/gitlab-springboot/assets/85424262/0809a5d2-0a46-480c-a367-5c82826ac1fe)

example:
```
docker build --load -t <source_image_name> .
```
## docker tag
```
https://docs.docker.com/engine/reference/commandline/tag/
```
example
```
docker tag <source_image_name>:<source_image_tag>  <username>/<target_image_name>:<target_image_tag>
```
