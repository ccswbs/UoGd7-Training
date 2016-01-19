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

## Building Specific Content Types
The following content types will be built and demonstrated:

1. How to Perform administration tasks.
2. How to Login/logout.
2. How to find and filter content.
3. A Basic Page.
4. How to create a FAQ.

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
4. If you have [page categories](../taxonomies.md#categories) defined, select the appropriate one.
5. In the **body field** enter what you want displayed on your web page. *Please see below on how to use the content editor*
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
