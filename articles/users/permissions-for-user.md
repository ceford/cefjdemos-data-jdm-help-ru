<!-- Filename: Help4.x:Permissions_for_User / Display title: Разрешения для пользователя  -->

## Описание

Страница *Разрешения для пользователя* показывает отчёт о разрешениях, отображая точные разрешения для любого пользователя по всем активам сайта. Это полезно для отладки проблем доступа пользователей.

### Общие элементы

Некоторые элементы этой страницы описаны в отдельных статьях помощи:

* [Панели инструментов](jdocmanual?article=help/common-elements/toolbars).
* [Фильтры списка](jdocmanual?article=help/common-elements/list-filters).
* [Заголовки столбцов списка](jdocmanual?article=help/common-elements/list-column-headers).
* [Пагинация списка](jdocmanual?article=help/common-elements/list-pagination).

## Как получить доступ

- Выберите **Пользователи → Управление** из меню администратора. Затем...
  - Выберите кнопку **Разрешения** для определенного пользователя.

## Скриншот

![разрешения пользователей для пользователя](../../../ru/images/users/users-permissions-for-user.png)

Над таблицей разрешений отображаются выбранные элементы, показывающие права доступа
с помощью значков для *Разрешено*, *Не разрешено* и *Запрещено*. Объяснение значков находится ниже
таблицы.

- **Вход на сайт** Может ли пользователь войти на фронтенд сайта.
- **Вход администратора** Может ли пользователь войти в бэкенд сайта.
- **Вход в веб-сервисы** Может ли пользователь получить доступ к Joomla Web Services
  API с помощью токена API суперадминистратора.
- **Доступ в оффлайн-режиме** Может ли пользователь получить доступ к фронтенду сайта, когда он
  находится в режиме оффлайн.

### Заголовки столбцов

В таблице, содержащей ресурсы сайта, показаны разрешения для выбранного пользователя.

- **Название ресурса** Имя ресурса на понятном языке.
- **Имя ресурса** Внутреннее имя ресурса.
- **Суперпользователь** Может ли пользователь выполнять действия суперадминистратора для данного ресурса
  независимо от любых других настроек разрешений.
- **Настройка параметров** Может ли пользователь редактировать параметры ресурса (кроме разрешений).
- **Доступ к административному интерфейсу** Может ли пользователь получить доступ к административному
  интерфейсу ресурса.
- **Создание** Может ли пользователь создавать контент в ресурсе.
- **Удаление** Может ли пользователь удалять контент в ресурсе.
- **Редактирование** Может ли пользователь редактировать контент в ресурсе.
- **Редактирование состояния** Может ли пользователь редактировать состояние ресурса.
- **Редактирование собственных данных** Может ли пользователь редактировать любой контент в ресурсе, которым владеет пользователь.
- **Редактирование значения пользовательского поля** Может ли пользователь редактировать любые
  значения пользовательских полей в ресурсе.
- **Левое и правое** Левые и правые значения в иерархии вложенности. Это используется
  для вложения и упорядочивания ресурсов.
- **ID** Это уникальный идентификационный номер для данного элемента, который назначается
  автоматически Joomla. Это используется для внутренней идентификации элемента
  и не может быть изменено.

*Переведено openai.com*
```
