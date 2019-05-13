helm install mySampleApp --name=app


kubectl describe $(kubectl get pods -o name | grep "boo")

kubectl describe $(kubectl get deployments -o name | grep "boo")


helm delete --purge app
