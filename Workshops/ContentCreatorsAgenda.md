# Content Creation Workshop
In this workshop you will be instructed on the following items:

1. Briefly touch on Accessibility, the AODA, and WCAG 2.0 Standards.
2. Some Tips and Tricks with our WYSIWYG editor.
3. How to build a *Basic Page*, a *News Item*, an *Event*, and a *Banner*.

## Accessibility, The AODA, and WCAG 2.0
Accessible design is good for all. Large public-sector organizations usually have large, multi-page, multi-department—and often cumbersome—websites. Accessible design and the principles of universal design, with their emphasis on clear, streamlined and flexible presentation, content and navigation, can lessen the frustrations of users who use your website. An accessible website is beneficial to all users and certainly to the organizations that create them because it means their website is better able to reach all members of its target audience.

**The Accessibility for Ontarians with Disabilities Act, 2005 (AODA)** became law on June 13, 2005. Under this landmark legislation, the government of Ontario has developed mandatory accessibility standards that identifies, removes, and prevents barriers for people with disabilities. Disability impacts the lives of many Ontarians, and the numbers of people with disabilities is increasing. Today, 15.5% of Ontario’s population has a disability and this number will continue to grow as the population ages.

The AODA requires that beginning January 1, 2014, new public websites, significantly refreshed websites and any web content posted after January 1, 2012 must meet **Web Content Accessibility Guidelines (WCAG) 2.0 Level A**. And beginning January 1, 2021, all public websites and web content posted after January 1, 2012 must meet **WCAG 2.0 Level AA**. WCAG 2.0 is an internationally accepted standard for web accessibility developed by the **World Wide Web Consortium (W3C)**, an international team of experts. Following these guidelines should make it easier for everyone to access your website and content.

WCAG 2.0 has 12 guidelines that are organized under 4 principles: Perceivable, Operable, Understandable, and Robust. For each guideline, there are testable success criteria, which are ranked at 3 levels: A, AA, AAA.

## How To Use The WYSIWYG Editor and Additional Tips.
There are a few items that need to be explained with our current version of our WYSIWYG editor until the updates come down the line. The items are as such:

1. How to add images within the body section.
2. How to add tables.
3. How to create links that are **WCAG 2.0 AA** compliant.

### Adding Images To The Content Body.
1. Goto the **Body** section of the page.
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

For more details, refer to the quick reference [How to Meet WCAG 2.0.](http://www.w3.org/WAI/WCAG20/quickref/)

## Building Specific Content Types
The following content types will be built and demostrated:

1. A Basic Page.
2. A News Article.
3. An Event Page.
4. How to create and add a Banner.

### Creating A Basic Page
The *Basic Page* content type is used for static content that can (but are not required to) be linked into the main navigation bar. This is one of the most "basic" content types and can be very flexible.

1. On the Administration bar, select `Add Content`.
2. Select `Page`.
3. Enter a **Title**.
4. If you have [page categories](../taxonomies.md#categories) defined select the appropriate one.
5. In the **body field** enter what you want displayed on your web page.
6. If you want to add any files to download attach them using the **File Attachment** option.
7. If you want this web page to be accessed through your menus check the `provide a menu link`.
    1. Enter an appropriate **Title** and **Description**.
    2. In the `Parent item` drop down menu select which menu heading you want the new link to be accessed through. *Example: If it is an event select event to have it as a sublink there.*
8. If you have the proper authority to publish right away, select `Published` in `Publishing options`.
9. Select `Save` when you are done.

### Creating A News Article
The *News* feature allows content authors to add news articles to the website and display them in a Listing Page view, an Article Detail Page view, and a Recent News Teaser List view. Any article can be featured on any page using the Featured News Article view. Site visitors can also browse for news articles by date and category tag.

1. On the Administration bar, select `Add Content`.
2. Select `News`.
3. Enter a **Title**
4. If you have [page categories](taxonomies.md#categories) defined select the appropriate one.
5. Enter a **Written by**.
6. In the body field enter what you want displayed on your web page. Follow this link [for more information on how to use the WYSIWYG editor.](wysiwyg-editor.md)
7. Add a feature image if there is one for the news, such as a image of the subject matter. It is required to add **Alternative Text** if the image is not a decorative one. Add a **Caption**.
8. Enter any *tags or keywords* that help categorize and organize your article.
9. If you want this web page to be accessed through your menus check the `provide a menu link`.
    1. Enter an appropriate **Title** and **Description**.
    2. In the `Parent item` drop down menu select which menu heading you want the new link to be accessed through.
10. If you have the proper authority to publish right away, select `Published` in `Publishing options`.
11. Ensure `Promoted to front page` is selected.
11. Select Save when you are done.

### Creating A Event
The Events feature allows **Authors** to add events to the website and display them in a Listing Page view, a Weekly Events view, a Monthly Calendar view, an Event Detail Page view, and an Upcoming Events Teaser List view. Any event can be highlighted (or “featured”) on any page using the Featured Items block. Site visitors can also browse for events by date and event category.

1. Select `Add Content` at the top of the administration bar.
2. Select `Event` in the list.
3. Enter a **Title**. *(Mandatory)*
4. Enter the starting and ending **Dates and Time**. *(Mandatory)*
5. Enter a **Location**.
`Add some points here about location field`
6. In the **Body field** enter the details and summary of the information.
7. [Select your Section](../taxonomies.md#Sections)
8. Add a `feature image` if there is one for the event, such as a poster image.  Add a descriptive **Alt Text** - a **Caption** is optional. *Note: Any information available on the image should also be available in your summary.*
9. Add any files relevant to the Event and enter a related website for your event *(if there is a page dedicated to the event)* with a descriptive title.
10. Select the Save button when you are done.

### Creating and Adding A Banner
There can be multiple static banners that change every time the page is refreshed or they can be displayed as a slide show. For proper display each banner image *must* be **1140 x 292**.

To Add a Banner Image:

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

To Display The Banner On The Front Page:

1. Select `Structure` at the top of the administration bar.
2. Select `Blocks`.
3. Two options:
    * If you want a **static banner** drag *View: B1 - Image slider (Banner): Block - Manual* up to the *Highlighted* block region or select highlighted from the dropdown menu.
    * If you want a **slide show banner** drag *View: B1 - Image slider (Banner): Block - Autoplay* up to the *Highlighted* block region or select highlighted from the dropdown menu.
    *It is recommended not to use the slideshow banner as it isn't considered AODA compliant**
4. Select `Save Blocks`.
