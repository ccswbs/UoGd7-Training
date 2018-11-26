# Customizing Site Search Box

The following are two different options for placement of a Search Box Form on you website. 

## Option 1: Placing Search Box Using Blocks

The Search box is placed on the right-hand side of the page using blocks. 
![Image of search box on right side example](/images/search-form-option-1.png)

### How to Implement Option 1

1. Select `Structure` from the Administration Menu Bar, then select `Blocks`
2. Scroll down the page until you reach the "Disabled" section and locate `Search form`
3. On the right-hand side, there is a drop-down menu that currently reads - None -. Choose `Secondary` from this drop-down menu
4. Scroll upwards until you find the "Secondary" section. The Search form item should be listed there
   * On the right-hand side, select `Configure` inline with the Search form
   * It will bring up a menu that looks like this:

![Image of a Drupal Menu](/images/search-form-editor.png)
  
   * Select `All pages except those listed`
   * In the blank textbox, type `<front>`
   * Select `Save Block`
  
Now the Search Box should appear on every page of the site except for the homepage. To enable the Search box on the homepage, see instructions below. 

## Option 2: Link to Search Added to Main Menu Bar

A link is added to the Main Menu Bar that takes the user to the Search page. 

![image of Main Menu Bar](/images/search-form-option-2.png)
![Image of search form page](/images/search-form-option-2a.png)

### How to Implement Option 2
1. Select `Structure` from the Administration Menu Bar, then select `Menus`
2. Click `list links` located to the far right of the "Main Menu" item
3. At the top of the page, select `Add link`
4. Input the following into the fields
   * Menu Link Title: Search
   * Path: search
   * Choose `save` at the bottom of the page
5. You will now find the "Search" lin at the bottom of the Menu Link List 

![Image of Drupal Main Menu links](/images/search-form-menu-links.png)

6. Click and drag the anchor on the left of Search to position the Search menu link in the list
7. Click `Save configuration` at the bottom of the page

You will now have a link in your Main Meny Bar that leads to the Search page.

## How to Add a Search Box to your Homepage

1. Navigate to the homepage. Select `Customize this page`
2. You will see your homepage broken down into sections. Under the Right Side section, select the + 
3. A menu will appear. Select `Widgets' and then `Search form`
4. Select `Finish`
5. Select `Save` at the bottom of the page 

You have successfully added a Search Box to your homepage. 

