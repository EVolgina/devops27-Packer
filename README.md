# Задача 1
Создайте собственный образ любой операционной системы (например ubuntu-20.04) с помощью Packer (инструкция).
Чтобы получить зачёт, вам нужно предоставить скриншот страницы с созданным образом из личного кабинета YandexCloud.
### Ответ:
![sub](https://github.com/EVolgina/devops27-Packer/blob/main/subnet.PNG)
![vm](https://github.com/EVolgina/devops27-Packer/blob/main/vmnew.PNG)
![vmycloude](https://github.com/EVolgina/devops27-Packer/blob/main/new%20vm.PNG)

# Задача 2
2.1. Создайте вашу первую виртуальную машину в YandexCloud с помощью web-интерфейса YandexCloud.
### Ответ
![zd](https://github.com/EVolgina/devops27-Packer/blob/main/sd%202%20vm.PNG)
![zd1](https://github.com/EVolgina/devops27-Packer/blob/main/zd21vm.PNG)
![zd2](https://github.com/EVolgina/devops27-Packer/blob/main/vmzd2.PNG)

# 2.2.* (Необязательное задание)
Создайте вашу первую виртуальную машину в YandexCloud с помощью Terraform (вместо использования веб-интерфейса YandexCloud). Используйте Terraform-код в директории (src/terraform).
Чтобы получить зачёт, вам нужно предоставить вывод команды terraform apply и страницы свойств, созданной ВМ из личного кабинета YandexCloud.
### Ответ:
# Задача 3
С помощью Ansible и Docker Compose разверните на виртуальной машине из предыдущего задания систему мониторинга на основе Prometheus/Grafana. Используйте Ansible-код в директории (src/ansible).
Чтобы получить зачёт, вам нужно предоставить вывод команды "docker ps" , все контейнеры, описанные в docker-compose, должны быть в статусе "Up".
### Ответ:
![docker ps](https://github.com/EVolgina/devops27-Packer/blob/main/docker.PNG)

# Задача 4
Откройте веб-браузер, зайдите на страницу http://<внешний_ip_адрес_вашей_ВМ>:3000.
Используйте для авторизации логин и пароль из .env-file.
Изучите доступный интерфейс, найдите в интерфейсе автоматически созданные docker-compose-панели с графиками(dashboards).
Подождите 5-10 минут, чтобы система мониторинга успела накопить данные.
Чтобы получить зачёт, предоставьте:
скриншот работающего веб-интерфейса Grafana с текущими метриками, как на примере ниже.

### Ответ:
![node](https://github.com/EVolgina/devops27-Packer/blob/main/node.PNG)
![grafana]( https://github.com/EVolgina/devops27-Packer/blob/main/grafana.PNG)
![]()
