# kubernetesplayground

## Kubernetes Dev Setup

1. install virtual box
2. install kubectl - https://kubernetes.io/docs/tasks/tools/install-kubectl/
3. install minikube - https://github.com/kubernetes/minikube/releases/
4. quick start - https://kubernetes.io/docs/getting-started-guides/minikube/#quickstart
- Note: --vm-driver=xxx settings for your virtualization
5. minikube container repository workflow - https://blog.hasura.io/sharing-a-local-registry-for-minikube-37c7240d0615
6. create manifest (https://kubernetes.io/docs/concepts/services-networking/service/)

More:

kompose (docker-compose.yaml -> k8s manifest.yaml) - https://github.com/kubernetes/kompose

cheat sheet - https://kubernetes.io/docs/user-guide/kubectl-cheatsheet/

setup private repository
- https://mtpereira.com/local-development-k8s.html
- https://kubernetes.io/docs/tasks/configure-pod-container/pull-image-private-registry/

kubernetes RESTful api spec - https://kubernetes.io/docs/api-reference/v1.8

issues encountered: 
- http://kukulinski.com/10-most-common-reasons-kubernetes-deployments-fail-part-1
- http://kukulinski.com/10-most-common-reasons-kubernetes-deployments-fail-part-2
