# Content Creation Workshop
In this workshop you will be instructed on the following items:

1. Briefly touch on Accessibility, the AODA, and WCAG 2.0 Standards.
2. How to login/logout and find/filter content.
3. Build a *Basic Page*, and a *FAQ*.
4. Some Tips and Tricks with our WYSIWYG editor.

## Accessibility, The AODA, and WCAG 2.0
Accessible design is good for all. Accessible design and the principles of universal design, can lessen the frustrations of users who use your website. An accessible website is beneficial to all users and certainly to the organizations that create them because it means their website is better able to reach all members of its target audience.

**The Accessibility for Ontarians with Disabilities Act, 2005 (AODA)** became law on June 13, 2005. Under this landmark legislation, the government of Ontario has developed mandatory accessibility standards that identifies, removes, and prevents barriers for people with disabilities. Today, 15.5% of Ontario’s population has a disability and this number will continue to grow as the population ages.

Beginning January 1, 2021, all public websites and web content posted after January 1, 2012 must meet **WCAG 2.0 Level AA**. **WCAG 2.0** is an internationally accepted standard for web accessibility developed by the **World Wide Web Consortium (W3C)**, an international team of experts. Following these guidelines should make it easier for everyone to access your website and content.

### Quick notes on accessibility when creating content
* Don't use low contrast text colours.
* Don't use flashing images or videos.
* If using videos ensure you also have a transcript or captions available.
* Use headings to structure your info logically, not for aesthetics.
* Create links that can be understood out of context (more info in another section).

## Building Specific Content Types
The following content types will be built and demonstrated:

1. How to Perform administration tasks.
2. How to Login/logout.
2. How to find and filter content.
3. Creating a Basic Page and going through the steps of our current WYSIWYG editor.
4. Adding Event content.
5. Adding News Articles.
6. Banners.

### How to Perform Administration and Content Tasks
To add any type of pre-defined content, the methods are the same. When Logged in as a Site Manager or Content Creator the first bar at the top of the page is called the **Administration Menu Bar** and it allows users with the correct permissions to add/view/delete/edit content as well as other administration specific tasks.

### How to Login/Logout
1. Navigate to your website: www.uoguelph.ca/*sitename*/user
2. To `login` use your Central Login ID and Password in the user login fields.
3. To `logout` select or click the `logout` option located on the menu bar.

### Finding, Filtering, and Editing Content
All content created on your website can be viewed by selecting the `Find Content` shortcut located on the Administration Menu shortcut bar, or by selecting `Content` on the Administration Menu bar itself.

To Edit content you can search using the filter drop-down menus for a particular content type and then select `edit` for that particular item.

### Creating A Basic Page
The *Basic Page* content type is used for static content that can (but are not required to) be linked into the main navigation bar. This is one of the most "basic" content types and can be very flexible.

