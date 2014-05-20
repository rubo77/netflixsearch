netflixsearch
=============

 A commandline thor script (ruby) that indexes all Netflix titles across all regions and provides simple search capabilities to list matching titles and the regions they are available in.

Usage:

thor netflix_search:search [TERM]  # lists matching titles and shows countries that have the title
thor netflix_search:updatedb       # Updates the database with a list of the titles available on all known Netflix regions
