# Meeting With Student affairs

Attendees: PJ Mancuso, Saman Asif, Jessica Westlake
Goal: To discuss SA website and to get them ready for production by the end of Sprint 10.

An accessibility report has been created by Saman. A second a11y report will be created after the sprint is over.

- Ask SA to commit time next week to get the site up.
- PJ will be commiting time all next week to get the site ready for release.

## Functional

* 3 panel footer needs to be rebuilt for responsiveness > use mini panel instead.
* For the 3 panel images, suggest uploading images with maximum width 380px (or larger if she plans to use them on a basic page using the full width of the content space); also recommend centering each of the logos in the uploaded image.

## Implementation

* FAQs should be using the FAQ content type (aoda-clint)
* FAQ custom teaser list should use list item code (show on aoda-web)
* Recommending uploading any images that link to other sources for the image (e.g. Feeling Better links to http://healthymindscanada.ca/wp-content/uploads/2015/09/feeling-better-now-cropped.png)
* Recommend using btn style for Additional questions and Answers (see aoda-web.uoguelph.ca/studentaffairs for example)
* Could use /<ul class="no-link-lines">/ if you do not want to see link lines on the teaser lists (see aoda-web.uoguelph.ca/studentaffairs for example)
* Change Departments button to "More departments"

## Incompleteness

* Missing SA logo
* Banner is missing if SA will be using one -> Related to Missing SA logo?
* Missing video (Are we allowing embedded video?)
* PDF's need to be uploaded
* Proper Alt tags are missing for footer images (discuss about external links)
* Question marks on contact us

## Notes:
* Remove all instances of style attribute (eg. <p style="line-height:15.6pt"> or <span style="font-size:10pt;font-family:Arial,sans-serif;">
