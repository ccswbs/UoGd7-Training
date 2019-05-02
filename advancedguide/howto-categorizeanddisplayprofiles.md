# Categorizing and Displaying Profiles

Some departments choose to display their staff profiles by the team they \(belong\) to, doing this with our Drupal platform will give you the following view. These instructions will guide you through the process of categorizing the profiles on your site by the teams they work in.

![An Example of a categorized profile page](../.gitbook/assets/profiles-main-image%20%281%29.png)

## Adding Profile Categories \(e.g web & development solutions\)

1. Add profile category terms using the steps in [How to Add Vocabulary Terms](../ugcontenttypes/howto-profiles.md#How-to-Add-Vocabulary-Terms)
2. Click edit beside each term you added and get the term Id from the URL \(/taxonomy/term/`#`/\) 

   ![URL to retrieve taxonomy term](../.gitbook/assets/taxonomy-term%20%282%29.png)

## Adding the Terms to a Custom Menu Block on the Right Side of the Page

1. Using the administration bar, navigate to structure &gt; menus
2. Select add menu ![blue add menu option with a plus sign](../.gitbook/assets/add-menu%20%282%29.png)
3. Enter a menu title e.g. Faculty and Staff Directory
4. Click, save
5. Select Add link ![blue add link option](../.gitbook/assets/add-link%20%282%29.png) and do the following for each taxonomy term you created in step 1\(Link to add vocabulary terms\)
   * Enter a "title" e.g. a section name \(Deans office\)
   * Enter the term Id you copied from **step 2** in the following format `people/#` into the “path” field. Where `#` is the Id number

## Adding the People page

1. Navigate back to menus ![breadcrumb pathe to menus](../.gitbook/assets/back-to-menus.png) and click on "add link" on the right of the Main menu option
2. Enter a menu link title e.g. Staff & Faculty
3. Enter "**people**" into the “path” field

## Adding the Custom Menu as A block on profiles page

1. Navigate to structure &gt; blocks
2. Select Add menu block ![Add menu block with a plus sign](../.gitbook/assets/add-menu-block%20%281%29.png)
3. Enter a title you would like as the “Block title” and “administrative title” e.g. Faculty and Staff Directory
4. Select the menu title you created under the “menu” drop down
5. Select “starting level” as 1st level \(Primary\)
6. Within the region setting select secondary in the drop down
7. Select “Only the listed pages” radio button
8. In the text area enter the following paths
   * people
   * people/\*

