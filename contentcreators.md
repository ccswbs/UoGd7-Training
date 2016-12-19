# Content Creators & Content Editors
As a **Content Creator or Content Editor** you must familiarize yourself with the normative criteria of [WCAG 2.0](https://www.w3.org/TR/WCAG20/). Content Creators and Content Editors are responsible for ensuring the accessibility of any web content that they upload or publish on the website. In many cases the Drupal Platform will cover the basic WCAG 2.0 Criteria but it is up to the Content Creator /  Content Editor to ensure that the content they produce is WCAG 2.0 Compliant.

## Guidlines to Making Content Accessible

### Page titles
In our Drupal 7 content management system (CMS) you give a web page a title or name when you create it. The specific field for this is called ‘Title’. It is important that this title is descriptive of what the page is about. It is the page title that is shown in the top of your browser and is read as the first thing on a web page by a screen reader.

### Text
When writing text for web pages, consider the fact that some users cannot get an overview of a page visually, as opposed to structurally. Make sure that pages are divided into logical sections each given a heading that is descriptive of the section. You can use several levels of headings: Heading 1, Heading 2, etc. so that assistive technologies can render them as headings.

Because of low vision some users will perceive a web page very differently to the way other users would visually perceive it. Therefore, make sure not to give important information solely by the use of color or with an instruction requiring sensory skills. For example, avoid writing only things like: …you can read more about the event in the blue box to the right’. It is fine to write something like this if you supplement it with something that all users can find, such as an additional text: ‘…you can read more about the event in the blue box to the right by the heading Events in March.’ This way you are also giving text that all users will be able to find.

### Links
When you add links on a page write link texts that make sense when read out of context. For instance, avoid using link texts such as ‘Read more,’ ‘Here,’ ‘Click here,’ ‘Publication,’ etc. It will be better to write ‘You can read more about the Assistive Technologies event here’ for example. This way you are giving a link text that in itself is a good indicator of what the destination page is about.

### Colours
Use of Color: Color is not used as the only visual means of conveying information, indicating an action, prompting a response, or distinguishing a visual element.
Contrast (Minimum): The visual presentation of text and images of text has a contrast ratio of at least 4.5:1, except for the following:

* Large Text: Large-scale text and images of large-scale text have a contrast ratio of at least 3:1;
* Incidental: Text or images of text that are part of an inactive user interface component, that are pure decoration, that are not visible to anyone, or that are part of a picture that contains significant other visual content, have no contrast requirement.
* Logotypes: Text that is part of a logo or brand name has no minimum contrast requirement.

### Documents
Can the content be uploaded as a web page instead of a [document](https://www.uoguelph.ca/accessibility/web/what-fix/documents)?
Can you request an accessible version of the document prior to posting it online?
Have you reviewed the Office of Diversity and Human Rights' [Tipsheets on Document Accessibility](https://www.uoguelph.ca/diversity-human-rights/accessibility/information-and-communication-document-accessibility)?
Have you visited the [Accessible Digital Office Document Project (ADOD)](http://adod.idrc.ocad.ca/) for additional guidance?

### Images
When you add images to a web page consider the fact that some users cannot see images. They need a text alternative. In our CMS, this is stated as ”alternative text” or ”alt text.” The text given here is not visually displayed on the page but is hidden in the code to be accessed by screen readers.

Describe the purpose of the image and not necessarily what the image is of. If the image is linking, it is important to describe where the link goes to/what happens when clicking on the image. If the image is solely used for decorative purposes such as creating an ambience or a visual context, then it should have no alternative text. If the image contains information that information should be given in the alternative text.

Avoid using images of text. This means that you should avoid writing text in an image editing program and saving it as an image. Many of the types of software that reads text aloud (for instance used by dyslexics) cannot read images of text. This is because you cannot highlight text within an image to have it read out to you. (Some of these types of software can read alternative texts, but far from all. And they should not be confused with screen reader software used by the visually impaired. These are much more advanced). Images of text also tend to pixelate and become blurry upon magnification making them difficult to read.

### Video and audio
If you are using video or audio clips on a web page there are several criteria to consider, such as captioning and audio description of video. Audio description is an extra track explaining what happens on the screen to visually impaired users. If you are not able to provide your videos with audio descriptions then give an alternative in the form of a transcript that is uploaded or linked to from the page. But be aware that without audio descriptions you cannot be AA compliant, only A-compliant. If the content is solely visual (no sound) or only audio (no visual) then a text version is an accepted alternative on both levels.


### Tables
When using data tables with information, it is important to indicate headings for rows and/ or columns. The way to do this is very CMS specific. In some cases the editor provides an accessibility tab where this information can be entered when using data tables.

### Lists
When using a list of items make sure to use the function for this that is built into the editor in the CMS. This will ensure that accessible code is entered for lists. Avoid just making dots that
look like a list (such as asterisk, dash etc.).

## Making Other General Content Accessible
When adding other types of content,for example a button or icon, please keep in mind the [Top 5 Accessibility Tips](accessibilitytop.md) as well as ensure that you reference the [Style Guide](styleguide.md) for assistance. If you require more assistance, we suggest that you reach out to your Web Managers / Site Owners.
