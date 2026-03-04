---
layout: post
title: Inclusions 
tags: [Test, Image]
categories: Tutorial
bootstrap: true
---

# Glowing Title
* Thanks to Farrow's site for the code.
* Including the class in the title in `_config.yml` breaks.
* In `_includes/default/navbar.liquid` `site.title` couldn't be altered without affecting other behaviours of the theme. 
* So _liquid_ code was used there to create a new variable `hltitle` with hl-html class for this specific use only.
* css is included in `_sass/custom.scss` file created and this custom was included in `_sass/type-on-strap.scss` as `@import 'custom';` 
* Whoa!!! It works

# Breadcrumb without plugin
* Create the file `_includes/breadcrumbs.html`.
* In `_includes/default/navbar.liquid` inject the liquid command at appropriate place. `{% include breadcrumbs.html %}`
* But it reads and breaks the permalink, so not accurate.
* Gets space that is extra without any good functions.
* Let's discard it.

# Latex css 
* Inclusion in head.liquid though works, breaks the theme features, but do not crashes, at least!

# Including google font
* link style sheet in _`includes/default/head.liquid`.
* `<link href="fonts.googleapis.com" rel="stylesheet">` didn't work for sofia?
* `<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Sofia">` Worked for Sofia print.
* Set in `_sass/base/_variables.scss` set the first choice to 'Sofia' before fall backs for `font-family-logo` variable of the theme that sets fonts for site title and subtitle. 
* Done in this line `$font-family-logo: 'Sofia','Source Sans Pro', Helvetica, Arial, sans-serif;`

# Printing pdf nicely
* @print defined properly in `_sass/base/_global.scss` .
* Note to keep colour black, font latexish Charter family.

# Portfolio making
* Based on Portfolio for projects that has a special page with projects in a folder `_portfolio`, a new item can be designed for other purpose.
* How it's done?
 - Create a file in _pages_ named _PhyUtkal_ like _portfolio.md_
 - This may contain it's own content. 
 - It will automatically fetch the pages from `_PhyUtkal` folder and arrange images in a grid and clickable.
 - Each page in the source folder will have it's detailed content. Here, we use paper details. 
 - Now there can be no subfolder? create pages for individual papers and then link them to this page.
    
# Call out system
Looking at quarto, material mkdocs, genspeck etc., lets try 'call out' option if possible `html` way! 
* Bootstrap to be enabled in yaml.

<div class="alert alert-primary" role="alert">
  <strong>Well done!</strong> You successfully read this important alert primary message.
</div>
<div class="alert alert-secondary" role="alert">
  <strong>Heads up!</strong> This **alert secondary** needs your attention, but it's not super important.
</div>
<div class="alert alert-success" role="alert">
  <strong>Well done!</strong> You successfully read this important 'alert success' message.
</div>
<div class="alert alert-danger" role="alert">
  <strong>Heads up!</strong> This 'alert danger' needs your attention, but it's not super important.
</div>
<div class="alert alert-warning" role="alert">
  <strong>Warning!</strong> Better check yourself, you're not looking too good.
</div>
<div class="alert alert-info" role="alert">
  <strong>INFO:</strong> alert-info.
</div>
<div class="alert alert-light" role="alert">
  <strong>Well done!</strong> You successfully read this important alert light message.
</div>
<div class="alert alert-dark" role="alert">
  <strong>Heads up!</strong> This alert dark needs your attention, but it's not super important.
</div>

### liquid way for single paragraph.
{: .alert alert-info}
Then the liquid way might be tried.
When using Kramdown {: .notice} can be added after a sentence to assign the '.notice' to the <p></p> element.
If you put {: #your-id-name} on the line underneath anything then it'll make an id for that element and you can link to it.

### liquid way for _multiple_ paragraphs.
{% capture alert alert-info %}
#### liquid way for _multiple_

* You can now have cover images on blog pages
* Drafts will now auto-save while writing
{% endcapture %}

### html way
<div class="alert">
  <h4>Message</h4>
  <p>A basic message.</p>
</div>