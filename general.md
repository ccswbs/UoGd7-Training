# Guide to UoG Drupal Web Content Management System and Template
## Conventions Used In This Documentation

* *Emphasis* or *Italic*
    * Used for pathnames, filenames, program names.
* **Strong** or __Bold__
    * Used for options, titles, new terms where they are defined
* `Constant Width`
    * For things the user will see and read on the screen.

# What is Drupal?
## A Brief Description
Websites are often thought as a collection of static pages, perhaps with some functions like a blog or a comments section. When they go to manage their site, they are thinking in terms of a tree-like hierarchy of pages that they will edit.

**The University of Guelph Business Web Solutions** department uses a *Content Management System (CMS)* called *Drupal*. *Drupal* on the other hand treats most content types as variations on the same concept: a *Node* (more on this in a moment). Static pages, blog posts, and news items (some possible node types) are all stored in the same way, and the site's navigation structure is designed separately by editing menus, views (lists of content), and blocks.

## The Flexibility Of Nodes
 Essentially, a **node** is a set of related bits of information. When you create a new blog post, you are not only defining its body text, but also its title, content, author link, creation date, taxonomy (tags), etc. Some of these elements will be shown by the theme layer when the node is displayed. Others are meta-data that control when the node will show up at all - such as taxonomy or publishing status.

## Regions and Blocks
![Image of Block Areas highlighted](images/Block_Areas.jpg)

**Nodes** on your *Drupal* site are laid out in **Regions**. These can include the header, footer, sidebars, and main content regions. Your theme may define additional regions.

**Blocks** are discrete chunks of information that are displayed in the regions of your site's pages. Blocks can take the form of static chunks of HTML or text, menus (which are for site navigation), the output from modules (e.g. hot forum topics), or dynamic listings that you've created yourself (e.g. a list of upcoming events).
