# friendship
Это API для магазина, которое позволяет управлять товарами, заказами, пользователями и другими элементами вашего магазина.

# Запуск backend
Для запуска бота на своем компьютере, вам понадобится установить следующее программное обеспечение:
- Docker
- Docker Compose
После установки Docker и Docker Compose, выполните следующие действия:
1. Клонируйте репозиторий с кодом бота: 
```
git clone https://github.com/GlebDontsov/friendship.git
```
2. Создайте .env-файл. Пример файла .env:
```
SECRET_KEY='<YOUR_SECRET_KEY>'
PASSWORD_DB='<YOUR_PASSWORD_DB>'

VK_APP_ID='<YOUR_VK_APP_ID>'
VK_SECRET_KEY='<YOUR_VK_SECRET_KEY>'
```
3. Запустите контейнеры Docker-Compose: 

```docker-compose build```

```docker-compose up```

# Технологии
- Django REST Framework
- PostgreSQL
- Docker
- Celery
- MailHog
- Redis
- OAuth2
