# Accessibility Awareness: Tips and Strategies for Creating AODA Compliant Websites

In this workshop, you will be instructed on the following items:

1.  Introduction - Overview of Agenda
2.  Planning & Working with Taxonomies
3.  Menus
4.  Document Accessibility
5.  Multimedia Accessibility
6.  SiteImprove Overview
7.  Scoping & Prioritization
8.  Accessibility Best Practices
9.  CourseLink – Basic WCAG 2.0 Training
10. Discussions & Questions - Future Workshops

## Taxonomy

*Taxonomy* is the practice of classifying content. In *Drupal*, the
taxonomy module allows you to classify your website content, and it can
be an important part of your information architecture. This module is
beneficial for everything from menu and navigation organization, to view
& display options.

### Planning Taxonomies

The first step in establishing taxonomy is creating a new vocabulary.
Next you provide the terms that fall within that vocabulary.

An example of how you might create taxonomy for a site using our
predefined vocabularies:

**Vocabulary = Page Category**

**Term = Workshops**

Our platform uses a *controlled vocabulary*, where only Site Managers
can assign terms to vocabularies. Site Managers must add the terms in
advance.

### Taxonomy Principles

-   Each vocabulary consists of a set of terms associated with
    particular content types.
-   Each vocabulary can contain an unlimited number of terms.
-   *Keywords* are a type of “tagging” vocabulary shared amongst all
    content types that can be used as a general keyword filter.

### Working with Taxonomies

Vocabularies are managed on the Taxonomy page.

-   It is found under `Administration Bar -> Structure` `-> Taxonomy`

#### Adding Terms

You website comes with a list of predefined vocabularies.

To add term to an existing vocabulary use `Add Term`:

1.  Navigate to `Structure -> Taxonomies`
2.  Select `Add Term` for the vocabulary you want to edit. From there,
    Drupal will prompt for:
-   **Term name (Required)** - *Example: Technology.*
-   **Description (Optional)** - Description of the term may be used by
    some modules and feeds but is not required. It is more for
    internal use.

To view or manage the terms of each vocabulary:

1.  Navigate to `Structure -> Taxonomies`
2.  Click on its `list terms` link
3.  On the `list terms` page you can edit each term by clicking the
    `edit` link. On the edit term page you have several choices:
-   You must assign your term a name as a “nameless term” does
    not exist.
-   You can delete a term altogether.

### Filtering with Taxonomies

The taxonomy filter is designed to assist narrowing down taxonomy
listings to find topics that are tagged by multiple terms.

## Menu Creation

Menus are a collection of links (menu items) that are used to navigate a
website. Site Managers have the ability to remove, add and rename menus
and menu items/tabs. Editors can only add menu items to existing menus.

### Creating a menu

1.  Navigate to the Menus page (***Structure &gt; Menus)***
2.  Click **Add menu**.
3.  In the **Title** field, enter a title (required).
4.  In the **Description** field, enter a description (optional).
5.  Click **Save**.

#### Adding a link to a menu

1.  Navigate to the Menus page (***Structure &gt; Menus)***
2.  Locate a menu to edit and click **add link**
3.  In the **Menu link title** field, enter the title as it will be
    displayed in the menu.
4.  In the **Path** field, enter a path for the link. This can be an
    internal Drupal path such as node/add (see "Before you begin" above)
    or an external URL such as http://example.com.
    Enter &lt;front&gt; to link to the front page.
5.  In the **Description** field, enter the text that will be displayed
    when a user hovers over the link.
6.  Enable any of the following options:
  - **Enabled**: If the link is not enabled, it will not be displayed in
    the menu.
  - **Expanded**: If this option is enabled and the menu link has
    children, the first level children of the menu link will always
    be expanded.
7.  In the **Parent link** list, select the parent of the link.
8.  In the **Weight** list, select the relative weight of the link.
    Links with the "lightest" weight will display higher in a menu.
    Links with the same weight will display in alphabetical
    order (Optional).
9.  Click **Save**.

#### Adding page to menu

1.  Navigate to the content editing screen (*Find content &gt;Choose
    content &gt; Edit*) for the node you want to add to the menu. This
    can also be done when you first create the content.
2.  Click the checkbox marked **Provide a menu link**. The menu options
    will appear.
3.  In the **Menu link title** field, enter the title as it will be
    displayed in the menu.
4.  In the **Description** field, enter the text that will be displayed
    when a user hovers over the link.
5.  In the **Parent item** list, choose the menu that should display
    this item. Note: the menu you want will only appear in this list if
    you have assigned it to the content type of the node you
    are editing. See "Before you begin" above.
6.  In the **Weight** list, select the relative weight of the
    link (Optional).
7.  Click **Save**.

## Document Accessibility

Providing documents in a range of formats will enable people with
different abilities and learning styles to choose the format that works
best for them.

