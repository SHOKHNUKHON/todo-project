# TODO проект 
Регистрация на сайте, получение данных под своим именем.

## Локальный запуск
- Поднять базу postgreSQL
- Создать БД с названием spring


- Создать роли (SQL запрос добавление ролей)
 ```sh
$ INSERT INTO public.t_role(id, name)
  VALUES (1, 'ROLE_USER'), (2, 'ROLE_ADMIN'); 
```
- Запустить проект и перейти:
http://localhost:8080/


