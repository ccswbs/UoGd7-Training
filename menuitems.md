# Creating and Editing Menus
## Adding a Menu Item Automatically When Creating New Content
* At the end of the page there are a few options you can select to customize your content. To add a menu item when your content is created follow these steps:
1. Check the checkbox labeled `Provide a menu link`.
2. In the **Menu Link Title** enter a menu title, this will be the text that users can click on to get to this page.
3. Enter a **Description**	If a user's mouse hovers over this link, after a moment the description you type here will show.
4. Choose the **Parent Item** for this page. For example, if we later created a *Event listing* page, we may want to file it under *Events of the month*, and we could do that here.
5. You can adjust the **Weight** to change in which order this link will appear.
6. Select `Save`.

## Adding a New Custom Menu Item Manually
1. Navigate to the Menus page `Structure > Menus` or http://example.com/admin/structure/menu.
2. Locate a menu to edit and click `add link`.
3. In the **Menu link title field**, enter the title as it will be displayed in the menu.
4. In the Path field, enter a path for the link. This can be an internal Drupal path such as about/example or an external URL such as http://example.com. Enter <front> to link to the front page.
5. In the **Description field**, enter the text that will be displayed when a user hovers over the link.
6. Enable any of the following options:
  * **Enabled**: If the link is not enabled, it will not be displayed in the menu.
  * **Expanded**: If this option is enabled and the menu link has children, the first level children of the menu link will always be expanded. (NOTE: This rule doesn't cascade down for subsequent levels of children links. You must enable this option at each level where you want the next level to be expanded.)
7. In the Parent link list, select the parent of the link.
8. (Optional) In the Weight list, select the relative weight of the link. Links with the "lightest" weight will display higher in a menu. Links with the same weight will display in alphabetical order.*
9. Click Save.

## Using Categories in Menus
The menus on your site can call for items that match specific taxonomy terms. To create a menu using Taxonomy, follow these steps:

1. Find the autopath given to your taxonomy term (*Note: To find the autopath, go to the Taxonomy > list terms page for the category to which your term belongs, and click the term. You'll be sent to a page with the autopath of your taxonomy term - save it*).
2. Go to the menus page `(Structure > Menus)`.
3. Select `Add link` to the Main Menu.
4. When you fill in the Path field you add your term as follows: category/term/ *i.e. event-heading/socials*
