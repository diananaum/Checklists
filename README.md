## Задание
Составление чеклиста для функциональной проверки личного кабинета зарегистрированного авторизованного пользователя, включая функционал разделов.

Ознакомиться с чеклистом можно в [гугл-документе](https://docs.google.com/spreadsheets/d/1YxKhGxbm7LuVqcvanPC2FU59khhmAhY9OSbse5bWRRY/edit?usp=sharing) или ниже:



| Модуль "Мои покупки"                                                                                         |      |
|--------------------------------------------------------------------------------------------------------------|------|
| Вкладка "Текущие заказы": просмотр информации о заказах                                                      | High |
| Вкладка "Выполненные заказы": просмотр информации о заказах                                                  | High |
| Вкладка "Отмененные заказы": просмотр информации о заказах                                                   | High |
| Вкладка "Покупки в салоне": просмотр информации о заказах                                                    | High |
| Переключение между вкладками "Текущие заказы", "Выполненные заказы", "Отмененные заказы", "Покупки в салоне" | High |

| Модуль "Личные данные"                                                                                                                                                                                                                                                                              |      |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| Валидация поля "Фамилия"                                                                                                                                                                                                                                                                            | High |
| Валидация поля "Имя"                                                                                                                                                                                                                                                                                | High |
| Валидация поля "Отчество"                                                                                                                                                                                                                                                                           | High |
| Валидация поля "Дата рождения"                                                                                                                                                                                                                                                                      | High |
| Радиобаттон "Пол":  1) Выбор "мужской",  2) Выбор "женский"                                                                                                                                                                                                                                         | High |
| Валидация поля "Телефон"                                                                                                                                                                                                                                                                            | High |
| Подтверждение по смс: 1) Проверка кнопки "Подтвердить по смс"; 2) Валидация поля "Код подтверждения из смс"; 3) Проверка кнопки "Прислать код повторно"; 4) Проверка кнопки "Подтвердить"                                                                                                           | High |
| Изменение email: 1) Проверка кнопки "Изменить"; 2) Валидация поля "Email"; 3) Проверка кнопки "Отправить код подтверждения на email"                                                                                                                                                                | High |
| Изменение пароля: 1) Проверка кнопки "Изменить пароль"; 2) Проверка кнопки "Свернуть"; 3) Валидация поля "Новый пароль"; 4) Валидация поля "Пароль еще раз"; 5) Ввести одинаковые пароли в поля "Новый пароль" и "Пароль еще раз"; 6) Ввести разные пароли в поля "Новый пароль" и "Пароль еще раз" | High |
| Привязка социальных сетей:  1) VK;  2) OK;  3) Мой мир;  4) Яндекс                                                                                                                                                                                                                                  | High |
| Проверка кнопки "Сохранить": 1) C незаполненными полями; 2) C заполненными обязательными полями; 3) Со всеми заполненными полями                                                                                                                                                                    | High |

| Модуль "Клубная карта"                                                                 |      |
|----------------------------------------------------------------------------------------|------|
| Проверка кнопки "Добавить карту"                                                       | High |
| Валидация поля "Серия"                                                                 | High |
| Валидация поля "№ карты"                                                               | High |
| Проверка кнопки "Добавить карту": 1) C заполненными полями; 2) C незаполненными полями | High |
| Проверка кнопки крестика окна "Карта HENDERSON"                                        | High |

| Модуль "Избранное"                                                                                                                                                                                 |      |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| Проверка селектора "Сортировка по"                                                                                                                                                                 | High |
| Проверка фильтра "Только в наличии": 1) Применен; 2) Не применен; 3) Применен с фильтром "Отложенные в корзине"                                                                                    | High |
| Проверка фильтра "Отложенные в корзине": 1) Применен; 2) Не применен; 3) Применен с фильтром "Только в наличии"                                                                                    | High |
| Карточка товара: 1) Переход к товару; 2) Проверка кнопки "Удалить"; 3) Проверка селектора "Выбрать размер"; 4) Проверка кнопки "Добавить в корзину"; 5) Проверка кнопки "Зарезервировать в салоне" | High |

| Модуль "Мои адреса"                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |      |
|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|
| Вкладка "Доставка курьером":  1) Проверка кнопки "Добавить адрес";  2) Валидация поля "Населенный пункт";  3) Валидация поля "Новый адрес доставки";  4) Проверка чекбоксов "Дом", "Работа", "Любимый адрес":    - если ничего не выбрано;    - если выбран чекбокс "Дом";    - если выбран чекбокс "Работа";    - если выбран чекбокс "Любимый адрес";  5) Валидация поля "Комментарий к адресу";  6) Проверка кнопки "Сохранить адрес":    - с заполненными полями;    - с незаполненными полями; 7) Проверка кнопки "Изменить адрес"; 8) Проверка кнопки "Удалить адрес" | High |
| Вкладка "Адреса салонов":  1) Валидация поля "Поиск по адресу, метро";  2) Проверка кнопки "Добавить в избранное";  3) Проверка выбора салона на карте;  4) Проверка карточки салона:     - проверка кнопки сворачивания секции "О магазине";      - проверка кнопки сворачивания секции "График работы";     - проверка кнопки сворачивания секции "Способ оплаты при получении"; 5) Проверка кнопки "Выбрать"; 6) Проверка кнопки "Вернуться к списку"; 7) Проверка кнопки "Изменить"                                                                                     | High |
| Вкладка "Пункты выдачи и постаматы":  1) Валидация поля "Поиск по адресу, метро";  2) Проверка кнопки "Добавить в избранное";  3) Проверка выбора пункта выдачи на карте;  4) Проверка карточки пункта выдачи:     - проверка кнопки сворачивания секции "Подробно";      - проверка кнопки сворачивания секции "График работы";     - проверка кнопки сворачивания секции "Способ оплаты при получении";     - проверка кнопки сворачивания секции "Как найти"; 5) Проверка кнопки "Выбрать"; 6) Проверка кнопки "Вернуться к списку"; 7) Проверка кнопки "Изменить"       | High |
| Переключение между вкладками "Доставка курьером", "Адреса салонов", "Пункты выдачи и постаматы"                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | High |

| Модуль "Мои подписки"                          |      |
|------------------------------------------------|------|
| Проверка чекбокса "Согласие на email-рассылку" | High |
| Проверка кнопки "Сохранить"                    | High |

| Модуль "Вопросы и ответы"   |        |
|-----------------------------|--------|
| Переход к товару с вопросом | High   |
| Редактирование вопроса      | Medium |
| Редактирование ответа       | Medium |

| Модуль "Мои отзывы"        |        |
|----------------------------|--------|
| Редактирование отзыва      | Medium |
| Переход к товару с отзывом | High   |
| Редактирование оценки      | Medium |

| Модуль "Навигация в личном кабинете"          |        |
|-----------------------------------------------|--------|
| Переход в разделы личного кабинета через меню | High   |
| Проверка кнопки "Назад" в разделах            | Medium |
| Проверка кнопки "Наверх" в разделах           | Medium |
| Переход между разделами личного кабинета      | High   |
