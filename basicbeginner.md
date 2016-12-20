# Beginner Guide to Drupal Website Architecture

This guide is designed to help those who are just starting their journey with the UG Drupal Platform in the world of Website Archetecture. If you require more advanced information and how to use specific content types, please check out the [UG Drupal Content Types](ugcontenttypes.md) section of the training module.

The Beginner Guide to Drupal Website Architecture will cover:

* [How to Login / Logout](basicbeginner.md#how-to-login--logout)
* [Introduction to the Admin Menu Bar](basicbeginner.md#introduction-to-the-admin-menu-bar)
* [Creating Basic Content](basicbeginner.md#creating-basic-content)
* [Editing Pre-existing Content](basicbeginner.md#editing-pre-existing-content)
* [Adding Users to the Website](basicbeginner.md#adding-users-to-the-website)
* [WYSIWYG Editor](wysiwyg-editor.md)
* [Managing Menues](menuitems.md)
* [Taxonomies](taxonomies.md)
* [Multimedia and Accessibility](multimedia.md)

## How to Login / Logout
### Logging In
1. Navigate to your website: www.uoguelph.ca/*sitename*/user Once there you will be brought to the following page.
![Login example](images/userlogin.png)
2. Enter your Central Login ID in the "Username" field.
3. Enter your Central Login Password in the "Password" field.
4. Select the "Login Button".

### Logging Out
There are many ways in which a user can logout. The simpliest way is to click the `logout` option located on the menu bar.

## Introduction to the Admin Menu Bar
When Logged in as a Site Manager or Content Creator the first bar at the top of the page is called the **Administration Menu Bar** and it allows users with the correct permissions to add/view/delete/edit content as well as other administration specific tasks.

![Admin Menu Bar](images/admin_menu_bar.png)

On the Admin Bar, the important features to note are:

* **House Icon**: When selected, the user will be brought to the home page.
* **Content**: When selected, the user will be brought to a table in which all content types are listed and availiable for selection.
* **Structure**: When selected, the user will be brought to a list of content types in which they can edit the overall structure of those types.
* **People**: When selected, the user will be brought to a table in which all users registered with the site are listed.

## Creating Basic Content
In order to publish content on your website, you must select a content type in which this new content should be displayed. Once you have selected the content type in which to put your content, the rest is easy.

There are a few ways in which you can add content to your websire:

### Option 1
Select the "Add Content" shortcut located on the Administration Bar.
![Add Content Button on Administration Bar](images/Content.png)

### Option 2
Select the "Content" button on the Administration Bar and then selecting the "+ Add Content" option.

Both Option 1 and Option 2 will bring you to the "Add Content" menu.
![Add Content Menu](images/addcon.png)
From this step, simply select the content type in which you would like to add.
For more information in regards to each content type, please visit the [UG Drupal Content Types](ugcontenttypes.md) section.


## Editing Pre-existing Content
All content created on your website can be viewed by selecting the "Find Content" shortcut located on the Administration Menu shortcut bar, or by selecting "Content" on the Administration Bar itself.
![Find Content Button Highlighted](images/findcontent.png)

Once selected, you will be brought to a page with the content listed in a table.
![Website Content Listings](images/contentMenu.png)

You can search for specific content through the "SHOW ONLY ITEMS WHERE" filter options.
These options consist of searching for the content using a combination of its status and type through the drop-down menus.
![Filter and edit content options displayed](images/filterandedit.png)

## Adding Users to the Website
To simplify the process in adding users to a website, we suggest that you ask the user to attempt to login to the site. Through doing this, the user is added into the system as a user of the website. Once this is done, the permission roles ca be easiy set.

**/!\ Note**: If you already know the Central Login-ID and email address, or the user is not U of G authenticated, accounts can be set-up without having the user attempt the initial login.

### Adding a New User
1. At the top of the Administration Menu Bar select "People".
2. Select the "+ Add User"
3. Under the "Role" category, select the roles in which you would like the user to have. 
    * All Unchecked (Except Authenticated User): User is a normal user with no creation/editing capabilities.
    * For more information on the user roles, please visit the [Drupal User Roles and Responsibilities](rolesandresp.md) section.
4. For the sake of saving the information you just edited, enter a *random* password in the "Password" and "Confirm Password" field. (This step is purely for the sake of saving. This password is **NOT IMPORTANT**!!! It will not be retained since the User's Central Login ID and Password will override and provide that user access to the website).
5. Select the "Save" button.

![Add New User Image](images/newUser.png)

### Adding /  Removing Permissions on Pre-existing Site

1. At the top of the Administration Menu Bar select "People".
2. Locate the appropriate user you would like to exit. You can do this by either using the filter provided, scrolling through the list or in-browser search feature.
4. Once the user is located, select the "edit" option for that user.
5. Under the "Role" category, select or deselect the roles in which you would like the user to have. 
    * All Unchecked (Except Authenticated User): User is a normal user with no creation/editing capabilities.
    * For more information on the user roles, please visit the [Drupal User Roles and Responsibilities](rolesandresp.md) section.
5. For the sake of saving the information you just edited, enter a *random* password in the "Password" and "Confirm Password" field. (This step is purely for the sake of saving. This password is **NOT IMPORTANT**!!! It will not be retained since the User's Central Login ID and Password will override and provide that user access to the website).
6. Select the "Save" button.

![Edit Pre-existing User](images/editUser.png)

## Common Web Errors
When creating, editing or managing content with the Drupal platform there are a few common web errors that you should look out for. These web errors are not only found on our Drupal platform, so they're benificial to know and understand their causes.
These common web errors include:

* **Error 404**: This error arises when the URL you have navigated to points to something that does not exist. Common causes of this error are typos in the URL provided when clicking a link, deletion/non existance of the node in which the URL links too. To fix these problems, simply update the link with the correct one, create the page in which the link points too or add a URL Alias to a page that should have this link but doesnt.
* **Error 403**: This error arises when the user does not have permission to access the URL they have navigated to. Common causes of this error are unauthenticated users (users not logged in to the website) trying to access webpages that are either unpublished or privated. Pages that are private may also limit access to specific types of users through their authentication privlidges.
* **Error 500**: This error arises when the webpage you have navigated to has problems connecting with its back-end server. This is most commonly seen from a content creator/editor and site manager point of view. Common causes of this error are timing out (more common) or input of incorrect information during critical periods (less common). To fix this error, simply refresh the page. If the error persists ensure that the data in which you are inputting is correct, then contact your Web Manager / Site Owner.
