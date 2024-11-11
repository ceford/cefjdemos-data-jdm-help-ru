<!-- Filename: Help4.x:Site_Modules:_Wrapper / Display title: Модули: Оболочка  -->

## Описание

Тип модуля *Wrapper* позволяет отображать внешний веб-сайт в модуле. Функциональность такая же, как и у *iFrame Wrapper*, который вы можете добавить как элемент меню. Если страница, с которой связан врапер, больше, чем фрейм, будут отображаться вертикальные и горизонтальные полосы прокрутки.

### Общие элементы

Некоторые элементы этой страницы рассматриваются в отдельных статьях Справки:

* [Панели инструментов](jdocmanual?article=help/common-elements/toolbars).
* [Модули: Вкладка Модули](jdocmanual?article=help/modules/modules-module-tab).
* [Модули: Вкладка Назначение меню](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Модули: Вкладка Дополнительно](jdocmanual?article=help/modules/modules-advanced-tab).
* [Вкладка Разрешения](jdocmanual?article=help/common-elements/edit-permissions).

## Как получить доступ

- Выберите **Система → Панель управления → Модули сайта** в меню администратора. Затем...
  - Чтобы создать новый модуль: выберите кнопку **Создать** на панели инструментов. Затем...
    - Выберите необходимый тип модуля.
  - Чтобы изменить существующий модуль:
    - Найдите модуль в списке установленных модулей и выберите
      ссылку заголовка в колонке **Заголовок**.

## Скриншот

![вкладка модуля-оболочки](../../../ru/images/modules-site/modules-wrapper-module-tab.png)

## Поля формы

- **Название** Название модуля. Это также название, отображаемое
  для модуля в зависимости от поля формы *Показывать заголовок*.

### Вкладка модуля

#### Лев панель

- **URL** URL сайта или файла, который вы хотите отобразить в iframe.
- **Авто добавление** По умолчанию добавляется http://, если не обнаружено
  http:// или https:// в предоставленном вами URL. Это позволяет вам
  отключить эту функцию.
- **Полосы прокрутки** Показывать или скрывать горизонтальные и вертикальные полосы прокрутки.
- **Ширина** Ширина окна iFrame. Вы можете ввести абсолютное значение
  в пикселях или относительное значение, добавляя %.
- **Высота** Высота окна iFrame.
- **Авто высота** Высота будет устанавливаться автоматически в зависимости от размера 
  внешней страницы. Это будет работать только для страниц в вашем собственном домене.
- **Рамка** Показывать рамку вокруг iframe.
- **Имя цели** Имя iFrame, когда он используется как цель.

*Переведено с помощью openai.com*
