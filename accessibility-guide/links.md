#Links

* [Accessible Links](#accessible-links)
* [External Links](#external-links)
* [Internal Links](#internal-links)
* [Email Links](#email-links)
* [Anchor Links](#anchor-links)

##Accessible Links
When adding links to a page, ensure that the user can determine the destination of the link. Avoid using ambiguous terms like "click here," "more" or "this" for link text. Instead, use descriptive link text to help users with a screen reader understand the context and destination of the link. For example, instead of "Click Here" you can use "read more about this topic here."

##External Links

**URL (External Path)**: Any link that is NOT under www.uoguelph.ca/*yourSiteName*
  * Ensure that the "link type" dropdown menu is set to `URL`.
  
  ![External URL Hyperlink](images/externalURL.png)
  
  * Paste the link where you would like this text to hyperlink to (Eg:www.google.ca) in the "URL" field.
  * Once completed, select `OK`.

##Internal Links

**Internal path**: Any link that is under www.uoguelph.ca/*yourSiteName*
  * Ensure that the "link type" dropdown menu is set to `internal path`.
        
   ![image](images/ckeditorlinkinternalpath.png)
        
   * Search for the internal page by typing the first few characters of the page name in the "Link" field.
   * Select the page you want to link from the list of suggestions.
  
   ![image](images/ckeditorlinksuggestions.png)
          
    * Once completed, select `OK`.

##Email Links

**Email**: Hyperlink text to an email address that, upon selection, will prompt the user to email the specified address.
   * Ensure that the "link type" dropdown menu is set to `E-mail`.
        
   ![Insert Email Image](images/emailLink.png)
        
    * Enter the email address you would like this text to hyperlink to.
    * If applicable, enter the email subject and message body into their respective fields.
    * Once completed, click `OK`.

##Anchor Links

Anchor links are links that will take the user to a specific spot on the same page. 

###How to create anchor links

1. In the Drupal text editor, highlight some text to be used as the anchor (the spot the link will jump to). 
2. Select the anchor button (flag icon). This will open the Anchor Properties dialog box. 

 ![Drupal text editor anchor button](/images/anchor-anchor-button.png)
 
2. Enter a name for the anchor. Select `OK`.

 ![Drupal text editor anchor dialog box](/images/anchor-dialog-box-1.png)
 
3. Highlight text to be used as the link. 
4. Select the link button (chain link icon). 

 ![Drupal text editor link button](/images/anchor-link-button.png)
 
5. The Link dialog box will open. Under link type, select "link to anchor in the text."
6. Using the "By element ID" drop-down menu, select the anchor's name. It is important that the anchor is selected by element ID and not by name. Select `OK`.

 ![Drupal text editor link dialog box](/images/anchor-link-dialog.png)


