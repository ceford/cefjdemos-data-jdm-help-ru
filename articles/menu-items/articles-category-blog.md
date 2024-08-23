<!-- Filename: Help4.x:Menu_Item:_Category_Blog / Display title: Меню: Блог категории -->

## Описание

A Category Blog menu item typically has one or two leading article
tasters occupying the full width of the content area followed by more
articles tasters in one, two or three columns and additional links to
more Articles in the same category.

## Как открыть

Select **Menus → \[name of the menu\]** from the Administrator menu.

To add a Menu Item:

1.  click the **New** toolbar button.
2.  click the Menu Item Type **Select** button.
3.  select the **Articles** item.
4.  select the **Category Blog** item.

To edit a Menu Item:

- select a **Title** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/5/56/Help-4x-Menus-Item-Articles-Category-Blog-screen-ru.png/800px-Help-4x-Menus-Item-Articles-Category-Blog-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/5/56/Help-4x-Menus-Item-Articles-Category-Blog-screen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/5/56/Help-4x-Menus-Item-Articles-Category-Blog-screen-ru.png/1600px-Help-4x-Menus-Item-Articles-Category-Blog-screen-ru.png 2x"
data-file-width="2880" data-file-height="1607" width="800" height="446"
alt="Menus Item Articles Category Blog screen" />

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
src="https://docs.joomla.org/images/thumb/8/88/Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/8/88/Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/8/88/Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-category-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1247" width="600" height="260"
alt="Menus Item Articles Category Blog category subscreen" />

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

### Блог

The Options control the appearance of the blog menu item.

<img
src="https://docs.joomla.org/images/thumb/2/21/Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/2/21/Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/2/21/Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-blog-layout-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Menus Item Articles Category Blog blog layout subscreen" />

- **Во всю ширину**. Number of Articles to show using the full width of
  the main display area. "0" means that no Articles will show when using
  the full width. If an Article has a "Read more..." break, only the
  part of the text before the break (the Intro text) will display.
- **Главный CSS-класс материалов**. Введите CSS-класс материалов для
  стилизации.Например, для выравнивания изображений вы можете
  использовать классы image-left, image-right, для отображения
  альтернативного порядка изображений вводного текста - класс
  image-alternate.
- **Только вводный текст**. Determines the number of Articles to display
  after the leading Article. These Articles will display in the number
  of columns set in the Columns parameter below. If an Article has a
  "Read more..." break, only the text before the break (Intro text) will
  display, followed by a "Read more..." link. The order in which to
  display the articles is determined by the Category Order and Article
  Order parameters below.
- **CSS-класс материалов**. Введите CSS-класс материалов для
  стилизации.Например, для выравнивания изображений вы можете
  использовать классы image-left, image-right, для отображения
  альтернативного порядка изображений вводного текста - класс
  image-alternate.
- **Количество столбцов**. The number of columns to use in the Intro
  Articles area. This is normally between 1 and 3 (depending on the
  template you are using). If 1 is used, the Intro Articles will display
  using the full width of the display area, just like the Leading
  Articles.
- **Порядок размещения в столбцах**. In multi-column blog layouts,
  whether to order articles Down the columns or Across the columns.
  - Вниз: Order articles going down the first column and then over to
    the next column, for example:

-
  - Поперек: Order articles going across the columns and then back to
    the first column, for example:

-
- **Количество ссылок на другие материалы**. The number of Links to
  display in the Links area of the page. These links allow a User to
  link to additional Articles, if there are more Articles than can fit
  on the first page of the Blog Layout.
- **Избранные материалы**.
  - Показать: Display featured articles and non-featured articles.
  - Скрыть: Display only non-featured articles.
  - Только: Display only featured articles.
- **Изображение вводного текста как ссылка**. If Yes, a click on the
  intro image shows the article.
- **Уровни подкатегорий**.
  - Нет: Only articles from the current category will show.
  - Все: All articles from the current category and all subcategories
    will show.
  - 1-5: All articles from the current category and subcategories up to
    and including that level will show.
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
  - Не опубликовано: Use the article unpublished date.
- **Разбиение на страницы**. Pagination provides page links at the
  bottom of the page that allow the User to navigate to additional
  pages. These are needed if the Articles will not fit on one page.
  - Скрыть: Pagination links not shown. Note: Users will not be able to
    navigate to additional pages.
  - Показать: Pagination links shown if needed.
  - Автоматически: Pagination links shown if needed.
- **Результат разбиения на страницы**. Show the current page number and
  total pages (e.g., "Page 1 of 2") at the bottom of each page.

### Отображение

The Options determine how the articles will show in the blog menu
item.
Options include "Use Article Settings". If this is selected, the setting
from Articles: Edit
will be used.

<img
src="https://docs.joomla.org/images/thumb/0/0a/Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/0/0a/Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/0/0a/Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-options-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="1300" width="600" height="271"
alt="Menus Item Articles Category Blog options subscreen" />

#### Макет

- **Макет**. Select from the dropdown list.
- **Заголовок**. Show the Article's Title.
- **Заголовок как ссылка**. Show the title as a link to the article.
- **Вводный текст**.
  - Show: The Intro Text of the article will show when you drill down to
    the article.
  - Скрыть: Only the part of the article after the Read More break will
    show.
- **Позиция информации о материале**.
  - Сверху: Puts the article information block above the text.
  - Снизу: Puts the article information block below the text.
  - Разделить: Splits the article information block into 2 separate
    blocks. One block is above and the other is below the text.
- **Заголовок информации о материале**. Displays 'Details' on top of the
  article information block.

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
- **Теги**. Show the tags for each article.
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
src="https://docs.joomla.org/images/thumb/b/bf/Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-ru.png/600px-Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/b/bf/Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-ru.png/900px-Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/b/bf/Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-ru.png/1200px-Help-4x-Menus-Item-Articles-Category-Blog-integration-subscreen-ru.png 2x"
data-file-width="2880" data-file-height="810" width="600" height="169"
alt="Menus Item Articles Category Blog integration subscreen" />

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

- To create a new Category see
- To create a new menu see
  Menus.
