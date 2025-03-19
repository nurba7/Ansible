# Ansible

### Запуск playbook и получение лога

1. Сохраните `homework.yaml` и `hosts.ini` в одной директории.
2. Выполните команду:
```
ansible-playbook -i hosts.ini homework.yaml -v | tee ansible_log.txt
```
