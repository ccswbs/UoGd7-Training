# Content Creation Workshop

## Taxonomy
*Taxonomy* is the practice of classifying features. In *Drupal*, the taxonomy module allows you to classify your website content, and it can be an important part of your information architecture.

### Planning Taxonomies
The first step in establishing a taxonomy is creating a new vocabulary. Next you provide the terms that fall within that vocabulary. The arrangement can be "flat", as in a tagging system, or hierarchical, with parents and children. The University of Guelph's drupal framework treats all terms as flat within the defined vocabulary.

Here's how you might create a taxonomy for a site using our predefined vocabularies:

**Vocabulary = Page Catagory**

    * Term = Athletics
    * Term = Departments
    * Term = BioPhysics

Our platform uses a *controlled vocabulary*, where only Site Managers can assign terms to vocabularies. Site Managers must add the terms in advance.

### Taxonomy Principles
* Each vocabulary consists of a set of terms associated with a particular feature.
* Each vocabulary can contain an unlimited number of terms.
* *Keywords* are a type of "tagging" vocabulary shared amongst all that can be used as a general keyword filter using the `G10 view pane`.

### Working With Taxonomies
Vocabularies are managed on the Taxonomy page.

* It is found under `Administration Bar -> Structure` (i.e. http://yoururl/admin/structure/taxonomy)


#### Adding Terms
The University of Guelph Drupal 7 template comes with a list of predefined vocabularies used by multiple UoG Modules. Most of these may need to be filled with terms.

You may populate vocabularies with terms using `Add Term`.

1. Navigate to `Structure -> Taxonomies`
2. Select `Add Term` for the vocabulary you want to edit. From there, Drupal will prompt for:

* **Term name (Required)** - The name for this term. *Example: Technology.*
* **Description (Optional)** - Description of the term (this item may be used by some modules and feeds but is not required). It is more for internal use.


To view or manage the terms of each vocabulary, click on its `list terms` link in `Structure -> Taxonomies`.

On the `list terms` page you can edit each term by clicking the `edit` link. Now, on the edit term page you have several kinds of choices:

* You must assign your term a name as a "nameless term" does not exist.
* You can delete a term altogether.

## Creating A News Article
The *News* feature allows content authors to add news articles to the website and display them in a Listing Page view, an Article Detail Page view, and a Recent News Teaser List view. Any article can be featured on any page using the Featured News Article view. Site visitors can also browse for news articles by date and category tag.

1. On the Administration bar, select `Add Content`.
2. Select `News`.
3. Enter a **Title**
4. If you have [page categories](taxonomies.md#categories) defined, select the appropriate one.
5. Enter a **Written by**.
6. In the body field enter what you want displayed on your web page. Follow this link [for more information on how to use the WYSIWYG editor.](wysiwyg-editor.md)
7. Add a feature image if there is one for the news, such as a image of the subject matter. It is required to add **Alternative Text** if the image is not a decorative one. Add a **Caption**.
8. Enter any *tags or keywords* that help categorize and organize your article.
9. If you want this web page to be accessed through your menus check the `provide a menu link`.
    1. Enter an appropriate **Title** and **Description**.
    2. In the `Parent item` drop down menu, select which menu heading you want the new link to be accessed through.
10. If you have the proper authority to publish right away, select `Published` in `Publishing options`.
11. Select Save when you are done.


## Filtering with Taxonomies

### URL alias

## Menu Creation

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

## To Display The Banner On The Front Page

1. Select `Structure` at the top of the administration bar.
2. Select `Blocks`.
3. Two options:
    * If you want a **static banner** drag *View: B1 - Image slider (Banner): Block - Manual* up to the *Top Bar* block region or select highlighted from the dropdown menu (*RECOMMENDED*).
    * If you want a **slide show banner** drag *View: B1 - Image slider (Banner): Block - Autoplay* up to the *Top Bar* block region or select highlighted from the dropdown menu.
4. Select `Save Blocks`.


### Discussions
