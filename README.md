# kubernetes_hw
1. дз kubernetes заняти2
2. Докер Образ на docker.hub привязанный к коду в github. С функцией автосборки.
3. Кубернетис кластер в котором в манифесте описан кластер с автоскейлингом и использованием образа из п.1
4. а Тип сервиса - LoadBalancer
5. https://github.com/Gazman2013/kuber_home
6. https://hub.docker.com/repository/docker/gazman2013/kuber_home
7. gcloud container clusters create kubernetes
8. create manifesr deploy.yml
9. kubectl apply -f deploy.yml
10. kubectl get hpa
NAME       REFERENCE                  TARGETS                             MINPODS   MAXPODS   REPLICAS   AGE
hw-scale   Deployment/hw-deployment   36975957333m/100Mi, <unknown>/50%   3         7         3          9m50s
11. 
