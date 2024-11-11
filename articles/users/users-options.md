<!-- Filename: Help4.x:Users:_Options / Display title: Пользователи: Настройки  -->

## Описание

Страница *Пользователи: Опции* используется для задания глобальных параметров для всех пользователей, включая:

- Captcha,
- разрешение и тип регистрации,
- группу пользователей по умолчанию для новых пользователей,
- сброс счётчика паролей или имени пользователя,
- уведомление администрации по электронной почте о регистрации нового пользователя и многое другое.

## Как получить доступ

* Выберите **Сайт → Пользователи** на *Главной панели мониторинга*. Или...
* Выберите **Пользователи → Управление** в меню Администратора. Затем...
* Выберите кнопку **Параметры** на панели инструментов

## Скриншот

![параметры пользователей вкладка пользовательские параметры](../../../ru/images/users/users-options-user-options-tab.png)

## Поля формы

### Вкладка Параметры пользователя

- **Разрешить регистрацию пользователей**
  - *Да* Пользователи могут зарегистрироваться с фронтенда сайта, используя
    ссылку *Создать аккаунт*, предоставленную в форме входа.
  - *Нет* Ссылка *Создать аккаунт* не будет отображаться.
- **Группа регистрации новых пользователей** Группа, к которой пользователи назначаются по умолчанию при регистрации на сайте. По умолчанию: *Зарегистрированные*.
- **Гостевая группа пользователей** Группа, к которой назначаются гости (Гостями
  являются посетители сайта, которые не вошли в систему). Возможно
  создать контент на сайте, который виден гостям, но не виден
  авторизованным пользователям.
- **Отправить пароль** Если установлено *Да*, первый пароль пользователя будет
  отправлен по электронной почте в письме о регистрации.
- **Активация аккаунта нового пользователя**
  - *Нет* Аккаунт пользователя будет активирован сразу без дополнительных действий.
  - *Самостоятельная* Пользователь получит электронное письмо с ссылкой активации. Аккаунт будет активирован, когда пользователь выберет ссылку активации.
  - *Администратор* Пользователь получит электронное письмо с ссылкой активации. Когда пользователь выберет эту ссылку, Администратор сайта будет уведомлен по электронной почте и попросят активировать учетную запись пользователя.
- **Отправить письмо администраторам** Отправить уведомление по электронной почте
  администраторам с активацией учетной записи пользователя в режиме *Нет* или *Самостоятельная*.
- **Капча** Плагин Капча для регистрации учетной записи пользователя, напоминания
  пароля и напоминания имени пользователя.
- **Параметры фронтенда пользователя**
  - *Показать* Пользователи смогут изменять основные настройки с фронтенда сайта.
  - *Скрыть* Пользователь не сможет изменить эти настройки.
- **Язык фронтенда** Показать или скрыть язык сайта. ...
- **Изменение имени пользователя** Разрешить пользователю изменить имя пользователя.

### Вкладка Параметры домена электронной почты

![вкладка параметров домена электронной почты пользователей ](../../../ru/images/users/users-options-email-domain-options-tab.png)

- **Имя домена** Введите список разрешенных и запрещенных доменов электронной почты.
  По умолчанию все домены разрешены. Поддерживаются подстановочные знаки (\*). Например:
  - \* (звездочка): Разрешает или запрещает все домены
  - \*.com: Разрешает или запрещает все домены '.com'
  - \*.joomla.org: Разрешает или запрещает все поддомены 'joomla.org'.
- **Правило** Выберите, разрешить или запретить домен.

### Вкладка Параметры пароля

![вкладка параметров пароля пользователей ](../../../ru/images/users/users-options-password-options-tab.png)

- **Максимальное количество сбросов** Максимальное количество разрешенных
  сбросов пароля в течение определенного времени. Ноль указывает на отсутствие ограничений.
- **Время сброса** Временной период, в течение которого ведётся учёт сбросов пароля, в часах.
- **Минимальная длина** Установить минимальную длину для пароля.
- **Минимальное количество цифр** Установить минимальное количество цифр, которые должны
  быть включены в пароль.
