<!-- Filename: Help4.x:Menu_Item:_Single_Article / Display title: Меню: Материал -->

## Описание

The Single Article menu item type is used to show one article in the
Frontend of the site.

## Как открыть

Select **Menus → \[name of the menu\]** from the Administrator menu.

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Single Article** item.

To edit a Menu Item:

- select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/6/6b/Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png/800px-Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/6b/Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png/1200px-Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/6/6b/Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png/1600px-Help-4x-Menus-Item-Articles-Single-Article-screen-ru.png 2x"
data-file-width="2880" data-file-height="1452" width="800" height="403"
alt="Menus Item Articles Single Article screen" />

## Form Fields

- **Title**. The title that will display for this menu item.
- **Alias**. The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.

### Подробности

#### Left Panel

- **Menu Item Type**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Select Article**. This field holds the article to be shown in the
  menu item. Press the **Select/Change** button to open the article
  selection window.This screen is similar to the
  Articles
  page. You can use the Filter fields to find the desired article and
  then click on the article's Title to select it. At that point, the
  modal window will close and the title will show in the Select Article
  field.
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window**. Select from the dropdown list.
- **Template Style**. Select from the dropdown list.

#### Right Panel

- **Menu**. Shows which menu the link will appear in.

### Параметры

The Options determine how the article will show on the Frontend Site
layout.

<img
src="https://docs.joomla.org/images/thumb/e/ea/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/e/ea/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/e/ea/Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Single-Article-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1340" width="600" height="279"
alt="Menus Item Articles Single Article options subscreen" />

Note: Options include "**Use Global**". If this is selected, the setting
from the Articles: Options
will be used.

#### Макет

- **Title**. Show the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- **Вводный текст**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.
- **Позиция информации о материале**.
  - Above: Puts the article information block above the text.
  - Below: Puts the article information block below the text.
  - Split: Splits the article information block into 2 separate blocks.
    One block is above and the other is below the text.
- **Article Info Title**. Displays 'Details' on top of the article
  information block.

#### Категория

- **Category**. Show the Article's Category Title.
- **Link Category**. Show the title as a link to that Category.Note: You
  can set this to be either a blog or list layout with the Choose a Layout
  option in the Category Tab.
- **Parent Category**. Show the Article's Parent Category Title.
- **Link Parent Category**. Show the title as a link to that
  Category.Note: You can set this to be either a blog or list layout
  with the Choose a Layout
  option in the Category Tab.

#### Связи

- **Associations**. Show the associated flags or Language Code.
  Multilingual only.

#### Автор

- **Author**. Show the author of the Article.
- **Link to Author's Contact Page**. Show it as a link to a Contact
  layout for that author.Note: The author must be set up as a
  Contact.
  Also, a link will not show if there is an Author Alias
  value for the article.

#### Дата

- **Create Date**. Show the Article's create date.
- **Modify Date**. Show the Article's modify date.
- **Publish Date**. Show the Article's start publishing date.

#### Параметры

- **Navigation**. Show a navigation link 'Prev' or 'Next' when you drill
  down to the article.
- **Hits**. Show the number of times the article has been displayed by a
  user.
- **Tags**. Show the tags for each article.
- **Неавторизованные ссылки**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.
- **Позиция ссылок**.
  - Above: Links are shown above the content.
  - Below: Links are shown below the content.

### Common Options

See Menus: New Item
for help on fields common to all Menu Item types, including:

- Right Panel
- Тип
  ссылки
- Страница
- Метаданные
- Связи
- Привязка
  модулей

## Панель инструментов

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Сохранить**. Saves the menu item and stays in the current screen.
- **Сохранить и закрыть**. Saves the menu item and closes the current
  screen.
  - **Сохранить и создать**. Saves the menu item and keeps the editing
    screen open and ready to create another menu item.
- **Закрыть**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made.
- **Справка**. Opens this help screen.

## Быстрые советы

- If you have a Single Article Layout defined for an article, that
  layout will show any time a user drills down to that article. For
  example, if an article is shown on another menu item type (for
  example, in a Category Blog or List Layout or a Featured Articles
  Layout), the user will be taken to the Single Article Layout for that
  article (if defined).
- Archived articles are no longer published but are still stored on the
  site. Articles are Archived using the Articles screen. Note that
  Articles assigned to the 'Uncategorised' Section will not show on the
  Archived Article List layout.
