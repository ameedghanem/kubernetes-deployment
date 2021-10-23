## Ingress-Deployment
	running the spring-music image

## Prerequisties
	docker
	kubernetes
 

## Deployment

```
$ kubectl create deployment spring-music --image=yanivomc/spring-music:latest
$ kubectl get deployments
$ kubectl expose deployment spring-music --port=8090 --target-port=8080
$ kubectl create -f ingress.yaml
$ curl -l http://127.0.0.1/music
```
