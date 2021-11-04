## Kubernetes Final Task
A deployment and service for the image [yanivomic/spring-music:latest](https://hub.docker.com/layers/yanivomc/spring-music/latest/images/sha256-b444784822fb38b1fb32495da1942fcf9ef6071ed33de0b305ddafb289d649f0?context=explore) in kubernetes.</br>
It also creates an Ingress to access the service.
	
## Prerequisties
	docker
	kubernetes
 
## Installation

```
$ git clone https://github.com/ameedghanem/kubernetes-hw.git
  ...
$ cd kubernetes-hw/
```
	
## Deployment

```
$ kubectl apply -f spring-music-deployment.yml && kubectl apply -f ingress.yml
```
---

### To view the app, browse to http://127.0.0.1/music
