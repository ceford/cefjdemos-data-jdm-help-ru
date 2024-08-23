<!-- Filename: Help4.x:Menu_Item:_Category_List / Display title: Меню: Материалы -->

## Описание

The Category List menu item type is used to show articles belonging to a
specific Category in a list layout.

## Как открыть

Select **Menus → \[name of the menu\]** from the Administrator menu.

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Category List** item.

To edit a Menu Item:

- select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/f/fa/Help-4x-Menus-Item-Articles-Category-List-screen-ru.png/800px-Help-4x-Menus-Item-Articles-Category-List-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/fa/Help-4x-Menus-Item-Articles-Category-List-screen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-List-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/f/fa/Help-4x-Menus-Item-Articles-Category-List-screen-ru.png/1600px-Help-4x-Menus-Item-Articles-Category-List-screen-ru.png 2x"
data-file-width="2880" data-file-height="1606" width="800" height="446"
alt="Menus Item Articles Category List screen" />

## Form Fields

- **Заголовок**. The title that will display for this menu item.
- **Алиас**. The internal name of the menu item. Normally, you can leave
  this blank and Joomla will fill in a default value Title in lower case
  and with dashes instead of spaces.

### Подробности

#### Left Panel

- **Тип пункта меню**. The Menu Item Type selected when this menu item
  was created. This can be one of the core menu item types or a menu
  item type provided by an installed extension.
- **Категория**. The articles that are within this category will be
  displayed.
- **Теги**. Optionally restrict displayed articles to those having the
  selected Tags.
- **Ссылка**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Окно браузера**. Select from the dropdown list.
- **Стиль шаблона**. Select from the dropdown list.

#### Right Panel

- **Меню**. Shows which menu the link will appear in.

### Категория

The Options control the way that category information is shown in the
menu item.

Options include "Use Global". If this is selected, the setting from the
Articles: Options
will be used.

<img
src="https://docs.joomla.org/images/thumb/1/1a/Help-4x-Menus-Item-Articles-Category-List-category-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Category-List-category-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/1/1a/Help-4x-Menus-Item-Articles-Category-List-category-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Category-List-category-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/1/1a/Help-4x-Menus-Item-Articles-Category-List-category-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-List-category-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Menus Item Articles Category List category subscreen" />

- **Заголовок категории**. Show the title of the category.
- **Описание категории**. Show the description for the category.
- **Изображение категории**. Show the category image.
- **Уровни подкатегорий**. Control how many levels of subcategories to
  show.
- **Пустые категории**. Show categories that don't contain any articles
  or subcategories.
- **Сообщение об отсутствии материалов**. Show a message "There are no
  articles in this category".
- **Заголовки подкатегорий**. Show the Subcategories as subheading on
  the page.
- **Описания подкатегорий**. Show the descriptions for subcategories.
- **Количество материалов в категории**. Show a count of the total
  number of articles in each category.
- **Теги категории**. Show the tags for the category.

### Список

List Layout Options control the appearance of the menu item.

<img
src="https://docs.joomla.org/images/thumb/d/da/Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/d/da/Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/d/da/Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-List-list-layouts-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Menus Item Articles Category List list layouts subscreen" />

- **Поле выбора количества элементов на странице**. Show the Display \#
  control that allows the user to select the number of articles to show.
- **Фильтр**. Show a text field in the Frontend where a user can filter
  the articles.Options in the Backend menu item edit.
  - Скрыть: Don't show a filter field.
  - Заголовок: Filter on article title.
  - Автор: Filter on the author's name.
  - Кол-во просмотров: Filter on the number of article hits.
  - Теги: Filter on the article tags.
  - Месяц (опубликовано): Filter on the month of published articles.
- **Заголовки столбцов**. Show a heading in the article list in the
  Frontend.
- **Поле даты**. Show a date in the list.
  - Скрыть: Don't show any date.
  - Создано: Show the created date.
  - Изменено: Show the date of the last modification.
  - Опубликовано: Show the start publishing date.
- **Формат даты**. Введите формат даты.
- **Количество просмотров в списке**. Show the number of hits for
  articles.
- **Автор в списке**. Show the name of the author.
- **Порядок категорий**.
  - Не упорядочивать: Articles are ordered only by the Article Order,
    without regard to Category.
  - Заголовок (по алфавиту): Categories are displayed in alphabetical
    order (A to Z).
  - Заголовок (против алфавита): Categories are displayed in reverse
    alphabetical order (Z to A).
  - Порядок в Joomla: Categories are ordered according to the Order
    column entered in Articles: Categories.
