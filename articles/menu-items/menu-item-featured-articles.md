<!-- Filename: Help4.x:Menu_Item:_Featured_Articles / Display title: Меню: Избранные материалы -->

## Описание

The Featured Articles menu item type is used to show all Articles that
have been tagged as Featured in a Blog Layout.

## Как открыть

Select **Menus → \[name of the menu\]** from the Administrator menu.

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Featured Articles** item.

To edit a Menu Item:

- select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/7/7e/Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png/800px-Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/7/7e/Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png/1200px-Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/7/7e/Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png/1600px-Help-4x-Menus-Item-Articles-Featured-Articles-screen-ru.png 2x"
data-file-width="2880" data-file-height="1449" width="800" height="403"
alt="Menus Item Articles Featured Articles screen" />

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
- **Link**. The system-generated link for this menu item. This field
  cannot be changed and is for information only.
- **Target Window**. Select from the dropdown list.
- **Template Style**. Select from the dropdown list.

#### Right Panel

- **Menu**. Shows which menu the link will appear in.

### Блог

The Options control the appearance of the blog menu item.

<img
src="https://docs.joomla.org/images/thumb/0/0e/Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/0e/Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/0/0e/Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Featured-Articles-blog-layout-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Menus Item Articles Featured Articles blog layout subscreen" />

- **Select Categories**. Select the categories you want to include in
  this layout. Click the 'X' in the category box to remove category.
- **\# Leading Articles**. Number of Articles to show using the full
  width of the main display area. "0" means that no Articles will show
  when using the full width. If an Article has a "Read more..." break,
  only the part of the text before the break (the Intro text) will
  display.
- **Leading Article Class**. You can add any CSS class for your own
  styling ideas. Add a border on top with class boxed.For image position
  use for example image-left, image-right. Add image-alternate for
  alternate ordering of intro images.
- **\# Intro Articles**. Determines the number of Articles to display
  after the leading Article. These Articles will display in the number
  of columns set in the Columns parameter below. If an Article has a
  "Read more..." break, only the text before the break (Intro text) will
  display, followed by a "Read more..." link. The order in which to
  display the articles is determined by the Category Order and Article
  Order parameters below.
- **Article Class**. You can add any CSS class for your own styling
  ideas. Add a border on top with class boxed.For image position use for
  example image-left, image-right. Add image-alternate for alternate
  ordering of intro images.
- **\# Columns**. The number of columns to use in the Intro Articles
  area. This is normally between 1 and 3 (depending on the template you
  are using). If 1 is used, the Intro Articles will display using the
  full width of the display area, just like the Leading Articles.
- **Multi Column Direction**. In multi-column blog layouts, whether to
  order articles Down the columns or Across the columns.
  - Down: Order articles going down the first column and then over to
    the next column, for example:

-
  - Across: Order articles going across the columns and then back to the
    first column, for example:

-
- **\# Links**. The number of Links to display in the Links area of the
  page. These links allow a User to link to additional Articles, if
  there are more Articles than can fit on the first page of the Blog
  Layout.
- **Linked Intro Image**. If Yes, a click on the intro image shows the
  article.
- Порядок категорий**.**.
  - No Order: Articles are ordered only by the Article Order, without
    regard to Category.
  - Title Alphabetical: Categories are displayed in alphabetical order
    (A to Z).
  - Title Reverse Alphabetical: Categories are displayed in reverse
    alphabetical order (Z to A).
  - Category Order: Categories are ordered according to the Order column
    entered in Articles: Categories.
- Порядок материалов**.**.
  - Featured Articles Order: Articles are ordered according to the Order
    column entered in Articles: Featured.
  - Most Recent First: Articles are displayed starting with the most
    recent and ending with the oldest.
  - Oldest First: Articles are displayed starting with the oldest and
    ending with the most recent.
  - Title Alphabetical: Articles are displayed by Title in alphabetical
    order (A to Z).
  - Title Reverse Alphabetical: Articles are displayed by Title in
    reverse alphabetical order (Z to A).
  - Author Alphabetical: Articles are displayed by Author in
    alphabetical order (A to Z).
  - Author Reverse Alphabetical: Articles are displayed by Author in
    reverse alphabetical order (Z to A).
  - Most Hits: Articles are displayed by the number of hits, starting
    with the one with the most hits and ending with the one with the
    least hits.
  - Least Hits: Articles are displayed by the number of hits, starting
    with the one with the least hits and ending with the one with the
    most hits.
  - Random Order: Articles are displayed in random order.
  - Article Order: Articles are ordered according to the Order column
    entered in
    Articles.
  - Article Reverse Order: Articles are ordered reverse to the according
    of the Order column entered in
    Articles.
