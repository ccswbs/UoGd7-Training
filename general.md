# What is Drupal?
## A Brief Description
People often think of a website as a collection of static pages, perhaps with some functions like a blog or a news engine thrown in to round it out. When they go to manage their site, they are thinking in terms of a tree-like hierarchy of pages that they will edit.

Drupal, on the other hand, treats most content types as variations on the same concept: a node (more on this in a moment). Static pages, blog posts, and news items (some possible node types) are all stored in the same way, and the site's navigation structure is designed separately by editing menus, views (lists of content), and blocks (side content which often have links to different site sections).

## The Flexibility of Nodes
 Essentially, a node is a set of related bits of information. When you create a new blog post, you are not only defining its body text, but also its title, content, author link, creation date, taxonomy (tags), etc. Some of these elements will be shown by the theme layer when the node is displayed. Others are meta-data that control when the node will show up at all - such as taxonomy or publishing status.

Comments can be also be enabled on any node type you choose - be it blog posts, news items, book pages (which provide basic wiki features) or any other type you may create.

## Regions & Blocks
`show image of regions`
Pages on your Drupal site are laid out in Regions. These can include the header, footer, sidebars, and main content regions. Your theme may define additional regions.

Blocks are discrete chunks of information that are displayed in the regions of your site's pages. Blocks can take the form of static chunks of HTML or text, menus (which are for site navigation), the output from modules (e.g. hot forum topics), or dynamic listings that you've created yourself (e.g. a list of upcoming events).

## Users, Permissions and Roles
Every visitor to your site, whether they have an account and log in or visit the site anonymously, is considered a user to Drupal. Every user when created also has a role assigned to them, these roles grant the user certain permissions. When those users are logged in, Drupal will let them do the actions that role has permissions for.

### Types of Users
`some special UoG roles`
#### Anonymous User
This is anyone visiting the website which is not logged in.
- can view the front-end of the website

#### Authenticated User
These users are assigned a user ID when they register for the website. A user name and email address is associated with any user that isn't anonymous (therefore must be logged in).
- can log in to the back-end of the website
- can edit their own user profile

#### Author
- can create new content drafts
- can edit (their own) content drafts

#### Editor
Can view/edit all project data, create/edit all content types
- can edit any content (drafts or published)
- can approve any content drafts for publishing
- can publish any content

#### Moderator
- TBD

#### Publisher
- TBD

#### Site Manager
- can create new users
- can edit any user profile

#### Administrator
- can configure site settings
- full access rights
- can delete any content (drafts or published)

# Basic Beginner functions for Drupal 7.
## Users
### How to Login/Logout
1.	 Navigate to your website: www.uoguelph.ca/*sitename*
2.	 Login (…using your Central Login ID and Password)
3.	 Logout (…click link on top right)

### Adding Users
Request that new users attempt to login to the site - this provides their Username (which is their Central Login-ID for U of G staff)
1. At the top of the administration bar select *People*
2. Either use the filter or scroll down to find the Username
3. Select appropriate Username
4. Select Role (i.e. editor)
5. Enter ‘random’ password information (It will not be retained since the Central Login ID and Password will override and provide access to the website)
6.	 SAVE

*Note:* If you already know the Central Login-ID and email address, or the user is not U of G authenticated, accounts can be set-up without having the user attempt the initial login.

## About AODA and Content Editing Standards.
AODA Standards – effective January 2014 website content changes must comply with provincial legislation known as the **Accessibility for Ontarians with Disabilities Act (AODA)**. The Standards governing websites is called the **Web Content Accessibility Guidlines (WCAG) 2.0** Level A compliance was required in 2014 and Level AA compliance is required by 2021. Recommendations that will assist content editors in maintaining these standards are identified and outlined in this user manual as well as in the following list:
* Ensure all images added to your site have *descriptive* Alt tags no less than 100 characters. In the event of a purely decorative image no Alt text needs to be added.
* [U of G Web Accessibility site](https://www.uoguelph.ca/accessibility/web/)
* Siteimprove is used for tracking technical compliance - for user training Contact Diversity & Human Rights or visit the [SiteImprove website](http://siteimprove.com/) for more information
* Required fields: fields with a red asterisk (* ) must be completed.

### Adding a Link
The WCAG 2.0 standard for links is that the purpose of each link can be determined by the link text alone.

*Example* Do not use:

> * For information on courses click [here](www.google.ca)

Use this format instead:
> * [Information on courses](www.google.ca)

To do this in the Body section:
1. Highlight the text to use for the link
2. Click on the Link icon (in the Editor)
3. Insert the URL that you want to link to:
    1. External links - use a link copied from the browser (i.e. www.uoguelph.ca )…or
    2. Internal links - use the page name copied from the browser (i.e. psychology/faq-page)

For more details, refer to the quick reference [How to Meet WCAG 2.0.](http://www.w3.org/WAI/WCAG20/quickref/)


## WYSIWYG Editor
Just a few basic notes.
* Mousing over the icons will describe their functionality.
Regarding copying a pasting

## Links to other pages on how to create specific content:
* [How to create a Basic Page](features/howto-page.md)
* [How to create a Featured Item](features/howto-featured.md)
* [How to create a Banner](features/howto-banner.md)
* [How to create a News Item](features/howto-news.md)
* [How to create an Events listing](features/howto-events.md)
* [Social Media](features/howto-socialmedia.md)
* [How to create a Service page](features/howto-services.md)
* [How to create a FAQ](features/howto-FAQ.md)
* [How to create a Book](features/howto-book.md)
* [How to create People Profiles](features/howto-profiles.md)
* [How to create a Blog](features/howto-blog.md)
* [How to create a Web Form](features/howto-webforms.md)
* [Creating a Landing Page](features/howto-landingpag.md)
* [How to create a Special Alert](features/howto-specialalert.md)
* [How to create Course Outlines](features/howto-courseoutlines.md)
* [How to create Custom Content](features/howto-customcon.md)
