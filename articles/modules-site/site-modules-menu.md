<!-- Filename: Help4.x:Site_Modules:_Menu / Display title: Site Modules: Menu -->

## Description

This **Menu** module type allows you to place a Menu at the desired
position and on the desired web pages. A web site may have more than one
menu on a single page and different menus on different web pages.

## How to Access

- Select **System → Manage Panel → Site Modules** from the
  Administrator menu. Then...
  - To create a new module: select the **New** button from the Toolbar.
    Then...
    - Select the required module type.
  - To edit an existing module:
    - Find the module in the list of installed modules and select the
      title link in the **Title** column.

## Screenshot

<img
src="https://docs.joomla.org/images/3/3e/Help-4x-modules-site-module-manager-module-menu-en.png"
decoding="async" data-file-width="800" data-file-height="673"
width="800" height="673"
alt="modules site module manager module menu" />

## Form Fields

- **Title.** The title of the module. This is also the title displayed
  for the module depending on the *Show Title* Form Field

### Module Tab

#### Left Panel

- **Select Menu:** (*About Joomla*/*Australian Parks*/*Fruit Shop*/*Main
  Menu*/*Top*/*User Menu*). Select a menu in the list.
- **Base Item:** (*Current*/*Getting Started*/*Using Joomla!*/*Using
  Extensions*/*Components*/*Content Component*/...). Select a menu item
  to always be used as the base for the menu display. You must set the
  Start Level to the same level or higher than the level of the base
  item. This will cause the module to be displayed on all assigned
  pages. If Current is selected the currently active item is used as the
  base. This causes the module to only display when the parent menu item
  is active.
- **Start Level:** (*1*/*2*/*3*/*4*/*5*/*6*/*7*/...). Level to start
  rendering the menu at. Setting the start and end levels to the same \#
  and setting 'Show Sub-menu Items' to yes will only display that single
  level.
- **End Level:** (*All*/*1*/*2*/*3*/*4*/*5*/*6*/...). Level to stop
  rendering the menu at. If you choose 'All', all levels will be shown
  depending on 'Show Sub-menu Items' setting.
- **Show Sub-menu Items:** (*Show*/*Hide*). Expand the menu and make its
  sub-menu items always visible.

#### Right Panel

- **Show Title.** (Show/Hide) Choose whether to show or hide the modules
  title in the front end. The title will be the one in the Form Field
  above.
- **Position.** Choose the module position
  you wish this module to be displayed in. A custom module position can
  be entered for use with the load position plugin
  or the position button can be pressed to select a module position from
  the template.
- **Status**. The published status of the item.
- **Access**. The viewing Access  Level   for this item.
- **Module Ordering.** This shows a drop down of every module in the
  position that the current module is in. This is the order that the
  modules will display in when displayed on in the front end as well as
in the Modules page
- **Start Publishing**. Date and time to start publishing. Use this
  field if you want to enter content ahead of time and then have it
  published automatically at a future time.
- **Finish Publishing**. Date and time to finish publishing. Use this
  field if you want to have content automatically changed to Unpublished
  state at a future time (for example, when it is no longer applicable).
- **Language**. Item language.
- **Note**. This is normally for the site administrator's use (for
  example, to document information about this item) and does not show in
  the Frontend of the site.

### Menu Assignment Tab

<img
src="https://docs.joomla.org/images/0/05/Help-4x-modules-manager-site-module-menu-assignment-tab-en.png"
decoding="async" data-file-width="600" data-file-height="595"
width="600" height="595"
alt="modules manager site module menu assignment tab" />

- **Module Assignment.** Select **On All Pages**, **No Pages**, **Only
  on the pages selected** or **On all pages except those selected** from
  the List.
- **Menu Selection.** If the latter two options are selected a list will
  show all of the menu items. This allows you to assign modules to some
  but not all pages, and by selecting the menu links that you want the
  module associated with you can customize on what pages modules
  appear/don't appear. See How do you assign a module to specific
  pages?
  for more information.

### Advanced Tab

<img
src="https://docs.joomla.org/images/4/4b/Help-4x-modules-manager-admin-module-site-advanced-options-en.png"
decoding="async" data-file-width="600" data-file-height="422"
width="600" height="422"
alt="modules manager admin module site advanced options" />

- **Layout.** If you have defined one or more alternative layouts for a
  module either in the template or Joomla! Core, you can select the
  layout to use for this module.
- **Module Class.** A suffix applied to the CSS class of the Module.
  This allows you to create customized CSS styles that will apply just
  to this module. You would then modify the "user.css" file of your
  template to apply styling to this new class. Enter this parameter with
  a leading space to create a new CSS class for this module. Enter the
  parameter without a leading space to change the CSS class name for
  this module.
- **Caching.** Use Global/No Caching. Whether or not to cache the
  content of this Module. A setting of "Use Global" will use the Cache
  Settings from the Global Configuration screen.
- **Cache Time.** The number of seconds for which to cache the item
  locally. It can safely be left at the default.
- **Module Style.** You can use this option to override the templates
  style for its position.
- **Module Tag.** The HTML tag for the module to be placed in. By
  default this is a div tag but other HTML5 elements can also be used.
- **Bootstrap Size.** (Values 0 to 12) This allows you to choose the
  width of the module via the span element built into bootstrap.
- **Header Tag.** The HTML tag to use for the modules header or title.
  This can be an h1, h2, h3, h4, h5, h6 or a p tag. Note that you must
  use a module style (chrome) of html5 or add your custom module styles
  in /html/modules.php.
- **Header Class.** Here you can add optional CSS classes to add to the
  modules header or title element.

### Permissions Tab

<img
src="https://docs.joomla.org/images/d/d8/Help-4x-modules-manager-admin-module-administrator-permissions-en.png"
decoding="async" data-file-width="600" data-file-height="374"
width="600" height="374"
alt="modules manager admin module administrator permissions" />

To change the permissions, do the following.

- Select the **Group** by clicking its title located on right.
- Find the desired **Action**. Possible Actions are:
  - **Delete**. Users can delete the module.
  - **Edit**. Users can edit the module.
  - **Edit State**. User can change the published state and related
    information for the module.
- Select the desired permission for the action you wish to change.
  Possible settings are:
  - ***Inherited.*** Inherited for users in this Group from the Global
    Configuration, Article Manager Options, or Category permissions.
  - ***Allowed.*** Allowed for users in this Group. Note that, if this
    action is Denied at one of the higher levels, the Allowed permission
    here will not take effect. A Denied setting cannot be overridden.
  - ***Denied.*** Denied for users in this Group.
- Select **Save** in the **Toolbar**. When the screen refreshes, the
  Calculated Setting column will show the effective permission for this
  Group and Action.

## Toolbar

At the top of the page you will see the toolbar shown in the
Screenshot above. The functions are:

- **Save**. Saves the item and stays in the current screen.
- **Save & Close**. Saves the item and closes the current screen.
- **Save & New**. Saves the item and keeps the editing screen open and
  ready to create another item.
- **Save as Copy**. Saves your changes to a copy of the current item.
  Does not affect the current item. This toolbar icon is not shown if
  you are creating a new item.
- **Close**. Closes the current screen and returns to the previous
  screen without saving any modifications you may have made. This
  toolbar icon is not shown if you are creating a new item.
- **Help**. Opens this help screen.

## Tips

No tips have been added at this time.
