Репозиторий с конфигурацией ansible, был выбран способ создания Kubernetes кластера при помощи ansible.
Я выложил всего 3 основных файла hosts.yaml, на основе которого и был запущен playbook, ansible.cfg, из playbook.
hosts.yaml файл был сконфигурирован по этой инструкции https://github.com/aak74/kubernetes-for-beginners/blob/master/15-install/30-kubespray/README.md, и добавил системную конфигурацию configmap своего кластера kubernetes сделав выгрузку в kubeadm-config.yaml
