:::: JEKYLL INTEGRATION ::::
============================

• Jekyll Installation:
	$ gem install jekyll

• Running Jekyll :
   jekyll --server
   ( and then browse to http://0.0.0.0:4000 )


:::: AN OVERVIEW OF EACH FOLDER ::::

_config.yml
------------
Stores configuration data. A majority of these options can be specified from the command line executable but it’s easier to throw them in here so you don’t have to remember them.

_layouts
---------
These are the templates which posts are inserted into. Layouts are defined on a post-by-post basis in the YAML front matter. The liquid tag {{ content }} is used to inject data onto the page.

_posts
-------
Your dynamic content. The format of these files is important, as named as YEAR-MONTH-DATE-title.MARKUP. The Permalinks can be adjusted very flexibly for each post, but the date and markup language are determined solely by the file name.
       
_site
------
This is where the generated site will be placed once Jekyll is done transforming it. 


index.html and Other HTML/Markdown/Textile Files
------------------------------------------------

Granted that this file has a YAML Front Matter section, it will be transformed by Jekyll. The same will happen for any .html, .markdown, or .textile file in your site’s root directory or directories not listed above.             


Other Files/Folders
-------------------

Every other directory and file except for those listed above will be transferred over as expected. For example, you could have a css folder, a favicon.ico, etc, etc.


:::: BASE-URL OPTION ::::
=========================

If you are using base-url option like
	jekyll --server --base-url '/blog'

then make sure that you access the site at
	http://localhost:4000/blog/index.html .

Just accessing
 	http://localhost:4000/blog
will not work.    


• For more information on Configuration, Deployment check out
		https://github.com/mojombo/jekyll/wiki/usage