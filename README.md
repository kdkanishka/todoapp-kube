# Prerequisites
* Setup minikube
    * https://minikube.sigs.k8s.io/docs/start/
    * Verify minikube installation is successful(`minikube status`)
* Install kubectl
    * https://kubernetes.io/docs/tasks/tools/install-kubectl-linux/

# Session Resources
* Clone https://github.com/kdkanishka/todoapp-kube.git
* Create deployments
    * `kubectl apply -f <yaml file>`
* Add hostentry for todoapi.com
    * `192.168.49.2 todoapi.com`
* Load testing
    * `ab -n 1000 -c 100 http://todoapi.com/todo/export`

# Related projects
    * Frontend app - https://github.com/kdkanishka/todoapp.git
    * ToDo api - https://github.com/kdkanishka/todo-api.git
    * ToDo service - https://github.com/kdkanishka/todo-backend.git

