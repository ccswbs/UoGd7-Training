# Basic Beginner Functions For Drupal 7
## How-to Perform Administration and Content Tasks
To add any type of pre-defined content, the methods are the same. When Logged in as a Site Manager or Content Creator the first bar at the top of the page is called the **Administration Menu Bar** and it allows users with the correct permissions to add/view/delete/edit content as well as other administration specific tasks.

## Users
### How-to Login/Logout
1. Navigate to your website: www.uoguelph.ca/*sitename*
![Login example](images/userlogin.png)
2. To `login` use your Central Login ID and Password in the user login fields.
3. To `logout` select or click the `logout` option located on the menu bar.

### Adding Users
Request that new users attempt to login to the site - this provides their Username (which is their Central Login-ID for U of G staff).

1. At the top of the **Administration Menu Bar** select `People`.
2. Either use the filter or scroll down to find the Username.
3. Select appropriate Username.
4. Select `Role` (i.e. editor).
5. Enter a *random* password information (It will not be retained since the Central Login ID and Password will override and provide access to the website).
6. Select `Save`.

*Note: If you already know the Central Login-ID and email address, or the user is not U of G authenticated, accounts can be set-up without having the user attempt the initial login.*

## Creating and Editing Menus
`add more information about menu items`
### Adding a New Menu Item
1. Navigate to the Menus page `Structure > Menus` or http://example.com/admin/structure/menu.
2. Locate a menu to edit and click `add link`.
3. In the **Menu link title field**, enter the title as it will be displayed in the menu.
4. In the Path field, enter a path for the link. This can be an internal Drupal path such as about/example or an external URL such as http://example.com. Enter <front> to link to the front page.
5. In the **Description field**, enter the text that will be displayed when a user hovers over the link.
6. Enable any of the following options:
  * **Enabled**: If the link is not enabled, it will not be displayed in the menu.
  * **Expanded**: If this option is enabled and the menu link has children, the first level children of the menu link will always be expanded. (NOTE: This rule doesn't cascade down for subsequent levels of children links. You must enable this option at each level where you want the next level to be expanded.)
7. In the Parent link list, select the parent of the link. *(Optional) In the Weight list, select the relative weight of the link. Links with the "lightest" weight will display higher in a menu. Links with the same weight will display in alphabetical order.*
8. Click Save.

### Using Categories in Menus
The menus on your site can call for items that match specific taxonomy terms. To create a menu using Taxonomy, follow these steps:

1. Find the autopath given to your taxonomy term (*Note: To find the autopath, go to the Taxonomy > list terms page for the category to which your term belongs, and click the term. You'll be sent to a page with the autopath of your taxonomy term - save it*).
2. Go to the menus page `(Structure > Menus)`.
3. Select `Add link` to the Main Menu.
4. When you fill in the Path field you add your term as follows: category/term/ *i.e. event-heading/socials*
