## minikube commands
<details>
  <summary>Click to expand</summary>

  ```minikube
  minikube start
  minikube docker-env
  minikube docker-env | Invoke-Expression

  minikube service flask-service
  ```
</details>

## Docker commands
<details>
  <summary>Click to expand</summary>

  ```docker
docker build -t flask_app .
docker run -p 5000:5000 flask_app
  ```
</details>

## Kubectl commands
<details>
  <summary>Click to expand</summary>

  ```kubernetes
  Kubectl create -f .\overlays\pods.yaml
  Kubectl create -f .\overlays\deploymnet.yaml
  ```
</details>


