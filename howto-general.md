# What is Drupal?

## A Brief Description
People often think of a website as a collection of static pages, perhaps with some functions like a blog or a news engine thrown in to round it out. When they go to manage their site, they are thinking in terms of a tree-like hierarchy of pages that they will edit.

Drupal, on the other hand, treats most content types as variations on the same concept: a node (more on this in a moment). Static pages, blog posts, and news items (some possible node types) are all stored in the same way, and the site's navigation structure is designed separately by editing menus, views (lists of content), and blocks (side content which often have links to different site sections).

## The Flexibility of Nodes
 Essentially, a node is a set of related bits of information. When you create a new blog post, you are not only defining its body text, but also its title, content, author link, creation date, taxonomy (tags), etc. Some of these elements will be shown by the theme layer when the node is displayed. Others are meta-data that control when the node will show up at all - such as taxonomy or publishing status.

Comments can be also be enabled on any node type you choose - be it blog posts, news items, book pages (which provide basic wiki features) or any other type you may create.

## Regions & Blocks

Pages on your Drupal site are laid out in Regions. These can include the header, footer, sidebars, and main content regions. Your theme may define additional regions.

Blocks are discrete chunks of information that are displayed in the regions of your site's pages. Blocks can take the form of static chunks of HTML or text, menus (which are for site navigation), the output from modules (e.g. hot forum topics), or dynamic listings that you've created yourself (e.g. a list of upcoming events).

## Users/Permissions/roles
Every visitor to your site, whether they have an account and log in or visit the site anonymously, is considered a user to Drupal. Every user also has a numeric user ID special to the type of user.

### Types of Users
#### Master Administrator
This user has the ID one (1). User of ID one (1) is the user account when you create and install Drupal. This user is very special because it has permission to do absolutely everything on the site.

#### Logged In
These users are assigned a user ID when they register for the website. A user name and email address is associated with any user that isn't anonymous (therefore must be logged in).

#### Anonymous
This is anyone visiting the website which is not logged in.

### Permissions & Roles
'rewrite for UG base options'
Users on your site can be assigned permissions via roles. To do this, you first need to create a role by navigating to people --> permissions --> role. A common role is "Content editor" or "Member". Next, you will assign permissions to that role, to tell Drupal what that role can and can't do on the site. Finally, you will grant certain users on your site your new role, which will mean that when those users are logged in, Drupal will let them do the actions you gave that role permission to do.
