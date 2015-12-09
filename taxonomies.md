# Taxonomies
## Summary
*Taxonomy* is the practice of classifying things. In *Drupal*, the taxonomy module allows you to classify your website content, and it can be an important part of your information architecture.

## Planning Taxonomies
The first step in establishing a taxonomy is creating a new vocabulary. Next you provide the terms that fall within that vocabulary. The arrangement can be "flat", as in a tagging system, or hierarchical, with parents and children.

Here's how you might create a taxonomy for a site arranged by musical genre:

**Vocabulary = Music**

    * Term = Classical
        * Sub-term = Concertos
        * Sub-term = Sonatas
        * Sub-term = Symphonies
    * Term = Jazz
        * Sub-term = Swing
        * Sub-term = Fusion

Sometimes you will want to create a *controlled vocabulary*, where content authors can assign terms that have been predetermined. If so, you will need to add those terms to your vocabulary in advance.

## Taxonomy Principles
* Each vocabulary consists of a set of terms.
* A site can have an unlimited number of vocabularies.
* Each vocabulary can contain an unlimited number of terms.
* Within a vocabulary, terms can be ordered into hierarchies. All vocabularies can be arranged into a hierarchy without taking additional steps, if you find this useful.
* In Drupal 7, you don't need to predefine the type of vocabulary in order to create a "tagging" vocabulary.

## Working With Taxonomies
Vocabularies are managed on the Taxonomy page.
* In *Drupal 7*, it's found under `Administration Bar -> Structure` (i.e. http://yoururl/admin/structure/taxonomy)

![Administration Menu Bar with Structure selected.](images/ambs.png)

### Adding a Vocabulary and Terms
The University of Guelph Drupal 7 template comes with a list of predefined vocabularies used by multiple UoG Modules. Most of these may need to be [filled with terms](taxonomies.md#terms).

To add a new Vocabulary:
* Go to `Administration -> Structure -> Taxonomies`.
* Click `Add Vocabulary` link.
* Choose a name for your vocabulary.
* Give your vocabulary a description. Modules may use this description in different ways. (For example, a module may show the description when users hover over a link.)
* Vocabularies can have hierarchies of terms. In Drupal 7 you simply arrange items to create a hierarchy.

### Terms
Once you have finished defining the vocabulary, you may populate it with terms using Add. Add terms to a vocabulary by navigating to `Structure -> Taxonomies` and selecting `Add Term` for the vocabulary you want to edit. From there, Drupal will prompt for:

* **Term name (Required)** - The name for this term. Example: Technology.
* **Description (Optional)** - Description of the term (this item may be used by some modules and feeds).

Advanced options:

* **Parents (Optional):** Select the term(s) under which this term is a subset.
* **Weight (Optional):** The weight is used to sort the terms of this vocabulary; by default they will be sorted alphabetically.
* **URL Alias**: For the UoGuelph template, *Generate automatic URL alias* should already be ticked.

To view or manage the terms of each vocabulary, click on its `list terms` link in `Structure -> Taxonomies`.

On the `list terms` page you can edit each term by clicking the `edit` link. Now, on the edit term page you have several kinds of choices:
* You can put the term in its place in the hierarchy by choosing the term's "parent"
* You must assign your term a name as a "nameless term" does not exist.
* You can decide the order in which your term will appear in lists by assigning it a "weight".
* You can delete a term altogether.
