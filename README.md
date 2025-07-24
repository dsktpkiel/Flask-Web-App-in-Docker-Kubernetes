# Flask-Web-App-in-Docker-Kubernetes
Kubernetes Application in local deployment and planned Cloud provision either AWS/Azure.

Cheatsheets Terminal Commands:

minikube start --driver=docker - starts minikube that will use Docker as the VM
kubectl get nodes - check and verify if the cluster is ready
minikube -p minikube docker-env | Invoke-Expression - switch to minikube's docker environment


Docker Build Commands:
docker build -t [app folder where dockerfile is located] .
docker run -p 3000:3000 [app folder where dockerfile is located]


ChatGPT Generated Sample YAML, Line-by-line explanation:

<img width="834" height="557" alt="image" src="https://github.com/user-attachments/assets/07d0c257-961f-41bf-b0cb-a10684a8cb4f" />
<img width="788" height="533" alt="image" src="https://github.com/user-attachments/assets/18242301-d606-4d3e-9f03-ead676bd2907" />
<img width="802" height="680" alt="image" src="https://github.com/user-attachments/assets/4a061483-2b3f-41f8-8291-173a44a8e28d" />