1. On the Administration bar, select `Add Content`.
2. Select `Page`.
3. Enter a **Title**.
4. If you have [Page Categories](../taxonomies.md#categories) defined, select the appropriate one.
5. In the **body field** enter what you want displayed on your web page.

*Please see below on how to use the content editor*
6. If you want to add any files to download attach them using the **File Attachment** option.
7. If you want this web page to be accessed through your menus check the `provide a menu link`.
    1. Enter an appropriate **Title** and **Description**.
    2. In the `Parent item` drop down menu select which menu heading you want the new link to be accessed through. *Example: If it is an event select event to have it as a sublink there.*
8. If you have the proper authority to publish right away, select `Published` in `Publishing options`.
9. Select `Save` when you are done.

## How To Use The WYSIWYG Editor and Additional Tips.
There are a few items that need to be explained with our current version of our WYSIWYG editor until the updates come down the line. The items are as such:

1. How to add images within the body section.
2. How to add tables.
3. How to create links that are **WCAG 2.0 AA** compliant.

### Adding Images To The Content Body.
1. Go to the **Body** section of the page.
2. From the WYSIWYG Editor click on the image icon.
3. And then click `Browse Server`.
4. If image isn't already uploaded to your filesystem select upload from the menu bar.
5. Select your desired image and then click ![Insert file]().
6. Unless the image is decorative it is **mandatory** to add Alternative Text.
  * Provide alternative text for images. These must reflect the purpose of the image:
    * Decorative: no alternative text.
    * Having a function: Describe the functionality.
    * Linking: Describe destination.
7. `Width`, `Height` and `Border` settings should be blank.
8. Select the `Advanced` tab setting and modify the following properties:
    * Stylesheet Class to *img-responsive*. **Required**
9. Select OK and your image should be inserted.

### Adding Tables
The **WCAG 2.0** standard for table settings dictates that table markup must be properly structured to differentiate and properly link between header and data cells.

1. Click on Table Icon[image] in the WYSIWYG editor.
2. Enter the number of columns and rows.
3. It is **mandatory** to set the following *Table Properties* to blank values:
    * `Border Size` *blank*
    * `Width` *blank*
    * `Height` *blank*
    * `Cell Spacing` *blank*
    * `Cell Padding` *blank*
4. Add a `Caption` if a title is not provided elsewhere.
5. Adding a `Summary` is optional but recommended if the table is complicated and information not provided elsewhere.
6. Ensure `Alignment` is set to *< not set >*.
7. Select the `Advanced` tab and modify the following Properties:
    * Stylesheet Class: *table table-responsive* **required** as well.
8. Hit `OK` and begin entering your data.

*Note: To modify an existing table right-click on a cell in the table and additional options will be displayed.*

### Adding a Link
The **WCAG 2.0** standard for links dictates that the purpose of each link can be determined by the link text alone.

*Example* Do not use:
>To search the internet click [here](www.google.ca).

Use this format instead:
>[Visit Google's webpage](www.google.ca).

To do this in the **body** section:

1. Highlight the text to use for the link.
`show image of highlighted text`
2. Click on the Link icon (in the Editor).
`insert image of link icon`
3. Insert the URL that you want to link to:
    1. External links - use a link copied from the browser *i.e. www.uoguelph.ca*.
    2. Internal links - use the page name copied from the browser *psychology/faq-page*.

For more details, refer to [Web Solutions full documentation.](https://mancusop.gitbooks.io/uog-drupal-training/content/)

## To Create an Event
1. Select `Add Content` at the top of the administration bar.
2. Select `Event` in the list.
3. Enter a **Title**. *(Mandatory)*
4. Enter the starting and ending **Dates and Time**. *(Mandatory)*
5. Enter a **Location**.
6. In the **Body field** enter the details and summary of the information.
  * Ensure your section item has been predefined, a common one is *Cost*.
7. [Select your Section](../taxonomies.md#Sections) if you have defined one.
  * For sections a **Taxonomy** for `Event_headings` needs to be created. The `Sections` datafield is where content creators can add data that doesn't conform to the already predetermined Events feature such as *Cost*, or *Extra Directions*, or  *Dinner Menu Items*. A Section does not need to be added and can be left blank.
8. Add a `feature image` if there is one for the event, such as a poster image.  Add a descriptive **Alt Text** - a **Caption** is optional. *Note: Any information available on the image should also be available in your summary.*
9. Add any files relevant to the Event and enter a related website for your event *(if there is a page dedicated to the event)* with a descriptive title.
10. Select the Save button when you are done.

## To Add a News Article
1. On the Administration bar, select `Add Content`.
2. Select `News`.
3. Enter a **Title**
5. Enter a **Written by**.
6. In the body field, enter what you want displayed on your web page. [Here is more information on how to use the WYSIWYG editor.](wysiwyg-editor.md)
7. Add a feature image if there is one for the news, such as an image of the subject matter. It is required to add **Alternative Text** if the image is not a decorative one. Add a **Caption**.
8. Enter any *tags or keywords* that help categorize and organize your article.
9. If you want this web page to be accessed through your menus check the `provide a menu link`.
    1. Enter an appropriate **Title** and **Description**.
    2. In the `Parent item` drop down menu select which menu heading you want the new link to be accessed through. *Example: If it is an event select event to have it as a sub-link there.*
10. If you have the proper authority to publish right away, select `Published` in `Publishing options`.
11. Ensure `Promoted to front page` is selected.
11. Select Save when you are done.

## To Add a Banner Image
1. Select `Add Content` at the top of the administration bar.
2. Select `Banner`.
3. Enter the required information: *Title, Category, Headline, Headline Link*.
    * **Headline:** Appears on the image.
    * **Headline Link:** can link to any website, if internal link use the page name.
4. Image - `Upload Image:` Choose File – *Upload*.
    * You must enter Alt text describing the image.
5. Enter optional information: *Summary, Keywords*.
    * **Summary:** Appears below the headline.
    * **Keywords:** like tags, are a filtering mechanism.
6. Select the Order (random order by default, 0 = first, 1 = second).
7. Select `Save` when done.

*Note: To add more banner images do the same steps as listed and change the order if you have a preferred order.*

### To Display The Banner On The Front Page
1. Select `Structure` at the top of the administration bar.
2. Select `Blocks`.
3. Two options:
    * If you want a **static banner** drag *View: B1 - Image slider (Banner): Block - Manual* up to the *Top Bar* block region or select highlighted from the dropdown menu.
    * If you want a **slide show banner** drag *View: B1 - Image slider (Banner): Block - Autoplay* up to the *Top Bar* block region or select highlighted from the dropdown menu.
4. Select `Save Blocks`.