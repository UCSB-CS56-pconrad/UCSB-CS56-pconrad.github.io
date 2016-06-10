---
---

# Jekyll

Jekyll is a software package that can be used in conjunction with github.com to publish web pages easily.   
* Content is authored in markdown, and kept in github.com repositories.
* Content is published automatically to a site with the url ____.github.io every time you push changes to your repo.
* There is no database to configure, and authorization is handled by existing github.com authorization mechanisms.
* There is no "lock-in"; it is straightforward to migrate a Jekyll-based site to a platforms outside of github.com (for example, Heroku, or any host that supports Ruby.)

# Jekyll tips

* Create pages as index.md files in a directory with the name that you want the page to appear under.
 - For example, to make a page with the URL `site.github.io/topics/jekyll`, create the file `/topics/jeykll/index.md`
* `.md` files must start with what Jekyll calls *Front Matter*.  
 - The minimal front matter is two consecutive lines of exactly three hyphens `---`
 - Use this minimal front matter until you have a reason to do something more specific
 - The front matter can be used to configure things such as the title of the page, and many other things.
 - The format of the front matter is Yaml (a syntax for key/value associations that includes JSON as a subset).