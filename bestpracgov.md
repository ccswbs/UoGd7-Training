# Website Governence and Accessibility Best Practices

## SiteImprove Accessibility top 5
### Text for everyone
* Make sure all text can be highlighted and read aloud so that screen readers and reading tools can access them (try turning off style sheets and images, and make sure no important information is missing. Another way to test is to access the website with reading tools or to test with real users of assistive technologies)
* Avoid images of text where possible. Where not, make sure that text alternatives are equivalent.
* Provide alternative text for images: These must reflect the purpose of the image:
* Decorative: no alternative text
* Having a function: Describe this
* Linking: Describe destination

### Versatility
Create a website that can be used by as many as possible, in as many ways as possible according to user needs.
* All functionality can be used with a mouse
* All functionality can be used without a mouse – from the keyboard alone.
* Users can adapt color and font according to specific needs.

### Association
* Text, headings, buttons, fields etc. that are logically connected must also be visually connected.
* Make sure it is also connected in the code.
* Make sure not to give instructions based solely on a location of content, such as ‘In the box to your right…’. Supplement with a heading also.
* Make link texts that can be read out of context. Avoid ‘Click here’, ‘Read more’, …

### Color for everyone
* Make sure that the color of the background and the color of the text are in sufficient contrast to each other. That way people with low vision can also read it.
* Make sure that you do not give information to the user only by use of color (such as saying ‘In the green box you will find…’). Otherwise it can create problems for both users with low vision or no vision, or people with color blindness.

### Robustness
* Have a consistent design throughout the website
* Follow known conventions.
* Follow the standard for the format you are publishing in (for example html 5 syntax) - this will optimize your website for many different platforms and user agents.

## Roles and Resonsibilities
### Mostly for web managers
If you have the responsibility of ensuring accessibility on a website, then all the criteria in WCAG are relevant to you (usually on level AA). It is then necessary to have a fundamental understanding of the subject in order to be able to ensure for instance that through a development project and by an acceptance test what is delivered conforms to the guidelines. It is also important that you as the responsible
party make the right requirements in the requirement specifications and understand how meeting them is ensured. It is also important that you train your web editor colleagues on how to publish content the ‘accessible way.’ This way, when content is added it furthers your site’s accessibility rather than introducing new accessibility issues.

If you have policies in your organization for communication and design it is a good idea to integrate the relevant accessibility criteria here.

If your job is to ensure accessibility on an existing website it is often a question of what can realistically be fixed now. It is always better to be 70% accessible rather than 60% accessible for instance because it makes the website accessible for more users.

Start out by using tools that can assist you in getting a quick overview of issues. For large websites the effort most likely needs to be prioritized. A good starting point is your main pages, for example the front page and a selection of your template pages. Often it requires minor adjustments in the CSS or in a template and an issue will be fixed and take effect across all pages. If there is special content on some web pages such as video, dynamic content or self-services it is a good idea to include these pages also.

There can be areas where it is not possible to do a fix on the current website or that should be directed to development. Write these down so they are not forgotten and bring them up in the next relevant meeting. Make a strategy for testing accessibility on a regular basis. It can be quarterly for instance as a part of the organization’s web strategy.

### Mostly for web editors / content creators
#### Page titles
In a CMS you give a web page a title or name when you create it. In some systems there is also a specific field for this called ‘Title’. It is important that this title is descriptive of what the page is about. It is the page title that is shown in the top of your browser and is read as the first thing on a web page by a screen reader.

#### Text
When writing text for web pages, consider the fact that some users cannot get an overview of a page visually, as opposed to structurally.Make sure that pages are divided into logical sections each given a heading that is descriptive of the section. You can use several levels of headings: Heading 1, Heading 2, etc. so that assistive technologies can render them as headings).

Because of low vision some users will perceive a web page very differently to the way other users would visually perceive it. Therefore make sure not to give important information solely by the use of color or with an instruction requiring sensory skills. For example, avoid writing only things like: …you can read more about the event in the blue box to the right’. It is fine to write something like this if you supplement it with something that all users can find, such as an additional text: ‘…you can read more about the event in the blue box to the right by the heading Events in March.’ This way you are also giving text that all users will be able to find.

If you change the language in the text make sure you state the language of that piece of text. In the code this is done with the attribute lang=”” for the text unit. If you have a good CMS it will allow you to highlight the piece of text and choose language from a drop down menu.

#### Links
When you add links on a page write link texts that make sense when read out of context. For instance avoid using link texts such as ‘Read more,’ ‘Here,’ ‘Click here,’ ‘Publication,’ etc. An example could be a text: ‘You can read more about the Assistive Technologies event here.’ Another example could be writing: ‘You can read more about the Assistive Technologies event here.’ It will be better to write ‘You can
read more about the Assistive Technologies event here’ for example. This way you are giving a link text that in itself is a good indicator of what the destination page is about.

