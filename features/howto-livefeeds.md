# Live Feeds

 * [Live Social Media Feeds](#to-add-a-live-twitter-feed-to-the-home-page)
 * [External Source Live Feed](#to-display-a-live-feed-from-an-external-source)
 * [Multiple Combined Feeds](#to-display-multiple-combined-feeds)

## To Add a Live Twitter Feed to the Home Page:

1. From the top administration bar, navigate to `Configuration` > `Web Services` > `Twitter`. 
2. At least one authenticated Twitter account is needed to have a live feed work properly. After the authenticated account is set up, you can also pull tweets from non-authenticated accounts, as long as you know the twitter handle (@username).
3. Select `Go to Twitter to add an authenticated account`. You will be prompted to sign into your Twitter account. 
4. Enter your username and password, then select `Authorize app`. 
5. Now that your authenticated account has been added, add any required non-authenticated accounts but pasting the handle in the "Twitter account name" field. 
6. Next, return to the home page. Select `Customize this page` at the botton of the screen. 
7. For the appropriate region, select `+` (plus sign). 
8. When the Add Content window opens, select `View panes` from the side menu. 
9. Select `View: S5 - Live Feed (Twitter)` from the list. 
10. In the "Num item" field, enter the number of tweets you would like to be displayed at a time. 
11. Select `Finish`. 
12. Select `Save` at the bottom of your screen. 

______

## To Display a Live Feed from an External Source:

### Step One: Add the Live Feed

1. From the administration bar, navigate to `Configuration` > `Feed aggregator` > `Add feed`. 
2. Enter the title and URL for the feed.
3. Set the update interval and number of news items shown in the block.
4. Categorize the news items if categories are defined.
5. Select `Save`.

### Step Two: Find the Aggregator Feed ID

1. From the Feed aggregator menu, click on the name of the feed. In the URL, you will see the feed ID, at `<site_name>/aggregator/sources/<feed_ID>`.

### Step Three: Add the Live Feed View Pane

1. From the page you would like to add a live feed to, select `Customize this page` at the botton of the screen.
7. For the appropriate region, select `+` (plus sign). 
8. When the Add Content window opens, select `View panes` from the side menu. 
9. Select `View: S5 - Live Feed` from the list. 
1. Override the title and add a new one if desired. If it is not overridden, no title will show.
2. Enter the Aggregator Feed ID.
3. Select `Finish`.
4. Select `Save` at the bottom of the page.

______

## To Display Multiple Combined Feeds:

### Step One: Create a Feed Category

1. From the administration bar, navigate to `Configuration` > `Feed aggregator` > `Add category`.
2. Enter a title for the feed category. 
3. Select `Save`. 

### Step Two: Find the Aggregator Feed ID

4. On the Feed aggregator page, you will see the category you created appear under "Category overview."
5. Click on the new category. 
6. You will see the Aggregator category ID in the URL, at `<site_name>/aggregator/categories/<category_ID>`.

### Step Three: Add the Multiple Combined Feed View Pane

1. From the page you would like to add a combined live feed to, select `Customize this page` at the botton of the screen.
7. For the appropriate region, select `+` (plus sign). 
8. When the Add Content window opens, select `View panes` from the side menu. 
9. Select `View: S5 - Live Feed (Category)` from the list. 
1. Override the title and add a new one if desired. If it is not overridden, no title will show.
2. Enter the Aggregator Category ID.
3. Select `Finish`.
4. Select `Save` at the bottom of the page.

