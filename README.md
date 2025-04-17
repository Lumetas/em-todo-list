Выполнено согласно [ТЗ](https://drive.google.com/file/d/1_LnL59MlJPiHJsglyRnRAubZ1Lm65Ot4/view)

Установка:
```
git clone https://github.com/Lumetas/em-todo-list.git;
cd em-todo-list;
composer install;
php artisan migrate;
php artisan serve;
```

Ендпоинты согласно ТЗ:
- Создание задачи: POST /tasks (поля: title, description, status).
- Просмотр списка задач: GET /tasks (возвращает все задачи).
- Просмотр одной задачи: GET /tasks/{id}.
- Обновление задачи: PUT /tasks/{id}.
- Удаление задачи: DELETE /tasks/{id}.