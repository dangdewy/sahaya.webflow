---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---

### Usage
## Home Layout
home.html is a flexible HTML layout for the site's landing-page / home-page / index-page. 

## Main Heading and Content-injection
From Minima v2.2 onwards, the home layout will inject all content from your index.md / index.html before the Posts heading. This will allow you to include non-posts related content to be published on the landing page under a dedicated heading. We recommended that you title this section with a Heading2 (##).

Usually the site.title itself would suffice as the implicit 'main-title' for a landing-page. But, if your landing-page would like a heading to be explicitly displayed, then simply define a title variable in the document's front matter and it will be rendered with an <h1> tag.

## Post Listing
This section is optional from Minima v2.2 onwards.
It will be automatically included only when your site contains one or more valid posts or drafts (if the site is configured to show_drafts).

The title for this section is Posts by default and rendered with an <h2> tag. You can customize this heading by defining a list_title variable in the document's front matter.

---
