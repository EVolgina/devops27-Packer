# Задача 1
Создайте собственный образ любой операционной системы (например ubuntu-20.04) с помощью Packer (инструкция).
Чтобы получить зачёт, вам нужно предоставить скриншот страницы с созданным образом из личного кабинета YandexCloud.
### Ответ:
![sub](https://github.com/EVolgina/devops27-Packer/blob/main/subnet.PNG)
![vm](https://github.com/EVolgina/devops27-Packer/blob/main/yc%20image%20list.PNG)
![vmycloude](https://github.com/EVolgina/devops27-Packer/blob/main/VM%20YA%20cloud.PNG)

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
![zd22](https://github.com/EVolgina/devops27-Packer/blob/main/%D0%BE%D1%88%D0%B8%D0%B1%D0%BA%D0%B0%20%D1%82%D0%B5%D1%80%D0%B0%D1%84%D0%BE%D1%80%D0%BC.PNG)
Очень прошу помощи. Не мгу разобраться в чем проблема

# Задача 3
С помощью Ansible и Docker Compose разверните на виртуальной машине из предыдущего задания систему мониторинга на основе Prometheus/Grafana. Используйте Ansible-код в директории (src/ansible).
Чтобы получить зачёт, вам нужно предоставить вывод команды "docker ps" , все контейнеры, описанные в docker-compose, должны быть в статусе "Up".
### Ответ:

# Задача 4
Откройте веб-браузер, зайдите на страницу http://<внешний_ip_адрес_вашей_ВМ>:3000.
Используйте для авторизации логин и пароль из .env-file.
Изучите доступный интерфейс, найдите в интерфейсе автоматически созданные docker-compose-панели с графиками(dashboards).
Подождите 5-10 минут, чтобы система мониторинга успела накопить данные.
Чтобы получить зачёт, предоставьте:
скриншот работающего веб-интерфейса Grafana с текущими метриками, как на примере ниже.

### Ответ:
![]()
