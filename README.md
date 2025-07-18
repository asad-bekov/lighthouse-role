# Ansible Role: LightHouse

Роль устанавливает LightHouse — веб-интерфейс для ClickHouse.

## Переменные роли

| Переменная         | Описание                    | Значение по умолчанию    |
|--------------------|-----------------------------|--------------------------|
| lighthouse_repo    | Репозиторий LightHouse      | https://github.com/VKCOM/lighthouse.git |
| lighthouse_dest    | Куда клонировать LightHouse | /opt/lighthouse          |

## Пример использования

```yaml
- hosts: all
  roles:
    - role: lighthouse-role
```

## Требования

- Debian/Ubuntu, nginx, git
