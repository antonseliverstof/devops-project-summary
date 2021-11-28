### Devops Project

#### 1. AWS Infrastructure with Terraform  
Конфигурационные файлы **Terraform**:
```
https://github.com/antonseliverstof/devops_terraform
```  
В качестве бекэнда используется **Terraform Cloud**:  
![alt text](terraform_cloud.png "Terraform_Cloud")  

#### 2. Kubernetes Cluster  
Кластер **Kubernetes** создан при помощи **Kubespray**:
```
```  





#### 3. Simple Test App  
```
https://gitlab.com/antonseliverstof/devops-test-app  
https://hub.docker.com/repository/docker/antonseliverstof/devops-test-app
```
В репозитории Gitlab находятся:
- Простое тестовое приложение **index.html**  
- Конфигурационный файл **Nginx.conf**  
- **Dockerfile** для сборки образа  

В репозитории Dockerhub:
- Готовые образы приложения  

Сборка образа и его загрузка в репозиторий происходят автоматически при коммите в ветку Main или добавлении Тэга.  

CI реализован на базе **Gitlab CI**  
![alt text](ci_pipelines_list.png "Pipelines")  
![alt text](ci_jobs.png "Jobs")  
