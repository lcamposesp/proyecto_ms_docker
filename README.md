# proyecto_ms_docker
proyecto final del curso de microservicios a escala con Docker utilizando Kubernetes

# instrucciones para el despliegue

para poder hacer el despliegue es necesario tener instalado Minikube https://minikube.sigs.k8s.io/docs/start/
Una vez instalado, abrir una terminal y confirmar que se este en el inicio del repositorio y ejecuta `kubectl apply -k ./` lo cual va a correr el`kustomization.yaml`
Despues de que termine de correr ese comando se pueden hacer los siguientes: 

Para poder ver los servicioes y su estado
`kubectl get service`
Para poder ver los pods y su estado
`kubectl get pods`

Y para poder obtener la ip para acceder al servicio
`minikube service wordpress --url`
