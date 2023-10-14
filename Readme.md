# DEVOPS-21: Дипломное задание по профессии «DevOps-инженер»

### Автор: Желобанов Е.Ю.

#### 14 октября 2023 г.

---

#### Создание кластера Kubernetes с помощью Ansible и Kubespray

В файле [public_ips.yaml](inventory/group_vars/all/public_ips.yaml) указать публичные IP адреса серверов в Yandex.Cloud.

Выполнить команду `ansible-playbook -i inventory/hosts.yaml site.yaml`, дождаться завершения.