Word documents and PDFs uploaded to your website must be formatted and
edited adequately for accessibility. The University of Guelph’s
**Diversity and Human Rights (DHR)** department has a [web page
dedicated to helping you create accessible
documents](https://www.uoguelph.ca/diversity-human-rights/accessibility/information-and-communication-document-accessibility).

It is recommended that clients go through their content and ensure their
documents are WCAG 2.0 AA compliant.

## Multimedia Accessibility

The University's position on web video is:

-   We have lots of web accessibility problems, and we're prioritizing
    what we work on
-   We have prioritized web video accessibility near the bottom of the
    list, and we will get to it someday, but right now we don't have a
    good solution

For clients, this means you have choices:

-   For a perfectly accessible website, you cannot
    embed videos until YouTube's flash version goes away.
-   If you "image link" to YouTube, captions and transcripts
    are required.
-   You can choose not to post videos at all
-   You can choose to embed YouTube videos knowing your website will not
    be perfectly accessible, and you will have to get back to it
    someday, and there may be a cost to do so.

## SiteImprove

[The Siteimprove website application](http://siteimprove.com/) is used
for tracking technical compliance. These courses are free for anyone
from the University of Guelph. The non-technical certification is for
content contributors, managers, marketing and other members of your
organization who participate in the decision-making for your web sites.

### Monitor your Website for Accessibility Issues

The University of Guelph monitors the accessibility of its websites
using an online web governance service called SiteImprove. Once a site
is added to SiteImprove, the service will check the site for
accessibility issues, broken links, and spelling mistakes that can be
found through automated means.

For more information on how to add your website to Siteimprove or to
register for the course, contact Kian Merrikh from Office of Diversity &
Human Rights (kmerrikh@uoguelph.ca).

## Scoping and Prioritization

As you transition into AODA Remediation Team’s Platform:

1.  Create an inventory of content.
2.  Scoping and Prioritization.
3.  Workflows

### Web Inventory

Take stock and create an inventory of the department’s public-facing
websites and Web applications. This enables Site Managers to have the
information they need to make strategic decisions to improve the
accessibility of information and services on their department’s
public-facing sites.

### Scoping and Prioritization

Once the Web inventory report has been developed:

**Scoping:** Determine which Web pages are redundant, outdated, and
trivial (ROT), and ensure their removal from the department’s websites;
identify and archive online or offline Web pages of websites and Web
applications that can be archived.

**Prioritization:** The AODA remediation team we will be providing an
accessibility report once your site has been migrated over to the new
platform. The report will highlight any changes that might need to be
made with your existing content. Newly created content should be given
prioritization. Legacy (content posted before Jan 1, 2012) content
corrections should be phased throughout your process.

## Best Practices

### 1. Design & Consistency

-   Make sure all text can be highlighted and read aloud so that screen
    readers and reading tools can access them.
-   Create a website that can be used by as many as possible, in as many
    ways as possible according to user needs.
-   All functionality can be used without a mouse – from the
    keyboard alone.
-   All functionality can be used with a mouse.
-   Text, headings, buttons, fields etc. that are logically connected
    must also be visually connected.
-   Have a consistent design throughout the website.
-   Follow known website conventions.
-   Follow the standard for the format you are publishing in (for
    example HTML 5 syntax) - this will optimize your website for many
    different platforms and user agents.

### 2. Links

-   Make sure not to give instructions based solely on a location of
    content, such as ‘In the box to your right’. Supplement with a
    heading as well.
-   Make link texts that can be read out of context. Avoid ‘Click here’,
    ‘Read more.’
-   Broken links negatively affect users perception of your website, yet
    all too often it is the basics like this that are overlooked. There
    should be no broken links on your website.
-   Website link texts can be problematic. The outcome is often that
    people revert to using ‘read more’ or ‘click here’, which are not
    only inaccessible to a number of users but also make no sense when
    taken out of context.

### 3. Images

-   Avoid images of text where possible. Where not, make sure that text
    alternatives are equivalent.
-   Provide alternative text for images. These must reflect the purpose
    of the image:
-   Decorative: no alternative text.
-   Having a function: Describe the functionality.
-   Linking: Describe destination
-   Users can adapt color and font according to specific needs.
-   Ensure none of your content will cause seizures - **avoid** rapidly
    flashing content.

### 4. Colour Contrast

-   Make sure that the color of the background and the color of the text
    are sufficient contrast to each other. That way people with low
    vision can also read it.
-   Make sure that you do not give information by use of color alone,
    such as saying “In the green box you will find”. Otherwise it can
    create problems for both users with low vision or no vision, or
    people with color blindness.

### 5. Keep it small

-   As a general rule of thumb, documents and files should not be bigger
    than 10MB otherwise they will cause a range of frustrating problems
    for the user. For example, it may slow the speed of your site, cause
    problems if you have a responsive design or create a serious dent in
    mobile users’ data plans.
-   Keep it short. Metadata includes things like Alt descriptions,
    summaries, and other descriptive text. Ideally, Meta descriptions
    should be no more than 150 characters or else you risk important
    information being cut or to long to be useful.
