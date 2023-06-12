# 🚀 Demo project to show the demo of containerization methods using Dockerfile,Buildpacks,Jib 🚀

## Commands while using Dockerfile

|     Command       |     Description          |
| ------------- | ------------- |
| "mvn clean install" | To generate a jar inside target folder |
| "docker build . -t eazybytes/accounts" | To generate a docker image based on a Dockerfile |
| "docker run  -p 8081:8080 eazybytes/accounts" | To start a docker container based on a given image |

## Links & commands of Buildpacks

* [Buildpacks Website](https://buildpacks.io)
* [Buildpacks features comparison](https://buildpacks.io/features/#comparison)

|     Command       |     Description          |
| ------------- | ------------- |
| "mvn spring-boot:build-image" | To generate a docker image using Buildpacks |
| "docker run  -p 8081:8080 eazybytes/accounts" | To start a docker container based on a given image |

## Links & commands of Jib

* [Jib GitHub](https://github.com/GoogleContainerTools/jib)
* [Getting started with Jib](https://cloud.google.com/java/getting-started/jib)

|     Command       |     Description          |
| ------------- | ------------- |
| "mvn compile com.google.cloud.tools:jib-maven-plugin:3.3.2:build" | To generate a docker image with out Docker daemon |
| "mvn compile com.google.cloud.tools:jib-maven-plugin:3.3.2:dockerBuild" | To generate a docker image with Docker daemon |


## Contact the Instructor

For any questions, feedback, or suggestions. Feel free to reach out to me on [LinkedIn](https://www.linkedin.com/in/challamadan/), or on Email - tutor@eazybytes.com

# 🚀 For detailed courses from the instructor, kindly visit www.eazybytes.com. 🚀
