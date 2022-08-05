# Geeks Profile Task
Web application that allows users to create their own profile, 
using FLASK and MySQL database.
Dockerize the app automatically using Jenkins pipeline  
push the docker image to DockerHub.
Run the app with Kubernetes over Minikube.


## Run  the app Using Docker Compose

Clone the project

```bash
    git clone https://github.com/waheeb96/geeks-profile.git
```

Go to the project directory

```bash
  cd Geeks-Profile
```

Build the project

```bash
  docker compose up
```

Run the app

```bash
  http://localhost:5000/
```
## DockerHub repository:
![geeks-profile1](https://user-images.githubusercontent.com/72220299/183122518-91294564-39c5-4f83-ac1d-109ed2563aa3.PNG)



## run in kubernetes 

Start minikube

```bash
  minikube start
```

Enable ingress

```bash
  minikube addons enable ingress
```

Apply 

```bash
  kubectl apply -f .
```

To run on localhost

```bash
  minikube tunnel
```


