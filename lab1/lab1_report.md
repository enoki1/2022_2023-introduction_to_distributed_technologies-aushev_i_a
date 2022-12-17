University: [SPbU]
Faculty: [Mathematics & Mechanics]
Course: [Introduction to distributed technologies](https://github.com/itmo-ict-faculty/introduction-to-distributed-technologies)
Year: 2022/2023
Group: 331
Author: Aushev Islam Amarhanovich
Lab: Lab1
Date of create: 15.12.2022

В работе было сделано следующее : 1) Установлен Docker 2) Установлен minikube и запущен кластер. 3) Создано тестовое пространство имен test, и написан манифест для развертывания пода HashiCorp Vault(vault.yaml). 3) Создан сервис для доступа к контейнеру. 4) Успешно зашел в Vault, используя свой token из логов(kubectl logs <pod name>).
  
![vault](https://user-images.githubusercontent.com/74561881/208247171-e37bda6a-9f1b-4c83-9d59-8c217b9570f9.png)
![logs](https://user-images.githubusercontent.com/74561881/208247174-3af92e0c-142d-4b5b-8337-23b5dddb6a13.png)
