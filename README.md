#Установка, настройка и использование веб-приложения

##Шаг 1: Скачать код с репозитория

git clone https://github.com/nuray0/executive_test_project.git
Шаг 2: Перейти в папку проекта


cd executive_test_project
Шаг 3: Применить миграции


docker-compose run web python manage.py migrate
Шаг 4: Создать миграции

docker-compose run web python manage.py makemigrations
Шаг 5: Запустить контейнеры Docker

docker-compose up
Шаг 6: Открыть приложение в браузере


http://0.0.0.0:8000/
Если по этому адресу не открывается, попробуйте зайти по:

http://localhost:8000/
http://127.0.0.1:8000/
Шаг 7: Создать аккаунт

Шаг 8: Создать управляющего

Шаг 9: Добавить больше информации к управляющему (по желанию)

Можно добавить информацию, такую как опыт работы, сертификаты, согласия на занятие должности и образование.

Шаг 10: Просмотреть список управляющих

На главной странице отображается список всех управляющих с краткой информацией о каждом из них.

Шаг 11: Редактировать и удалять профили управляющих (по желанию)

Вы можете редактировать и удалять управляющих, а также данные их профилей по своему усмотрению.
