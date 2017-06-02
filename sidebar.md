# Sidebar Menus

Sidebar menus show up on the right side of the page, beside the main body content. They can be easily customized to display a portion of the main menu on all pages, or a few select ones.

For help with creating menus, see the [Managing Menus](menuitems.md) page.

There are two main methods for creating sidebar menus.

## 1. Panels Method

1. On the page you would like to add a sidebar menu to, select `Customize this page` at the bottom of your screen. Keep in mind that changes made here will affect all nodes in the content type. For example, if you are adding a sidebar menu to a basic page, the menu will show up on all basic pages.
2. Scroll down to the Right side region, and select the plus sign.
3. In the add content menu, select `Menus` from the side menu. Then select `menu tree of the menu selected by the page`.
4. In the configuration dialog, the "Starting level" drop-down controls how much of the main menu appears on the page. Starting from the secondary level is recommended, because it means that the portion of the main menu most relevant to the page will show up in the sidebar. Starting from the primary level means that the whole main menu will show up in the sidebar.
5. Select `Finish`. Try selecting `Finish` again if an error message appears.
6. When the configuration dialog closes, make sure to select `Save` at the bottom of the page.

## 2. Blocks Method

### Creating and Configuring a Menu Block

1. From the administration bar, navigate to `Structure` > `Blocks`.
2. At the top of the page, select `Add menu block`.
3. Enter a title for the menu block if it should be different from the default title, determined by the menu. Enter `<none>` to display no title.
4. From the Menu dropdown, select either "Main menu" to display the whole menu in the sidebar, or `<the menu selected by the page>` to only display the portion of the main menu relevant to the page.
5. Select the starting level for the menu. 
6. Under Visibility settings, specify the pages that the menu block should be displayed on, if desired. Specify pages using the internal path rather than the full URL.
7. Select `Save block`.

### Placing a Menu Block

1. From the administration bar, navigate to `Structure` > `Blocks`.
2. Find the menu block you just created in the list of blocks, under "Disabled."
3. Drag your block from "Disabled" to "Secondary."
4. Scroll to the bottom of the page and select `Save blocks`.
