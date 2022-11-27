Running Kubernetes and the dashboard with Docker Desktop:
https://andrewlock.net/running-kubernetes-and-the-dashboard-with-docker-desktop/
get latest version number of dashboard and use it in installation(v2.2.0 was latest at the time of writing):
kubectl apply -f https://raw.githubusercontent.com/kubernetes/dashboard/v2.2.0/aio/deploy/recommended.yaml
create admin account, to get access dashboard with no restrictions:
kubectl create clusterrolebinding serviceaccounts-cluster-admin --clusterrole=cluster-admin --group=system:serviceaccounts

Nginx+GO+MongoDB with Docker Stack
https://github.com/itwars/docker-golang-rest-mongodb-nginx

marcel-dempers:
https://github.com/jeanclei/marcel-dempers_docker-development-youtube-series
