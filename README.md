# Ansible

### Файл inventory (hosts.ini)

```
[all]
netology-ml ansible_host=IP_ADDRESS ansible_user=ansible ansible_ssh_private_key_file=~/.ssh/id_rsa
```

### Запуск playbook и получение лога

1. Сохраните `homework.yaml` и `hosts.ini` в одной директории.
2. Выполните команду:
```
ansible-playbook -i hosts.ini homework.yaml -v | tee ansible_log.txt
```
