<!-- Filename: Help4.x:Articles:_Options / Display title: Материалы: Настройки -->

## Описание

Used to set global defaults for menu items that display articles. These default values will be used when 'Use Global'
is selected for an option in an Articles menu item.

For example, to show the 'Create Date' for an article in your Articles
menu items, then set that option to 'Show' here and it will be the
default value.

You do not need to set any of these options. Your Joomla site will work
with the default settings.

## Как открыть
Выбирать **Контент → Материалы**

- click the **Options** toolbar button

## Скриншот

![Articles options screenshot](../../../ru/images/articles/articles-options-articles-tab.png "Articles options")

## Form Fields

### Материалы

Options used in articles and the menu items Blog, List, Featured Articles,
List All Categories, and Single Article.

#### Макет

- **Макет**. Select the default value for Single Article menu items.
- **Заголовок**. Show the Article's Title.
- **Заголовок как ссылка**. Show the title as a link to the article.
- **Вводный текст**.
  - Показать: The Intro Text of the article will show when you drill
    down to the article.
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
  Multilingual only.
  - **Изображения флагов**. Display language choice as image flags.

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

#### Материалы

- **Ссылки "Назад/Вперед"**. Show a navigation link 'Prev' or 'Next'
  when you drill down to the article.
- **Ссылка "Подробнее"**. Show the Read More link to link from the part
  of the article before the Read More break to the rest of the Article.
- **Заголовок со ссылкой "Подробнее"**.
  - Показать: The article title is part of the Read More link. The link
    will be in the format "Read More: \[article title\]".
  - Скрыть: The link will be "Read more".
- **Количество символов**. The maximum number of characters from the
  title to include.Note: This can prevent the Read More text to become
  excessively long if the article has a very long title.
- **Теги**. Show the tags for each article.
- **Записывать просмотры**. Record the number of times the article has
  been viewed.
- **Количество просмотров**. Show the number of times the article has
  been displayed by a user.
- **Неавторизованные ссылки**.
  - Да: The Intro Text for restricted articles will show. Clicking on
    the Read more link will require users to log in to view the full
    article content.
  - Нет: Articles that the user is not authorised to view (based on the
    viewing access level for the article) will not show.
- **Позиция ссылок**.
  - Сверху: Links are shown above the content.
  - Снизу: Links are shown below the content.

### Форма

Options of the article editing page.

![Articles options editing layout tab](../../../ru/images/articles/articles-options-editing-layout-tab.png "Articles options editing layout")

- **Включить CAPTCHA**. Select the captcha plugin
  that will be used in the article submit form. If 'Use Global' is
  selected, make sure a captcha plugin is selected in Global Configuration.
- **Публикация**. Hide the Publishing Options tab
  in the Backend when editing Articles. This means that Backend users
  will not be able to edit the fields in this tab. These fields will
  always be set to their default values.
- **Отображение**. Hide the Article Options tab
  in the Backend when editing Articles. This means that Backend users
  will not be able to edit the fields in this tab. These fields will
  always be set to their default values.
- **Форма редактирования**. Hide the Configure Edit Screen tab
  when editing Articles.
- **Права доступа**. Hide the Permissions tab
  when editing Articles.
- **Языковые связи**. Hide the Associations tab
  when editing Articles.
- **История версий**. Save version history for Articles and Categories.
- **Количество версий**. The maximum number of versions to store for an
  Article or Category. If an Article or Category is saved and the
  maximum number of versions has been reached, the oldest version will
  be deleted automatically. If set to "0", then versions will never be
  deleted automatically.
- **Изображения и ссылки (сайт)**. Hide the Images and Links tab in the
  Frontend article editor screen.
- **Изображения и ссылки (панель управления)**. Hide the Images and
  Links tab in the Backend when editing Articles.
- **Окно браузера для ссылки A**. Sets the default value for the target
  for the first Link in the article. Choices are:
  - Родительское окно: Opens the in the main browser window, replacing
    the current Joomla article.
  - Новое окно: Opens the link in a new browser window.
  - Всплывающее окно: Opens the link in a popup browser window (without
    full navigation controls).
  - Модальное окно: Opens the link in a modal popup window.
- **Окно браузера для ссылки B**. Sets the default value for the target
  for the second Link in the article. Same options as URL A.
- **Окно браузера для ссылки C**. Sets the default value for the target
  for the third Link in the article. Same options as URL A.
- **CSS-класс изображения вводного текста**. Sets the class attribute
  for an Intro Image selected in the Intro Image field.
- **CSS-класс изображения полного текста**. Sets the class attribute for
  an Full Article Image selected in the Full Article Image field.

### Категория

Options control how a Category and its articles will show. They are used
in categories and the menu items Blog, List, and List All Categories.

![Articles options category tab](../../../ru/images/articles/articles-options-category-tab.png "Articles options category")

- **Макет**. Select the default layout to show when you click on a
  Category link.
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

### Категории

Options control the display of the menu item List All Categories.

![Articles options categories tab](../../../ru/images/articles/articles-options-categories-tab.png "Articles options categories")

- **Описание категории высшего уровня**. Show the description for the
  top-level category.
- **Уровни подкатегорий**. Control how many levels of subcategories to
  show.
- **Пустые категории**. Show categories that don't contain any articles
  or subcategories.
- **Описания подкатегорий**. Show the description for subcategories.
- **Количество материалов в категории**. Show a count of the total
  number of articles in each category.

