# Banners

* [Creating a Banner Image](howto-banner.md#creating-a-banner-image)
* [Editing a Banner Image](howto-banner.md#editing-a-banner-image)
* [Removing a Banner Image](howto-banner.md#removing-a-banner-image)
* [Displaying a Banner](howto-banner.md#displaying-a-banner)
* [Filtering Banner Images by Category on Specific Pages](howto-banner.md#filtering-banner-images-by-category-on-specific-pages)
* [Banner Block Spacing Issue](howto-banner.md#banner-block-spacing-issue)

**Content Creators** can create a site Banner with captions and a link. There can be multiple static banners that change every time the page is refreshed or they can be displayed as a slide show. For properly displayed banner, the recommended image dimensions are **1140 x 292**.

![An Example of a Banner](../.gitbook/assets/baex%20%281%29.png)

## Creating a Banner Image

1. On the Administration bar, navigate to `Add Content` &gt; `Banner`.
2. Once selected, the folowing page will appear.

   ![Banner Creation Page](../.gitbook/assets/bannercreate%20%282%29.png)

3. Enter the required information: 1. **Title** 2. **Category** 3. **Headline:** The main text attached to the image of the banner. 4. **Headline Link:** Used to hyperlink the headline text. The headline link can link to any URL. If the link is internal, please use a relative path. The headline link is mandatory. 5. **Image**: Choose the image that you would like to upload as the banner. Then select `Upload`. 6. **Alt Text**: You must enter Alt text describing the image if it is non-decorative. 7. **Summary \(Optional\)**: Appears below the headline of the banner image. 8. **Keywords \(Optional\)**: Like tags, keywords are a filtering mechanism.
4. Select the order in which you would like this banner image to appear \(random order by default, 0 = first, 1 = second\).
5. Once the above steps are completed, select `Save`.

## Editing a Banner Image

1. On the Administration bar, select `Find Content`.
2. Filter the content by "Banner" using the "type" dropdown menu.

   ![Banner Sort](../.gitbook/assets/filterbanner%20%282%29.png)

3. On the desired banner, select `edit`.
4. Make the required changes.
5. Once the above steps are completed, select `Save`.

## Removing a Banner Image

1. On the Administration bar, select `Find Content`.
2. Filter the content by "Banner" using the "type" dropdown menu.

   ![Banner Sort](../.gitbook/assets/filterbanner%20%285%29.png)

3. On the desired banner, select `delete`. **!IMPORTANT!**: Ensure that you are removing the correct banner image.

## Displaying a Banner

**/! Note**: Only Web Managers/Site Owners can configure & display banners.

1. On the Administration bar, select `Structure`.
2. Select `Blocks`.
3. Locate the "View: B1 - Image slider \(Banner\): Block - Autoplay" display.
4. Select `configure`.
5. After selecting `configure`, the banner block configure page will open.

   ![Configure Banner Block Page](../.gitbook/assets/configurebannerblock%20%283%29.png)

6. Select "Top Bar" in the drop-down menu under "Region Settings".
7. Under "Show block on specific pages" in the "Visibility Settings" section, you can choose the following display options:
   * **all pages except those listed**: The block will be displayed on all pages of the website **EXCEPT** for those listed in the field below.
   * **only the listed pages"**: The block will **ONLY** be displayed on the pages of the website listed in the field below.
8. Once the above steps are complete, select `Save Block`.

### To Display The Banner On The Front/Home Page Only

1. On the Administration bar, select `Structure`.
2. Select `Blocks`.
3. Locate the "View: B1 - Image slider \(Banner\): Block - Autoplay" display.
4. Select `configure`.
5. After selecting `configure`, the banner block configure page will open.

   ![Configure Banner Block Page](../.gitbook/assets/configurebannerblock%20%282%29.png)

6. Select "Top Bar" in the drop-down menu under "Region Settings".
7. Under "Show block on specific pages" select "only the listed pages".
8. In the text field below, enter `<front>`.
9. Once the above steps are complete, select "Save Block".

## Filtering Banner Images by Category on Specific Pages

By following the steps below, you can create a banner slideshow that is \(a\) filtered by a specific category and will \(b\) only show on specific pages.

1. Creating a Banner Category 1. On the Administration bar, select `Structure`. 2. Select `Taxonomy`. 3. Locate "Banner Category" and select `add terms`. 4. Add a term to identify each unique slideshow \(eg. Front Page\). 5. Enter a description if needed. 6. Select `Save`. 7. After selecting save, take note of the term ID associated with your new term \(you can find this is the URL when you edit the term after creating one and clicking the edit button\). Write it down or remember it for later. 8. Navigate to each banner that you want to show in this slideshow and set its category to match the one you just created. For steps on how to do this follow the [Editing a Banner Image](howto-banner.md#editing-a-banner-image) section.
2. Create a Mini Panel for you new Banner Category 1. On the Administration bar, select `Structure`. 2. Select `Mini panels`. 3. Select `Add`. 4. Enter a descriptive administrative title for your unique slideshow. 5. Enter a description if needed. ![Demo block being created](../.gitbook/assets/createbannerpanel.jpg) 6. Select `Continue`. 7. Select `Continue` again. 8. Select `Continue` again. 9. Select the cog icon in the top left corner of the Top section. 10. Select `add content`. 11. Under `View panes` select `View: B1 - Image lider (Banner): Manual`. 12. Add the category name in the category box and enter the number of items to show. 13. Select `Finish`. 14. Select the cog icon in the top left corner of the Top section. 15. Under `Style` select `change`. 16. Select `Bootstrap` and `Save`. 17. Select the cog icon on the right side of `View: B1...` 18. Under `Style` select `change`. 19. Select `No markup at all` and `Next`. 20. Select `Finish`.
3. Place your Mini Panel 1. On the Administration bar, select `Structure`. 2. Select `Blocks`. 3. Locate the minipanel you just created, select `Configure`. 4. Under `UG Cornerstone Theme (default theme)` select top bar. 5. Configure which pages you would like to display your banner on by adding their paths to and selecting `Only the listed pages` or select the pages you do not want to display the banner by adding their paths and selecting `All pages except those listed`. 6. To add the banner to the front page, add `<Front>` and select `Only the listed pages`. 6. Select `Save Blocks`.

## Banner Block Spacing Issue

**When you add a banner to a custom page using blocks, you will notice a small space underneath the banner, to fix that, take the following steps**.
1. Go to `Structure` &gt; `Blocks`.
2. Find the block you have added to the top bar **Should be underneath the 'Top Bar' Section**.
3. Click **Configure** and on then click *Source* on the **WYSIWYG editor**.
4. Wrap the small code bit in a `<div>` tag (if it isn't already).
5. An example of a image wrapped in a `<div>` tag is: <div><img alt="" class="img-responsive" src="/sites/default/files/YOURIMG.jpg" /></div> **Note: Don't forget the final </div> tag.** 
6. Scroll to the bottom and click `Save blocks`.
