## Зависимости:

Перед выполнением плейбука необходимо убедиться, что:

`ansible` установлен версией >= `2.5`

Установлены перечисленные ниже пакеты:
```bash
sudo pip2 install awscli boto boto3
```

Сконфигурирована утилита для доступа к консоли управления облачными сервисами Амазон (добавлены ключи авторизации в файл настроек awscli):
https://docs.aws.amazon.com/cli/latest/userguide/cli-chap-getting-started.html

## Запуск

Просто выполнить:
```bash
ansible-playbook stroylandiyagq.yml
```
