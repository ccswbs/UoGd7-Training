# Taxonomies

_Taxonomy_ is the practice of classifying content. In Drupal, the taxonomy module allows you to classify your website content and direct it at certain audiences. This module is useful for everything from menu and navigation organization, to view & display options.

## Planning Taxonomies

The first step in establishing a taxonomy is creating a new vocabulary. Next, terms that fall within that vocabulary are defined. The arrangement can be "flat", as in a tagging system, or hierarchical, with parents and children. The University of Guelph's Drupal framework treats all terms as flat within the defined vocabulary.

An example of how you might create taxonomy for a site using our predefined vocabularies:

**Vocabulary = Page Category**

**Term = Workshops**

Our platform uses a _controlled vocabulary_, in which only Site Managers can assign terms to vocabularies.

## Taxonomy Principles

* Each vocabulary consists of a set of terms associated with a particular feature.
* Each vocabulary can contain an unlimited number of terms.
* _Keywords_ are a type of "tagging" vocabulary shared amongst all content types.

## Working With Taxonomies

Vocabularies are managed on the Taxonomy page.

* It is found under `Administration Bar` &gt; `Structure` \(i.e. [http://yoururl/admin/structure/taxonomy](http://yoururl/admin/structure/taxonomy)\)

### Adding Terms

The University of Guelph Drupal 7 template comes with a list of predefined vocabularies used by multiple UoG Modules. Most of these may need to be filled with terms.

You may populate vocabularies with terms using `Add Term`. 1. Navigate to `Structure` &gt; `Taxonomies` 2. Select `Add Term` for the vocabulary you want to edit. From there, Drupal will prompt for:

* **Term name \(Required\)** - The name for this term. Example: Technology.
* **Description \(Optional\)** - Description of the term \(this item may be used by some modules and feeds but is not required\).

To view or manage the terms of each vocabulary:

1. Navigate to `Structure` &gt; `Taxonomies`
2. Click on its `list terms` link
3. On the "List Terms" page you can edit each term by clicking the `edit` link. You can also a delete a term from here. 

### Filtering with Taxonomies

The taxonomy filter is designed to assist narrowing down taxonomy listings to find topics that are tagged by multiple terms.

