# ERP System Infrastructure

**Инфраструктура (PostgreSQL, Redis, Adminer) для ERP System**

1. Инфраструктура (ЭТОТ РЕПОЗИТОРИЙ): [Infra](https://github.com/Esmien/erp_system_infra)
2. Бэкенд: [Backend](https://github.com/Esmien/erp_system_backend)
3. ТГ-бот: [Bot](https://github.com/Esmien/erp_system_bot)

### Запуск

1. #### Клонировать репозиторий с инфраструктурой:

```BASH
git clone https://github.com/Esmien/erp_system_infra.git
```

2. #### Перейти в директорию инфраструктуры:

```BASH
cd erp_system_infra
```

3. #### Создать .env-файл, отредактировать его и сохранить (Ctrl+O → Ctrl+X):

```BASH
cp .env.example .env && nano .env
```

4. #### Запустить инфраструктуру и вернуться в исходную директорию:

```BASH
docker compose up --build -d && cd ..
```

Поздравляю, инфраструктура запущена, можете переходить
к [бэкенду](https://github.com/Esmien/erp_system_backend/blob/master/README.md)