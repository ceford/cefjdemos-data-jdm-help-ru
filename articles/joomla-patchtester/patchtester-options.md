<!-- Filename: Help4.x:Components_Patch_Tester_Options / Display title: Опции тестировщика патчей  -->

## Описание

*Joomla! Patch Tester* используется тестировщиками для проверки того, что исправления кода, созданные разработчиками, действительно выполняют свои функции без нежелательных побочных эффектов. Страница *Параметры* используется для настройки подключения к Github.

### Общие элементы

Некоторые элементы этой страницы описаны в отдельных статьях справки:

* [Панели инструментов](jdocmanual?article=help/common-elements/toolbars).
* [Вкладка Разрешения](jdocmanual?article=help/common-elements/edit-permissions).

Дополнительная информация: [Руководство для чайников по тестированию ошибок в Joomla](https://brian.teeman.net/joomla/873-a-dummies-guide-to-joomla-bug-testing)

## Как получить доступ

- Выберите **Components → Patch Tester** в меню Администратора.
  - Выберите кнопку *Options* на панели инструментов.

## Скриншот

![Форма настроек Patchtester](../../../en/images/joomla-patchtester/patchtester-options-github-repository-tab.png)

## Поля формы

### Вкладка репозитория GitHub

- **Репозиторий GitHub** По умолчанию используется `Joomla! CMS`. Используйте его.

### Вкладка аутентификации GitHub

Вам необходимы аккаунт GitHub и токен GitHub. Всё бесплатно — подробности смотрите на вкладке аутентификации GitHub.

![Опции Patchtester вкладка аутентификации на GitHub](../../../en/images/joomla-patchtester/patchtester-options-github-authentication-tab.png)

- **Метод аутентификации GitHub** Выберите метод с использованием токена. Метод с использованием учётных данных не будет работать с сентября 2020 года.
- **Токен GitHub** Вставьте токен, полученный из GitHub.

### Вкладка настроек сервера CI

Эти настройки используются для автоматического тестирования. Используйте значения по умолчанию для ручного тестирования.

![Опции Patchtester вкладка настроек сервера CI GitHub](../../../en/images/joomla-patchtester/patchtester-options-ci-server-settings-tab.png)

- **Адрес сервера CI** По умолчанию: `https://ci.joomla.org`
- **Переключить интеграцию CI** По умолчанию: Выключено

*Переведено с помощью openai.com*