- **Минимальное количество символов** Установить минимальное количество символов (таких как !@#\$),
  требуемых в пароле.
- **Минимальное количество заглавных букв** Установить минимальное количество заглавных
  букв, требуемых в пароле.
- **Минимальное количество строчных букв** Установить минимальное количество строчных
  букв, требуемых в пароле.

### Вкладка Многофакторная аутентификация

![вкладка многофакторной аутентификации пользователей ](../../../ru/images/users/users-options-multi-factor-authentication-tab.png)

- **Разрешенные позиции модулей на фронтенде** При отображении страницы
  многофакторной аутентификации на фронтенде все модули будут скрыты, кроме
  тех, которые выбраны здесь.
- **Показать заголовок на фронтенде** Отображать заголовок на странице
  многофакторной аутентификации на фронтенде? Обратите внимание, что
  заголовок всегда отображается в бэкэнде. Если вы хотите изменить
  заголовок, переопределите языковой ключ `COM_USERS_HEADING_MFA` с помощью
  переопределений языков.
- **Разрешенные позиции модулей на бекэнде** При отображении на
  странице многофакторной аутентификации на бэкэнде все модули будут скрыты, кроме
  тех, которые выбраны здесь. Обратите внимание, что модули в позиции
  `title` всегда отображаются: это необходимо для
  отображения значка и заголовка страницы на бекэнде.
- **Отключить многофакторную аутентификацию** Любой пользователь, который принадлежит к *любой*
  из выбранных групп пользователей, будет освобожден от многофакторной
  аутентификации. Даже если они настроили методы многофакторной
  аутентификации, их не попросят использовать их при входе в
  систему и они не смогут их просматривать, удалять или изменять их
  конфигурацию.
- **Принудительная многофакторная аутентификация** Любой пользователь,
  который принадлежит *любому* из выбранных групп пользователей, должен будет включить
  многофакторную аутентификацию, прежде чем сможет использовать сайт.
- **Стиль шаблона фронтенда** Выберите стиль шаблона
  фронтенда для использования на странице многофакторной
  аутентификации. Выберите *Использовать по умолчанию*, чтобы использовать
  стиль шаблона сайта по умолчанию.
- **Многофакторная аутентификация после тихого входа** Должен ли
  пользователь пройти через многофакторную аутентификацию после тихого
  входа? Тихие входы — это входы, которые не требуют имени пользователя и
  пароля, например функция Remember Me, WebAuthn и т.д.
- **Типы ответов аутентификации тихого входа (для экспертов)** Для
  экспертов. Список, разделенный запятыми, типов ответов аутентификации Joomla,
  которые считаются тихими входами. По умолчанию это `cookie` (функция
  Remember Me) и `passwordless` (WebAuthn).
- **Онбординг новых пользователей** Если пользователь еще не настроил
  многофакторную аутентификацию и эта опция включена, он будет
  перенаправлен на страницу настройки многофакторной аутентификации или
  пользовательский URL, который вы установили ниже. Это простой способ чтобы
  уведомить ваших пользователей о том, что многофакторная аутентификация
  является опцией на вашем сайте.
- **Пользовательский URL перенаправления** Если это поле не пустое, перенаправление
  выполняется на этот URL вместо страницы настройки многофакторной
  аутентификации, когда включена опция выше. Внимание: это должен быть
  URL-адрес внутри вашего сайта. Вы не можете входить на внешний
  ресурс или в другой поддомен.

### Вкладка История заметок пользователя

![вкладка истории заметок пользователей ](../../../ru/images/users/users-options-user-notes-history-tab.png)

- **Включить версии** Сохранить историю версий для заметок пользователя.
- **Максимальное количество версий** Максимальное количество хранимых
  версий заметки пользователя. Если заметка пользователя сохранена и
  достигнуто максимальное количество версий, самая старая версия будет
  автоматически удалена. Если установлено 0, версии никогда не будут удаляться автоматически.

### Вкладка Массовая рассылка пользователей

![вкладка массовой рассылки пользователей ](../../../ru/images/users/users-options-mass-mail-users-tab.png)

- **Префикс темы** Введите необязательный текст для автоматического
  вставки перед темой массового электронного письма.
- **Суффикс тела письма** Введите необязательный текст для автоматического
  вставки после текста письма (например, подпись).

### Вкладка Интеграция

![вкладка интеграции пользователей ](../../../ru/images/users/users-options-integration-tab.png)

- **Включить пользовательские поля** Включить создание пользовательских полей.

## Советы

Если вы новичок, сохраняйте значения по умолчанию здесь,
пока не узнаете больше об использовании глобальных опций.

*Переведено с помощью openai.com*  
