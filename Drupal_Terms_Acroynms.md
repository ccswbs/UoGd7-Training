## Nodes
A node is the generic term for a piece of content on your web site. The content type of the node will define what fields are included with it. Depending on the type of node, different fields will be attached, and this is known as a content type. For example, a basic Page content type has attached fields such as title and body fields. Other examples of content type are: Book pages for use in Books, Discussion topics in forums, Blog pages in blogs, and News articles.

## Content Type
Every node belongs to a single “node type” or “content type”, which defines various default settings for nodes of that type, such as whether the node is published automatically and whether comments are permitted. Common "Content Types" that just about any website would have include: blog post and page. Content types can have different fields and modules can define their own content types. The core Drupal Book and Poll modules are two examples of modules that define content types.

### Site architecture - Content Types UoG template provides:
* [Basic Page](/howto-page.html)
* [Featured Items](/howto-featured.html)
* [Banner](/howto-banner.html)
* [News](/howto-news.html)
* [Events](/howto-events.html)
* [Social Media](/howto-socialmedia.html)
* [Services](/howto-services.html)
* [FAQ](/howto-FAQ.html)
* [Book](/howto-book.html)
* [People Profiles](/howto-profiles.html)
* [Blog](/howto-blog.html)
* [Web Forms](/howto-webforms.html)
* [Landing Page](/howto-landingpag.html)
* [Special Alert](/howto-specialalert.html)
* [Course Outlines](/howto-courseoutlines.html)
* [Custom Content](/howto-customcon.html)


## Taxonomy
Drupal has a system for classifying content known as taxonomy. This is provided by the core Taxonomy module. You can define your own vocabularies (groups of taxonomy terms) and add terms to each vocabulary. Each vocabulary can then be attached to one or more content types, and in this way, nodes on your site can be grouped into categories, tagged, or classified in any way you choose.

## Menus
`add a generic image showing where each menu goes`

There are four standard menus in Drupal 7:

1. **The Main Menu** is built by site administrators and displayed automatically in the page header of many themes (and if not, you can enable their blocks to display them).
2. **Management** is the administration menu, and is presented in the Admin toolbar.
3. **Navigation** is a catch-all menu that usually contains links supplied by modules on your site.
4. **User Menu** contains links to the User account and the logout link.
