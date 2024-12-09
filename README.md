Доска Объявлений на Django

Этот проект представляет собой доску объявлений, построенную на Django. Пользователи могут добавлять, редактировать и просматривать объявления.

Функции проекта

Регистрация пользователей
Представление signup
URL: /signup/
Описание:Пользователи могут зарегистрироваться, заполнив форму с именем пользователя и паролем.
Вход пользователей
Представление: login (не показано в вашем коде, но предполагается)
URL: /login/
Описание: Пользователи могут войти в систему, указав свои учетные данные.
Выход пользователей
Представление:logout_view
URL:/logout/
Описание:Пользователи могут выйти из своей учетной записи.
Главная страница
Представление:home
URL: /
Описание: Отображает приветственное сообщение и ссылку на доску объявлений.
Список объявлений
Представление: advertisement_list
URL: /board/
Описание: Отображает список всех объявлений.
Просмотр деталей объявления
Представление: advertisement_detail
URL: /board/advertisement/<int:pk>/
Описание: Отображает детали конкретного объявления по его идентификатору (PK).
Добавление объявления
Представление: add_advertisement
URL:/board/add/
Описание: Авторизованные пользователи могут добавлять новые объявления, заполняя форму.
Редактирование объявления
Представление: edit_advertisement
URL: /board/edit/<int:pk>/
Описание: Авторизованные пользователи могут редактировать свои объявления, заполняя форму с уже загруженными данными.