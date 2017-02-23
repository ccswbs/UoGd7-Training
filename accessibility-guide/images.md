#Images

When you add images to a web page, consider the fact that some users cannot see images and therefore require a text alternative in order to recieve the same amount of information as a user who can see the image. In our CMS, providing a text alternative to images is referred to as ”alternative text” or ”alt text.” The text given here is not visually displayed on the page but is hidden in the code to be accessed by screen readers.

* [Alt Text](#alt-text)

### How to write appropriate alternative "alt" text
* Describe the purpose of the image and not necessarily the image itself. 
    * If the image is hyperlinked, it is important to describe the link destination, or what happens when the linked image is selected.
    * If the image is solely used for decorative purposes such as creating ambience or visual context, then it should have no alternative text. 
    * If the image contains information that can only be found within the image, then that information should be given in the alternative text.
* Avoid using images of text. This means that you should avoid writing text in an image editing program and saving it as an image. Many assistive technology applications cannot read images of text. This is because you cannot highlight text within an image to have it read out to you. Images of text also tend to pixelate and become blurry upon magnification, making them difficult to read.
* If the image is purely decorative and provides absolutely no information to the user other than to make the page look better, ensure that there is no alt text provided, BUT there is an empty alt attribute (Eg: alt="").
