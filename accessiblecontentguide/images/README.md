# Images

When you add images to a web page, consider the fact that some users cannot see images and therefore require a text alternative in order to recieve the same amount of information as a user who can see the image. In our CMS, providing a text alternative to images is referred to as ”alternative text” or ”alt text.” The text given here is not visually displayed on the page but is hidden in the code to be accessed by screen readers.

## Writing appropriate alternative "alt" text

* Describe the purpose of the image and not necessarily the image itself. 
  * If the image is functional, use the alt text to summarize the information provided or describe its purpose. 
  * If the image is hyperlinked, it is important to describe the link destination, or what happens when the linked image is selected.
  * If the image is solely used for decorative purposes such as creating ambience or visual context, then it should have no alternative text \(empty alt atribute --&gt; `alt=""`\)

For more information on accessible images, please see the [W3C Image Tutorial](https://www.w3.org/WAI/tutorials/images/).

## Avoid using images of text

Avoid using images of text. This means that you should avoid writing text in an image editing program and saving it as an image. Many assistive technology applications cannot read images of text. This is because you cannot highlight text within an image to have it read out to you. Images of text also tend to pixelate and become blurry upon magnification, making them difficult to read.

## How to add alt text

1. From the Drupal text editor, click on the image icon in the menu bar. This action will open a window like this: 

   ![WYSIWYG image properties window](../../.gitbook/assets/alt-text-wysiwyg%20%282%29.png)

2. Add short, descriptive alternative text in the "Alternative Text" field.
3. Click `OK`. 
4. Click `Save`.

