kai's site ig                                                   https://k3t.xyz
________________________________________________________________________________

my site lol

(forked from https://github.com/notquitek3t/k3t.xyz)

--- Dev Instructions
if you're trying to make your own site based on this, follow below:

your raw plain/html files go into the /site/ folder, with the same path as you'd
see on the url itself.

/template.html contains the header and footer, and css.

to build the site, github actions is currently used. it will create or update 
the gh-pages branch, where you can set pages to build from.

the /make file goes over each file in /site/ and puts it in between the header
and footer of /template.html . the output goes in /docs/, where you can copy
or point your web server to.