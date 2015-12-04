# UoGd7-Training
Business Solutions Client Drupal 7 Training Materials and Accessibility guidelines.
Guide to The University of Guelph's Drupal Web Content Management System and Template

Please use the navigation menu to begin learning about what the University of Guelph Drupal template has to offer.

## Navigation
### Basic:
[General Guide](general.md) // [Taxonomies](taxonomies.md) // [Features, Terms, Acronyms](Drupal_Features_Terms_Acroynms.md) // [WYSIWYG Info](wysiwyg-editor.md)
### Features:
[Page](features/howto-page.md) //
[Featured Item](features/howto-featured.md) //
[News](features/howto-news.md) //
[Events](features/howto-events.md) //
[Banner](features/howto-banner.md) //
[FAQ](features/howto-FAQ.md) //
[Social Media](features/howto-socialmedia.md) //
[Services](features/howto-services.md) //
[Book](features/howto-book.md) //
[People Profiles](features/howto-profiles.md) //
[Custom Content](features/howto-customcon.md) //
[Blog](features/howto-blog.md) //
[Web Forms](features/howto-webforms.md) //
[Landing Page](features/howto-landingpag.md) //
[Special Alert](features/howto-specialalert.md) //
[Course Outlines](features/howto-courseoutlines.md)

## Basic Github workflow guidelines
* The Documentation Team takes note when a new feature was shipping.
* Create a new issue to track the feature.
* When we were ready, we'd open a pull request to start iterating on the content.
* When the content was in a good place, we'd @mention the team (@github/docs) and have a peer editor review our words.
* When the feature was ready to ship, we'd merge the pull request. A webhook would fire from the content repository to our hosted Rails app; the webhook's payload updated a database row containing the article's raw Markdown.