### Блог

Options control the layout of the menu items Blog, Featured Articles,
and List All Categories.

![Articles options blog and featured layout tab](../../../ru/images/articles/articles-options-blog-layouts-tab.png "Articles options blog andfeatured layout")

- **Во всю ширину**. Number of Articles to show using the full width of
  the main display area. "0" means that no Articles will show when using
  the full width. If an Article has a "Read more..." break, only the
  part of the text before the break (the Intro text) will display.
- **Главный CSS-класс материалов**. You can add any CSS class for your
  own styling ideas. Add a border on top with class boxed.For image
  position use for example image-left, image-right. Add image-alternate
  for alternate ordering of intro images.
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
  - Поперек: Order articles going across the columns and then back to
    the first column, for example:
- **Количество ссылок на другие материалы**. The number of Links to
  display in the Links area of the page. These links allow a User to
  link to additional Articles, if there are more Articles than can fit
  on the first page of the Blog Layout.
- **Уровни подкатегорий**.
  - Нет: Only articles from the current category will show.
  - Все: All articles from the current category and all subcategories
    will show.
  - 1-5: All articles from the current category and subcategories up to
    and including that level will show.
- **Изображение вводного текста как ссылка**. If Yes, a click on the
  intro image shows the article.

### Список

Options control the layout of the menu items List and List All Categories.

![Articles options list layouts tab](../../../ru/images/articles/articles-options-list-layouts-tab.png "Articles options list layouts")

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
- **Количество просмотров в списке**. Show the number of hits for
  articles.
- **Автор в списке**. Show the name of the author.
- **Количество материалов в списке**. Number of articles shown in the
  list.

### Общие

Options shared by the menu items Blog, List, and Featured Articles.

![Articles options shared tab](../../../ru/images/articles/articles-options-shared-tab.png "Articles shared")

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
  - Порядок в Joomla: Articles are ordered according to the Order column
    entered in
    Articles.
  - В обратном порядке: Articles are ordered reverse to the according of
    the Order column entered in
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
- **Избранные материалы**.
  - Показать: Display featured articles and non-featured articles.
  - Скрыть: Display only non-featured articles.
  - Только: Display only featured articles.

### Интеграция

Options control how Articles integrate News Feeds, Routing, Custom
Fields, and Workflow.

![Articles options integration tab](../../../ru/images/articles/articles-options-integration-tab.png "Articles options integration")

#### Лента новостей

- **Ссылка на RSS**. If set to Show, a Feed Link will show up as a feed
  icon in the address bar of most browsers.
- **Для материалов ленты показывать**.
  - Вводный текст: Only the article's intro text will show in the feed.
  - Полный текст: The entire text of the article will show in the feed.
- **Ссылка "Подробнее"**. Show a "Read more" link in the feed.

#### Маршрутизация

- **Удалить ID из URL**. Remove the database id of articles in a link.

#### Настраиваемые поля

- **Настраиваемые поля**. Enable the creation of custom fields.

#### Процессы

- **Процессы**. Use customised workflows to manage articles.

### Права доступа

This section lets you set up the default Access Control List
permissions for all articles in all categories.

![Articles options permissions tab](../../../ru/images/articles/articles-options-permissions-tab.png "Articles options permissions")

To change the permissions for articles and categories, do the following.

1.  Select the **Group** by clicking its title located on the left.
2.  Find the desired **Action**.
    - **Управлять параметрами и правами**. Users can edit the options
      and permissions.
    - **Управлять параметрами**. Users can edit the options exept the
      permissions.
    - **Доступ в панели управления**. Users can access user
      administration interface.
    - **Создать**. Users can create articles and categories.
    - **Удалить**. Users can delete articles and categories.
    - **Редактировать**. Users can edit articles and categories.
    - **Изменить состояние**. User can change the published state and
      related information.
    - **Редактировать свои**. Users can edit own created articles and
      categories.
    - **Редактировать значение поля**. Users can edit any value of
      custom fields submitted in articles and categories.
    - **Управлять процессами**. Users can manage workflows.
    - **Выполнить переход**. Users can execute transitions.
3.  Select the desired permission for the action you wish to change.
    - **Унаследовано**. Inherited for users in this Group from the
      Global Configuration
      permissions.
    - **Разрешено**. Allowed for users in this Group.Note: If this
      action is Denied at one of the higher levels, the Allowed
      permission here will not take effect. A Denied setting cannot be
      overridden.
    - **Запрещено**. Denied for users in this Group.
4.  Click **Save** in **Toolbar** at top. When the screen refreshes, the
    Calculated Setting column will show the effective permission for
    this Group and Action.

## Панель инструментов

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Сохранить**. Saves the articles options and stays in the current
  screen.
- **Сохранить и закрыть**. Saves the articles options and closes the
  current screen.
- **Закрыть**. Закрывает текущий экран и возвращает к предыдущему
  экрану, без сохранения внесенных изменений.
- **Подсказки**. Show help text below some options.
- **Справка**. Opens this help screen.

## Быстрые советы

- If you are a beginning user, you can just keep the default values here
  until you learn more about using global options.
- If you are an advanced user, you can save time by creating good
  default values here. When you set up menu items and create articles,
  you will be able to accept the default values for most options.
- All values set here can be overridden at the menu item, category, or
  article level.
