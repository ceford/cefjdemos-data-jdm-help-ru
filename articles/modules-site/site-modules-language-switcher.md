<!-- Filename: Help4.x:Site_Modules:_Language_Switcher / Display title: Модули: Переключатель языка -->

## Описание

Модуль типа *Переключатель языка* позволяет переключаться между доступными языками контента. Выбор языка перенаправит вас на соответствующую страницу для этого языка.

### Общие элементы

Некоторые элементы этой страницы описаны в отдельных справочных статьях:

* [Панели инструментов](jdocmanual?article=help/common-elements/toolbars).
* [Модули: вкладка Модули](jdocmanual?article=help/modules/modules-module-tab).
* [Модули: вкладка Назначение меню](jdocmanual?article=help/modules/modules-menu-assignment-tab).
* [Модули: вкладка Расширенные параметры](jdocmanual?article=help/modules/modules-advanced-tab).
* [Вкладка Разрешения](jdocmanual?article=help/common-elements/edit-permissions).

## Как получить доступ

- Выберите **Система → Управление панелью → Модули сайта** в меню администратора. Затем...
  - Чтобы создать новый модуль: выберите кнопку **Создать** на панели инструментов. Затем...
    - Выберите требуемый тип модуля.
  - Чтобы редактировать существующий модуль:
    - Найдите модуль в списке установленных модулей и выберите
      ссылку на название в столбце **Название**.

## Скриншот

![вкладка модуля переключателя языка](../../../ru/images/modules-site/modules-language-switcher-module-tab.png)

## Поля формы

- **Заголовок** Заголовок модуля. Он также отображается как заголовок модуля в зависимости от поля формы *Показывать заголовок*.

### Вкладка модуля

#### Левый панель

- **Предварительный текст** Это текст или HTML, отображаемый над переключателем языков.
- **Последовательный текст** Это текст или HTML, отображаемый под переключателем языков.
- **Использовать раскрывающийся список** Три следующих элемента изменяются для *Да* и *Нет*
  - **Нет**
    - **Использовать флаги в виде изображений** Если установлено *Да*, отображает выбор языка в виде изображений-флагов. В противном случае используется название языка на родном языке. Если установлено *Нет*, появляется дополнительное поле: **Полные названия языков**, которое отображает код языка из двух заглавных букв для каждого языка.
    - **Активный язык** Отображать или нет активный язык. Если отображать, класс `lang-active` будет добавлен к элементу.
    - **Горизонтальное отображение** По умолчанию установлено *Да*, т.е. создается горизонтальный список. Установите значение *Нет*, чтобы получить вертикальный список.
  - **Да** Элемент *Активный язык* отображается выбранным.
    - **Использовать флаги для раскрывающегося списка** Если установлено *Да*, флаг языка размещается перед названием языка в раскрывающемся списке.
    - **Полные названия языков** Если установлено *Нет*, отображается код языка из двух заглавных букв для каждого языка.
    - **Активный язык** Не оказывает влияния в раскрывающемся списке.

*Переведено с помощью openai.com*

