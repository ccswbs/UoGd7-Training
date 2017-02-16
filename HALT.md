#H.A.L.T.

This module is designed as an overview of techniques that content creators can use to make websites more accessible.
Small changes based on these guidelines will make a big difference for assistive technology users. 


##What is H.A.L.T?

***H***eadings

***A***lternative Text

***L***ists

***T***ables

H.A.L.T addresses some common accessibility issues for static content commonly found on basic pages on the Drupal content management
system (CMS). 

##Headings

For users who cannot visually perceive the layout of information on a web page, assistive technology helps them navigate quickly by reading a list of headings found on the page. However, assistive technology can only tell that a piece of text is a content heading if the code indicates that it is.

In HTML, headings are denoted with `<h>` tags. These tags have six levels:

![Heading Tag Levels H1-H6](/images/heading-tags.jpg) ![Heading Tags with Subheadings Shown](/images/heading-subheads.gif)

When using Drupal, you can set headings with the rich text editor, also known as the WYSIWYG editor. Highlight some text, and then select a heading level from the dropdown menu:
![WYSIWYG Editor with Headings Drop-Down Menu](/images/Headings drop down WYSIWYG 2.png)

For each piece of text, the bottom bar of the text editor lists the HTML elements it is marked up with, including any heading tags.

**/!\ Note**: Do not use heading elements simply to increase font size, and do not use *empty* heading elements to create space on the page. These improper uses of headings will make the web page less accessible. 

##Alternative Text

Alternative text, or "alt text" for short, is a brief description of a image on a webpage. Alt text is not visible on the page, but it is essential for creating accessible content. Users who cannot see images on the screen depend on alt text, which can be read aloud by assistive technology. There are a few important things to know about alt text:
* Alt text should be kept short and descriptive.
* Alt text is necessary for images that provide information to the user. 
* Alt text should not be attached to images that are purely decorative.
* Alt text for a linked image must describe the link destination, not the image itself. 

###Adding Alt Text in the Drupal Text Editor

From the Drupal text editor, click on the image icon in the menu bar. This action will open a window like this: 

![WYSIWYG image properties window](/images/alt-text-wysiwyg.png)

Add short, descriptive alternative text in the "Alternative Text" field.

##Lists

Lists are an important feature for organizing information on a web page. For a web page to be accessible, any content that is visually presented as a list must also be marked up as a list in the source code. 

In the Drupal text editor, content creators have the choice between ordered (numbered) and unordered (bullet) lists. When creating a list, either select a list button and begin typing the list items, or highlight existing text and then select the list button to turn it into a list. Press the `Enter` or `Return` key to go to the next list item, and press `Tab` to start a sub-list or nested list.

![Drupal text editor example list](/images/Lists example 2.png)

##Tables

Tables are useful for organizing information into a grid of cells. To make sure a table is accessible, it is important to keep it fairly simple. If your table is complex, with split or merged cells, consider splitting into multiple tables if possible. In order to assess complexity, imagine hearing the information over the phone. Can the information be understood without a visual aid? 

###Using Tables in Drupal

1. Start by selecting the table button in the Drupal text editor.
![Highlight of the table button in the Drupal text editor](/images/tables 1.png)
2. The following dialog box will appear. Enter the appropriate number of rows and columns.
![Table properties dialog box](/images/tables 2.png)
3. 

###Table Headers and Captions
