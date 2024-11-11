<!-- Filename: Help4.x:Menu_Item:_Single_Contact / Display title: Один контакт -->

## Описание

Тип элемента меню **Контакт** используется для отображения ссылки в меню для одного контакта с дополнительными настройками, такими как контактные данные, форма обратной связи и фильтры темы и сообщения электронной почты.

### Общие элементы

Некоторые аспекты этой страницы освещены в отдельных статьях помощи:

* [Панели инструментов](jdocmanual?article=help/common-elements/toolbars).
* [Вкладка "Детали"](jdocmanual?article=help/menu-items-common/menu-item-details).
* [Вкладка "Тип ссылки"](jdocmanual?article=help/menu-items-common/menu-item-link-type).
* [Вкладка "Отображение страницы"](jdocmanual?article=help/menu-items-common/menu-item-page-display).
* [Вкладка "Метаданные"](jdocmanual?article=help/menu-items-common/menu-item-metadata).
* [Вкладка "Ассоциации"](jdocmanual?article=help/common-elements/edit-associations).
* [Вкладка "Назначение модуля"](jdocmanual?article=help/menu-items-common/menu-item-module-assignment).

## Как получить доступ

Чтобы создать новый пункт меню «Единичный контакт»:

- Выберите **Меню → \[название меню\]** из меню администратора
  (например, **Меню → Главное меню**). Затем...
  - Нажмите кнопку **Создать** на панели инструментов. Затем...
  - Выберите кнопку выбора типа пункта меню.
  - В модальном окне выберите элемент Контакты, чтобы открыть список, а затем
    выберите элемент **Единичный контакт**.

Чтобы отредактировать существующий пункт меню «Единичный контакт»:

- Выберите его заголовок в списке пунктов меню.

## Скриншот

![Элемент меню Вкладка с деталями контакта](../../../ru/images/menu-items/contacts-single-contact-details-tab.png)

## Поля Форм

- **Заголовок Меню** Заголовок, который будет отображаться для этого элемента меню.
- **Алиас** Внутреннее имя элемента. Обычно, вы можете оставить это
  поле пустым, и Joomla заполнит его значением по умолчанию — заголовком в нижнем регистре
  с дефисами вместо пробелов.

### Опции Отображения Контактов

Опции отображения контактов управляют внешним видом макета списка.

![Меню Элемента Единичный контакт вкладка опций отображения контакта](../../../ru/images/menu-items/contacts-single-contact-contact-display-options-tab.png)

- **Категория Контакта** Показать или скрыть вид отображения категории контакта.
    Доступны следующие опции.
    - *Использовать Общее* Использовать значение по умолчанию с экрана опций контактов.
    - *Скрыть* Не показывать имя категории контактов.
    - *Показать Без Ссылки* Показать имя категории контактов только как текст в стиле заголовка.
    - *Показать Со Ссылкой* Показать имя категории контактов как текст в стиле заголовка,
    связанный с категорией.
- **Список выбора Контактов** Показать или скрыть, чтобы позволить пользователю использовать выпадающий 
  список всех контактов в одной категории контакта. 
- **Имя** Показать или скрыть *Имя* контакта.
- **Теги** Показать или скрыть теги контакта.
- **Информация о Контакте** Если установлено значение Показать, будут доступны следующие поля:
  - **Должность Контакта** Показать или скрыть *Должность Контакта*.
  - **Электронная почта** Показать или скрыть *Электронную почту* контакта.
  - **Адрес улицы** Показать или скрыть *Адрес улицы* контакта.
  - **Город или Район** Показать или скрыть *Город или Район* контакта.
  - **Штат или Область** Показать или скрыть *Штат или Область* контакта.
  - **Почтовый индекс** Показать или скрыть *Почтовый индекс* контакта.
  - **Страна** Показать или скрыть *Страну* контакта.
  - **Телефон** Показать или скрыть *Телефон* контакта.
  - **Мобильный телефон** Показать или скрыть *Мобильный телефон* контакта.
  - **Факс** Показать или скрыть *Факс* контакта.
  - **Веб-страница** Показать или скрыть *Веб-страницу* контакта.
  - **Изображение** Показать или скрыть *Изображение* контакта.
- **vCard** Отобразить *vCard* контакта.
- **Различная Информация** Отобразить *Различную Информацию* контакта.
- **Статьи Пользователя** Отобразить *Статьи* контакта.
- **\# Статей для Списка** Количество статей контакта для списка.
- **Ссылки Контакта** Показать или скрыть *дополнительные ссылки* контакта. Это могут быть
  ссылки на аккаунты в социальных сетях, такие как Twitter, Facebook, Skype...
- **Ярлык Ссылки \<буква\>**. Ярлыки (A до E) для переопределения
  показанного ярлыка ссылки.

### Опции Почты

![Меню Элемента Единичный контакт вкладка опций почты](../../../ru/images/menu-items/contacts-single-contact-mail-options-tab.png)

- **Форма Связи** Показать или скрыть форму *связи* контакта.
- **Отправить Копию Подавшему** Показать или скрыть флажок
  для разрешения подающему отправить копию письма себе.
- **Проверка Сессии** Проверять наличие куки для сессии. Пользователи с отключенными
  куки не смогут отправлять электронные письма.
- **Персональный Ответ** Включить или выключить персональное сообщение-ответ для отправителя
  формы связи.
- **Перенаправление Контактов** Введите альтернативный URL для перенаправления отправителя
  после успешной отправки письма через форму связи.

*Переведено openai.com*
