# kubernetes_hw
1. дз kubernetes заняти2
2. Докер Образ на docker.hub привязанный к коду в github. С функцией автосборки.
3. Кубернетис кластер в котором в манифесте описан кластер с автоскейлингом и использованием образа из п.1
4. а Тип сервиса - LoadBalancer
5. Dokckerfile https://github.com/Gazman2013/kuber_home
6. https://hub.docker.com/repository/docker/gazman2013/kuber_home
7. gcloud container clusters create kubernetes
8. create manifesr deploy.yml
9. kubectl apply -f deploy.yml
10. kubectl get hpa
NAME       REFERENCE                  TARGETS                             MINPODS   MAXPODS   REPLICAS   AGE
hw-scale   Deployment/hw-deployment   36975957333m/100Mi, <unknown>/50%   3         7         3          9m50s
12. kubectl get services
NAME         TYPE           CLUSTER-IP     EXTERNAL-IP   PORT(S)        AGE
hw-service   LoadBalancer   10.59.241.72   34.91.60.55   80:30767/TCP   16m
kubernetes   ClusterIP      10.59.240.1    <none>        443/TCP        60m
13. http://34.91.60.55/
14. kubectl describe nodes|grep ext -i
15. ExternalIP:   34.90.197.92
  ExternalIP:   34.90.86.21
  ExternalIP:   34.90.37.235
