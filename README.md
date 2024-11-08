Кирилл Васильев ( s063062 )

OC : Debian ( generic/debian12 ) or CentOS ( generic/centos9s )

Попытался через systemd (ветка problems), но застрял на этапе установки пакета semaphore, а именно момент с интерактивным модом установки.

Запуск плейбука:
ansible-playbook semaphore.yml -i hosts --extra-vars "target=host"
