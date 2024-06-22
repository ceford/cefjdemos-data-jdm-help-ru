<!-- Filename: Help4.x:Users / Display title: Пользователи -->

## Описание

The Users list is used to find, add, and edit users.

## Как открыть
Выбирать **Панель управления → Site → Пользователи**

To add a User:

- click the **New** toolbar button

To edit a User:

- select a **Name** from the list

## Скриншот

<img
src="https://docs.joomla.org/images/thumb/6/6f/Help-4x-Users-screen-ru.png/800px-Help-4x-Users-screen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/6/6f/Help-4x-Users-screen-ru.png/1200px-Help-4x-Users-screen-ru.png 1.5x, https://docs.joomla.org/images/thumb/6/6f/Help-4x-Users-screen-ru.png/1600px-Help-4x-Users-screen-ru.png 2x"
data-file-width="2453" data-file-height="1500" width="800" height="489"
alt="Users screen" />

## Заголовки столбцов

- **Checkbox**. Check this box to select users. To select all users,
  check the box in the column heading. After boxes are checked the
  toolbar button 'Actions' get active.
- **Имя**. The full name of the user.
  - **Создать**. ru
    - **Показать все заметки**. Show the
      <a href="https://docs.joomla.org/Help4.x:User_Notes/ru" class="new"
      title="Special:MyLanguage/Help4.x:User Notes/ru (page does not exist)">User
      Notes</a> for the user as a list.
    - **Показать 1 заметку**. Show the User Notes for the user in a
      window and stays in the current screen.
- **Логин**. The name the user will log in as.
- **Включен**. Whether or not the user is enabled.
- **Активирован**. Whether or not the user is activated. Normally when a
  user registers from the Frontend, some type of activation is required.
  This is controlled by the 'New User Account Activation' parameter in
  the
  <a href="https://docs.joomla.org/Help4.x:Users:_Options/ru" class="new"
  title="Special:MyLanguage/Help4.x:Users: Options/ru (page does not exist)">Users:
  Options</a>.
- **Группы**. The list of groups that the user belongs to. Note that a
  user may belong to more than one group.
- **E-mail**. The email address from the user is displayed here.
- **Дата входа**. Here you can see the date on which the user last
  logged in.
- **Дата регистрации**. The date the user was registered.
- **ID**. A unique identification number for this user, you cannot
  change this number.

## List Filters

**Search bar**. Near the top of the page you will see the search bar
shown in the Screenshot above.

- **Search by Text**. Enter part of the search term and click the Search
  icon. *Hover* to see a *Tooltip* indicating which fields will be
  searched.To 'Search by ID' enter "id:x", where "x" is the ID number
  (for example, "id:19").
- **Параметры поиска**. Click to display the additional filters.
- **Очистить**. Click to clear the Filter field and restore the list to
  its unfiltered state.
- **Ordering**. Shows the current list ordering field. 2 ways to change
  the order:
  - Select from the dropdown list. Ordering may be in ascending or
    descending order.
  - Click a column heading. The column heading toggles between ascending
    and descending order.
- Number to DisplayGlobal Configuration.

### Параметры поиска

Near the top of the page you will see the filter bar shown in the
Screenshot above.

- **Выбор состояния**. Select from Enabled / Disabled.
- **Выбор состояния активации**. Select from Activated / Unactivated.
- **Выбор группы**. Select from the list box to list only users who are
  members of that group.
- **Выбор даты последнего входа**. Select from a list to show only users
  who visited in a selected time frame.
- **Выбор даты регистрации**. Select from a list to show only users who
  registered in a selected time frame.

### Pagination

**Page Controls**. When the number of articles is more than one page,
you will see a page control bar near the bottom of the page shown in the
Screenshot above. The current page number being viewed
has a dark colour background.

- **Start**. Click to go to the first page.
- **Prev**. Click to go to the previous page.
- **Page numbers**. Click to go to the desired page.
- **Next**. Click to go to the next page.
- **End**. Click to go to the last page.

## Панель инструментов

At the top of the page you will see the toolbar shown in the
Screenshot above.

- **Создать**. Opens the editing screen to create a new user.
- **Действия**. Reveals a list of actions for selected users. Check one
  or more users checkboxes to activate the list.
  - **Активировать**. Activates multiple users. Select all the users
    required using their checkboxes then click this button. An email
    will be sent to the user notifying that their account has been
    activated
  - **Заблокировать**. Blocks one or more users. Select the users to be
    blocked using their checkboxes then click this button.
  - **Разблокировать**. Unblocks one or more users. Select the users to
    be unblocked using their checkboxes then click this button.
  - **Пакетная обработка**. Batch processes the selected users.
  - **Удалить**. Deletes the selected users.
- **Настройки**. Opens
  <a href="https://docs.joomla.org/Help4.x:Users:_Options/ru" class="new"
  title="Special:MyLanguage/Help4.x:Users: Options/ru (page does not exist)">Users:
  Options</a>.
- **Справка**. Opens this help screen.

## Пакетная обработка

The Batch Process allows a change in settings for a group of selected
users.

<img
src="https://docs.joomla.org/images/thumb/f/f1/Help-4x-Users-batch-subscreen-ru.png/600px-Help-4x-Users-batch-subscreen-ru.png"
decoding="async"
srcset="https://docs.joomla.org/images/thumb/f/f1/Help-4x-Users-batch-subscreen-ru.png/900px-Help-4x-Users-batch-subscreen-ru.png 1.5x, https://docs.joomla.org/images/thumb/f/f1/Help-4x-Users-batch-subscreen-ru.png/1200px-Help-4x-Users-batch-subscreen-ru.png 2x"
data-file-width="1598" data-file-height="814" width="600" height="306"
alt="Users batch subscreen" />

**How to Batch Process** a group of users:

1.  Select one or more users on the list by checking the desired
    checkboxes.
2.  Click the Batch Toolbar button.
3.  Set one or more of the following values:
    - To change the **User Group**, select the desired new user group
      from the Select Group list box.
    - Choose to do the desired action.
      - Добавить в группу
      - Удалить из группы
      - Переместить в группу
    - Decide if a **Password Reset** is wanted.
4.  When all of the settings are entered, click on Process to perform
    the changes. A message **"Batch process completed successfully."**
    will show.

## Быстрые советы

- Click on the name of a user to edit the user's properties.
- Click on the icon in the Enabled column to toggle between Enabled and
  Disabled status.