- **Порядок материалов**.
  - Порядок избранных материалов: Articles are ordered according to the
    Order column entered in Articles: Featured.
  - Новые первыми: Articles are displayed starting with the most recent
    and ending with the oldest.
  - Старые первыми: Articles are displayed starting with the oldest and
    ending with the most recent.
  - Заголовок (по алфавиту): Articles are displayed by Title in
    alphabetical order (A to Z).
  - Заголовок (против алфавита): Articles are displayed by Title in
    reverse alphabetical order (Z to A).
  - Автор (по алфавиту): Articles are displayed by Author in
    alphabetical order (A to Z).
  - Автор (против алфавита): Articles are displayed by Author in reverse
    alphabetical order (Z to A).
  - Наиболее популярные: Articles are displayed by the number of hits,
    starting with the one with the most hits and ending with the one
    with the least hits.
  - Наименее популярные: Articles are displayed by the number of hits,
    starting with the one with the least hits and ending with the one
    with the most hits.
  - В случайном порядке: Articles are displayed in random order.
  - Порядок материалов: Articles are ordered according to the Order
    column entered in
    Articles.
  - Материалы в обратном порядке: Articles are ordered reverse to the
    according of the Order column entered in
    Articles.
- **Поле даты для сортировки**. The date used when articles are sorted
  by date.
  - Создано: Use the article created date.
  - Изменено: Use the article modified date.
  - Опубликовано: Use the article start publishing date.
- **Разбиение на страницы**. Pagination provides page links at the
  bottom of the page that allow the User to navigate to additional
  pages. These are needed if the Articles will not fit on one page.
  - Скрыть: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Показать: Pagination links shown if needed.
  - Автоматически: Pagination links shown if needed.
- **Результат разбиения на страницы**. Show the current page number and
  total pages (e.g., "Page 1 of 2") at the bottom of each page.
- **Количество материалов в списке**. Number of articles shown in the
  list.
- **Избранные материалы**.
  - Показать: Display featured articles and non-featured articles.
  - Скрыть: Display only non-featured articles.
  - Только: Display only featured articles.

### Отображение

The Options determine how the articles will show in the list menu item.

<img
src="https://docs.joomla.org/images/thumb/2/2c/Help-4x-Menus-Item-Articles-Category-List-options-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Category-List-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/2c/Help-4x-Menus-Item-Articles-Category-List-options-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Category-List-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/2/2c/Help-4x-Menus-Item-Articles-Category-List-options-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-List-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1252" width="600" height="261"
alt="Menus Item Articles Category List options subscreen" />

#### Макет

- **Макет**. Select from the dropdown list.
- **Заголовок**. Show the Article's Title.
- **Заголовок как ссылка**. Show the title as a link to the article.
- **Вводный текст**.
  - Показать: The Intro Text of the article will show when you drill
    down to the article.
  - Скрыть: Only the part of the article after the Read More break will
    show.

#### Категория

- **Заголовок категории**. Show the Article's Category Title.
- **Категория как ссылка**. Show the title as a link to that
  Category.Note: You can set this to be either a blog or list layout
  with the Choose a Layout
  option in the Category Tab.
- **Заголовок родительской категории**. Show the Article's Parent
  Category Title.
- **Родительская категория как ссылка**. Show the title as a link to
  that Category.Note: You can set this to be either a blog or list
  layout with the Choose a Layout
  option in the Category Tab.

#### Связи

- **Языковые связи**. Show the associated flags or Language Code.
  Многоязычные
  связи.

#### Автор

- **Автор**. Show the author of the Article.
- **Автор как ссылка**. Show it as a link to a Contact layout for that
  author.Note: The author must be set up as a
  Contact.
  Also, a link will not show if there is an Author Alias
  value for the article.

#### Дата

- **Дата создания**. Show the Article's create date.
- **Дата изменения**. Show the Article's modify date.
- **Дата публикации**. Show the Article's start publishing date.

#### Параметры

- **Ссылки "Назад/Вперед"**. Show a navigation link 'Prev' or 'Next'
  when you drill down to the article.
- **Ссылка "Подробнее"**. Show the Read More link to link from the part
  of the article before the Read More break to the rest of the Article.
- **Заголовок со ссылкой "Подробнее"**.
  - Показать: The article title is part of the Read More link. The link
    will be in the format "Read More: \[article title\]".
  - Скрыть: The link will be "Read more".
- **Количество просмотров**. Show the number of times the article has
  been displayed by a user.
- **Неавторизованные ссылки**.
  - Да: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - Нет: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.

### Интеграция

The Options determine whether a news feed will be available for the page
and what information it will show.

<img
src="https://docs.joomla.org/images/thumb/7/79/Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/79/Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/7/79/Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-List-integration-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="810" width="600" height="169"
alt="Menus Item Articles Category List integration subscreen" />

- **Ссылка на RSS**. If set to Show, a Feed Link will show up as a feed
  icon in the address bar of most browsers.
- **Для материалов ленты показывать**.
  - Вводный текст: Only the article's intro text will show in the feed.
  - Полный текст: The entire text of the article will show in the feed.

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

- The Category List layout is a convenient way to list a compact
  directory of articles in a category that can include filtering and
  searching.
- To create a new Category see Articles: Edit Category.
- To create a new menu see
  Menus.
