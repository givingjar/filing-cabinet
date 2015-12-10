# Giving Jar Blogging Guide

In addition to sharing news about nonprofits, Giving Jar creates regular original content and progress reports on the Giving Jar Blog. This content is an early and consistent way to provide direct value to anyone interested in learning about nonprofits and the Giving Jar platform. It is also helps promote nonprofits and charitable giving.

## Setup

Run the blog software on your own computer when you are writing drafts. You will need to know or learn how to use [Git][1]/[Github][2], [Jekyll][3], and [Markdown][4]/[Kramdown][5] to run the blog and write for it.

When you're ready, proceed to [blog.givingjar.org repository][6] to get the latest blog content.

## Create a Draft

If you do not have permission to push directly to the master branch then you should fork the master branch and write your content to that repository. If you do have permission to push directly to the master branch, then lucky you! You should still consider forking or creating a feature branch for writing, just to be safe.

Either way, create your draft in the `_drafts` directory of the blog repository. Here are some naming conventions to use when creating your draft file:

* Omit the date from the name of the file.
* Always use the `.md` file extension.
* Use lowercase letters only in the filename.
* Separate words in the filename with hyphens.
* The filename should match the name of the permalink in your draft's [Front Matter][7].

Now you're ready to write!

## Content

All content on the Giving Jar Blog should stick to one of the topics listed below. Keep your content fun, educational, and positive!

### Charity Spotlights

Spotlights are published every other week in between Giving Jar progress reports and they have a specific structure to them. Refer an existing spotlight or the [Spotlight Questions][8] to see what sort of content should go in such an article.

Use the tag `spotlight` in the Front Matter of a Charity Spotlight article so Giving Jar can properly index all published spotlights.

### Giving Jar Progress Reports

Giving Jar progress reports are published fortnightly in between the charity spotlights. Summarize the work that has been accomplished and offer some insight into the next couple of weeks of work on Giving Jar.

Use the tag `progress-report` in the Front Matter of a progress report so we have a complete history of the construction of Giving Jar.

## Style Guide

If you stick with strict Markdown syntax, the styles of the blog will make your content look great in practically all situations. The style does affect the readability of an article, though.

The following tips will help you create articles that are consistent with the other articles on the blog and easy to read

* Use `##` for top-level headings (i.e. do not use single `#` headings in your articles).
* Avoid using tables to convey information. They just don't look good on small screens.
* Keep paragraphs to 5-6 sentences or fewer. Any more than that and a paragraph will look like a wall of text on a phone.
* If an idea is particularly profound or worth standing out on its own, make the sentence its own paragraph.
* Use reference-style links in your article. It makes the Markdown easier to read and if you have to replace a link, it'll save you a lot of searching and replacing.
* Avoid using HTML in your articles.
* Articles should be between 300 and 1,000 words long. This keeps the overall reading time of any one article to roughly 2-5 minutes.

### Images

Images are a great way to spice up an article but it's important that they are used consistently and proper attribution is given.

Here are the guidelines for using images in your articles:

* All images should be between 750 and 1,200 pixels wide.
* In general, use images that are twice as wide as they are tall (e.g. 750x375, 1024x512, 1200x627).
* Place each image on its own line. This will break the content up but it will also scale the images appropriately on all screen sizes.
* Use bright, colorful, and uplifting images whenever possible.
* Use the reference-style Markdown syntax for specifying images.
* Save all original images to the `/img` directory.

**Give credit where credit is due, forever and always!**

If you use an image that you did not create, save it to the `/img/ext` directory and place an attribution at the bottom of your article.

Here's an example of embedding an image in your article:

    Here's a [regular link][1] to some site.

    ![Image Alt Text][2]

    Image Credits:
    * "Some Image Title" via [Image Source Title][3]

    [1]: http://somesite.com "Some Site Title"
    [2]: /img/ext/some-image.jpg "Some Image Title"
    [3]: http://imagesource.com "Image Source Title"

Notice how the "Some Image Title" and "Image Source Title" text appears twice. Be consistent about this and someday the blog may generate the image credits automatically using the reference notation.

## Draft Review

When your draft is complete, sleep on it. Come back the next day and read it. Fix any spelling and grammar mistakes ([Grammarly][8] is an excellent tool for catching these, try the Chrome extension). Then read it out loud to yourself. Most people read as if speaking the words in their own head. Writing in a way that sounds good out loud will be that much easier to read in general.

After you have reviewed your own article, commit and push the file to GitHub and ask someone else to review the article. It can be anyone, really, but make sure they're considering the structure of the content, not just spelling and grammar. Discuss the feedback with your reviewer and quickly settle on which suggestions to incorporate.

## Publishing

*todo*



[1]: http://www.git-scm.com/ "Git Version Control Software"
[2]: https://github.com/ "GitHub Project Management"
[3]: http://jekyllrb.com/ "Jekyll Blog Aware Site Generator"
[4]: http://daringfireball.net/projects/markdown/syntax "Markdown Syntax Guide"
[5]: http://kramdown.gettalong.org/syntax.html "Kramdown Syntax Guide"
[6]: https://github.com/technical-rex/blog.givingjar.org "blog.givingjar.org repository on GitHub"
[7]: http://jekyllrb.com/docs/frontmatter/ "Jekyll Front Matter"