- **Date for Ordering**. The date used when articles are sorted by date.
  - Created: Use the article created date.
  - Modified: Use the article modified date.
  - Published: Use the article start publishing date.
  - Unpublished: Use the article unpublished date.
- **Pagination**. Pagination provides page links at the bottom of the
  page that allow the User to navigate to additional pages. These are
  needed if the Articles will not fit on one page.
  - Hide: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Show: Pagination links shown if needed.
  - Auto: Pagination links shown if needed.
- **Pagination Summary**. Show the current page number and total pages
  (e.g., "Page 1 of 2") at the bottom of each page.

### Отображение

The Options determine how the articles will show in the blog menu
item.
Options include "Use Article Settings". If this is selected, the setting
from Articles: Edit
will be used.

<img
src="https://docs.joomla.org/images/thumb/3/31/Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/3/31/Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/3/31/Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Featured-Articles-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1274" width="600" height="265"
alt="Menus Item Articles Featured Articles options subscreen" />

Макет

- **Title**. Show the Article's Title.
- **Linked Titles**. Show the title as a link to the article.
- Вводный текст**.**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Hide: Only the part of the article after the Read More break will
    show.
- Позиция информации о материале**.**.
  - Above: Puts the article information block above the text.
  - Below: Puts the article information block below the text.
  - Split: Splits the article information block into 2 separate blocks.
    One block is above and the other is below the text.
- **Article Info Title**. Displays 'Details' on top of the article
  information block.

Категория

- **Category**. Show the Article's Category Title.
- **Link Category**. Show the title as a link to that Category.Note: You
  can set this to be either a blog or list layout with the Choose a Layout
  option in the Category Tab.
- **Parent Category**. Show the Article's Parent Category Title.
- **Link Parent Category**. Show the title as a link to that
  Category.Note: You can set this to be either a blog or list layout
  with the Choose a Layout
  option in the Category Tab.

Связи

- **Associations**. Show the associated flags or Language Code.
  Multilingual only.

Автор

- **Author**. Show the author of the Article.
- **Link to Author's Contact Page**. Show it as a link to a Contact
  layout for that author.Note: The author must be set up as a
  Contact.
  Also, a link will not show if there is an Author Alias
  value for the article.

Дата

- **Create Date**. Show the Article's create date.
- **Modify Date**. Show the Article's modify date.
- **Publish Date**. Show the Article's start publishing date.

Параметры

- **Navigation**. Show a navigation link 'Prev' or 'Next' when you drill
  down to the article.
- **"Read More" Link**. Show the Read More link to link from the part of
  the article before the Read More break to the rest of the Article.
- Заголовок со ссылкой "Подробнее"**.**.
  - Show: The article title is part of the Read More link. The link will
    be in the format "Read More: \[article title\]".
  - Hide: The link will be "Read more".
- **Hits**. Show the number of times the article has been displayed by a
  user.
- **Tags**. Show the tags for each article.
- Неавторизованные ссылки**.**.
  - Yes: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - No: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.

### Интеграция

The Options determine whether a news feed will be available for the page
and what information it will show.

<img
src="https://docs.joomla.org/images/thumb/2/2a/Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/2a/Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/2/2a/Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Featured-Articles-integration-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="820" width="600" height="171"
alt="Menus Item Articles Featured Articles integration subscreen" />

- **RSS Feed Link**. If set to Show, a Feed Link will show up as a feed
  icon in the address bar of most browsers.
- Для материалов ленты показывать**.**.
  - Intro Text: Only the article's intro text will show in the feed.
  - Full Text: The entire text of the article will show in the feed.

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

- To see an example of the featured layout, install Joomla with the
  sample data and select the Home page.
- Featured articles are selected using Articles: Featured.
