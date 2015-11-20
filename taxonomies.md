# Taxonomies
## Summery
Taxonomy is the practice of classifying things. In Drupal, the Taxonomy module allows you to classify your website content, and it can be an important part of your information architecture.

## Planning taxonomies
The first step in establishing a taxonomy is creating a new vocabulary. Next you provide the terms that fall within that vocabulary. The arrangement can be "flat," as in a tagging system, or hierarchical, with parents and children.

Here's how you might create a taxonomy for a site arranged by musical genre:

**Vocabulary = Music**
    * Term = Classical
        * Sub-term = Concertos
        * Sub-term = Sonatas
        * Sub-term = Symphonies
    * Term = Jazz
        * Sub-term = Swing
        * Sub-term = Fusion
Sometimes you will want to create a "controlled vocabulary," where content authors can assign terms that have been predetermined. If so, you will need to add those terms to your vocabulary in advance.

## Taxonomy principles
* Each vocabulary consists of a set of terms.
* A site can have an unlimited number of vocabularies.
* Each vocabulary has an associated ID number. Each taxonomy term has an associated ID number.
* Each vocabulary can contain an unlimited number of terms.
* Within a vocabulary, terms can be ordered into hierarchies. All vocabularies can be arranged into a hierarchy without taking additional steps, if you find this useful.
* In Drupal 7, you don't need to predefine the type of vocabulary in order to create a "tagging" vocabulary.

## Working with Taxonomies
Vocabularies are managed on the Taxonomy page.
* In Drupal 7, it's found under Administration > Structure (i.e., http://yoururl/admin/structure/taxonomy)

### Adding a Vocabulary and Terms
The University of Guelph Drupal 7 template comes with a list of predefined vocabularies used by multiple UoG Modules. Most of these may need to be [filled with terms](taxonomies.md#terms)

To add a new vocabulary:
* Click 'Add vocabulary' link
* Choose a name for your vocabulary.
* Give your vocabulary a description. Modules may use this description in different ways. (For example, a module may show the description when users hover over a link.)
* Vocabularies can have hierarchies of terms. In Drupal 7 and 6, you simply arrange items to create a hierarchy.

### Terms
To view or manage the terms of each vocabulary, click on its `list terms` link. On the `list terms` page you can edit each term by clicking the `edit` link. Now, on the edit term page you have several kinds of choices:
* You can put the term in its place in the hierarchy by choosing the term's "parent"
* You must assign your term a name as a "nameless term" does not exist.
* You can decide the order in which your term will appear in lists by assigning it a "weight".
* You can delete a term altogether.

To add new terms to your vocabulary, click its `add terms` link. The list terms page also has an add terms link that does the same thing. When you add new terms you have the same options as when you edit them.

### Using Categories in Menus

The menus on your site can call for items that match specific taxonomy terms. To create a menu using Taxonomy, follow these steps:

1. Find the autopath given to your taxonomy term (*Note: To find the autopath, go to the Taxonomy > list terms page for the category to which your term belongs, and click the term. You'll be sent to a page with the autopath of your taxonomy term - save it*)
2. Go to the menus page `(Administer > Site building > Menus)`
3. Select `Add link` to the main menu
4. When you fill in the Path field you add your term as follows: category/term/ *i.e. event-heading/socials*
