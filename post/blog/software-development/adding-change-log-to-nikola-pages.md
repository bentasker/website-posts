# Adding Dates to Nikola's Static Pages

Nikola automatically adds the date of publication and updates to blog posts, but most templates do not do the same for pages.
I use static pages for things like policies and I wanted them to be able to show when a policy was last updated.
This post describes adjusting a Nikola theme to show publication dates and to automatically append a list of dates that the page was changed.


Installing the page template
We need to copy the page template into our theme:
nikola theme -c page.tmpl

Having done this, though, I found that my theme reuses the story template:
cat themes/btasker/templates/page.tmpl
<%inherit file="story.tmpl"/>

So I needed to copy...

[Read more](https://www.bentasker.co.uk/posts/blog/software-development/adding-change-log-to-nikola-pages.html?utm_source=github)