#### Images
When you add images to a web page consider the fact that some users cannot see images. They need a text alternative. In most CMSs this is stated as ”alternative text” or ”alt text.” The text given here is not visually displayed on the page but is hidden in the code to be accessed by screen readers. (The alternative text is not the same as a tooltip: The text displayed when you hover over the image from the ‘title’ attribute).
Close your eyes and visualize what information you need if you cannot see the image. Describe the purpose of the image and not necessarily what the image is of. If the image is linking, it is
important to describe where the link goes to/what happens when clicking on the image. If the image is solely used for decorative purposes such as creating an ambience or a visual context, then it should have no alternative text. If the image contains information that information should be given in the alternative text.

Avoid using images of text. This means that you should avoid writing text in an image editing program and saving it as an image. Many of the types of software that reads text aloud (for instance used by dyslexics) cannot read images of text. This is because you cannot highlight text within an image to have it read out to you. (Some of these types of software can read alternative texts, but far from all. And they should not be confused with screen reader software used by the visually impaired. These are much more advanced). Images of text also tend to pixelate and become blurry upon magnification making them difficult to read.

#### Video and audio
If you are using video or audio clips on a web page there are several criteria to consider, such as captioning and audio description on video. Audio description is an extra track explaining what happens on the screen to visually impaired users. If you are not able to provide your videos with audio descriptions then give an alternative in the form of a transcript that is uploaded or linked to from the page. But be aware that without audio descriptions you cannot be AA compliant, but only A-compliant. If the content is solely visual (no sound) or only audio (no visual) then a text version is an accepted alternative on both levels.

#### Tables
When using data tables with information it is important to indicate headings for rows and/ or columns. The way to do this is very CMS specific. In some cases the editor provides an accessibility tab where this information can be entered when using data tables.

#### Lists
When using a list of items make sure to use the function for this that is built into the editor in the CMS. This will ensure that accessible code is entered for lists. Avoid just making dots that
looks like a list (such as asterisk, dash etc.).


## SiteImprove Top 8 must-have Policies
1. Start with the basics – Broken Links
Broken links negatively affect a user’s perception of your website, yet all too often it’s the basics like this that are overlooked. To ensure your site is always at its best, set a policy that there should be no broken links on your website. If you’re short on time or resources, make the task more manageable by setting a policy that is restricted to your most popular pages within the last seven days.
2. Keep it short for best SEO practices
Meta descriptions are commonly used on search engine result pages (SERPs) to display preview snippets for a given page. Ideally, Meta descriptions should be no more than 155 characters or else you risk important information being cut and dampened SEO efforts that result in less website traffic. To mitigate this set a policy which limits your meta descriptions to 155 characters or less.
3. Keep it small
A simple thing to overlook when adding documents and media files to a website is their size. As a general rule of thumb, documents and files shouldn’t be bigger than 10MB otherwise they’ll cause a range of annoying problems for the user. They’ll slow the speed of your site, cause problems if you have a responsive design and put a serious dent in mobile user’s data plans. To avoid this set a policy that will inform you and your team when people upload documents and files over a set size.
4. Link it right
Website link texts can be problematic. While many editors are aware of how to correctly use link texts, time, pressure and repetition can cause complacency. The outcome is often that people revert to using ‘read more’ or ‘click here’, which are not only inaccessible to a number of users but also make no sense when taken out of context. To stay on top of this set up a policy that will alert you when one of these exact phrases finds its way onto your website.
5. Testing 1, 2, 3
When training new employees to use your CSM, or switching to a new system, it’s common for learning errors to occur. One common error is to use the word ‘test’ in the H1 heading field, which someone publishes, and then hides. While technically this page is hidden, for those using assistive technologies such as screen readers this will still be present in the source code - meaning your ‘test’ page is actually out there for people to find. One way to ward against this is to set up a policy that will alert you to all H1 headings that contain the word test.
6. Out with the old, in with the new
Having old documents and media files on your website causes a range of problems. On the most basic level they are obviously old, which can mean they don’t comply with new or recently introduced design and content policies. For those websites that contain important information such as pricing, and timetables, this is even more problematic as you risk misinforming your users or finding yourself in muddy legal waters. To avoid this headache always set up a policy that will alert you when documents older than a set date appear on your site.
7. What happens in Vegas, stays in Vegas
Uploading internal documents to a website happens way more often than you’d think, usually in the form of a Microsoft Word or PowerPoint document. Not only can these documents contain private information but they also create a range of other issues as Word documents are for example easy to manipulate. Microsoft documents also provide a wealth of information such as creation date and author. Tablet and mobile users also often struggle to open them or end up viewing a distorted document. To safeguard against this set up a policy, which will alert you when editable documents, such as those made in Microsoft Word, are uploaded to your site.
8. Cut the jargon & unwanted content
Jargon words can vary greatly, and can include a set list of words or phrases that should never appear on your site. Similarly, there are often a number of unwanted words one wouldn’t want to appear on their website such as a competitor’s name or an ex-employees name. These can also include words that should always be spelt or presented in a certain way - such as private firms wanting a trademark to appear in conjunction with all product names. To ensure your content and wording is exactly as you wish set up a policy that will instantly alert you to violations.
