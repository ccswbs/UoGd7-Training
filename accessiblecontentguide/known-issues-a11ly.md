# Known Accessibility Issues 

These are known accessiblity issues which may appear in Siteimprove reports, and can be ignored for now.

## BrightEdge cookie (#becookiebuttonbarid)

BrightEdge is a SEO solution and content performance marketing platform, used for generating web traffic
and targeted links. You may notice a short list of links at the bottom of the page on your site, labelled 
"Also of interest".

**Note**: This issue can only be fixed by BrightEdge and in the meantime site owners can ignore this error.

![Siteimprove Report](../.gitbook/assets/becookie.png)

## Scrollable element is not keyboard accessible

This issue occurs on Event pages, due to the alternate Calendar grid view. Normally, the List view is displayed first (the default).
The (inaccessible) grid is an alternative to the (fully accessible) list view (and therefore the feature as a whole is accessible.)
We are asking Siteimprove to override this issue so that it presents as a known issue but doesn't affect the accessibility score.

**Note**:  Site owners can ignore these Site Improve errors assuming they have not altered the default behavior. 

![Siteimprove Screenshot](../.gitbook/assets/scrollelem.png)

## Table Headers are not referenced correctly

This is a wide spread issue with the use of calendars for Events. Data tables can present a challenge especially if the table contains a lot of information.
Screen readers can only announce table data correctly if cells and headers are marked up correctly in the code.

Normally, the List view is displayed first (the default). The (inaccessible) grid is an alternative to the (fully accessible) list view 
(and therefore the feature as a whole is accessible.) We are asking Siteimprove to override this issue so that it presents as a known issue
but doesn't affect the accessibility score.

**Note**:  Site owners can ignore these Site Improve errors assuming they have not altered the default behavior. 
