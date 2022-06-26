INSTALL KUBERNETES:
--------------------------------------------
step-1: sudo apt-get update -y
step-2: sudo apt install docker.io
step-3: sudo wget https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
step-4: pwd
step-5: ls -lrt
step-6: sudo mv minikube-linux-amd64 /usr/local/bin/minikube
step-7: sudo chmod 755 /usr/local/bin/minikube
step-8: curl -LO https://storage.googleapis.com/kubernetes-release/release/`curl -s https://storage.googleapis.com/kubernetes-release/release/stable.txt`/bin/linux/amd64/kubectl
step-9: ls -lrt
step-10: sudo mv kubectl /usr/local/bin/kubectl
step-11: sudo chmod 755 /usr/local/bin/kubectl
step-12: kubectl version
step-13: minikube start
step-14: ls -l /var/run/docker.sock
step-15: sudo usermod -aG docker ubuntu
step-16: exit
step-17: minikube start
step-18: minikube status
step-19: kubectl cluster-info
step-20: kubectl get nodes
