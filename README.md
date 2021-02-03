publistf Plugin for DokuWiki
============================

NOTE: This plugin build on the bib2tpl which has not been support since 2013,
I am looking at [bibtexbrowser](https://github.com/monperrus/bibtexbrowser)
as a possible replacement for parsing and generating output of Bibtex.

Includes the content of BibTeX files in DokuWiki pages in a flexible way.

All documentation for this plugin can be found at
https://www.dokuwiki.org/plugin:publistf

Additionally, use parameter author:page:authorpage if you want links to
websites of coauthors added automatically to the bibtex entries. The
specified authorpage page or file requires author URLs followed by their
names (as they appear fully formatted), and will automatically replace
Author Name with [[Author_URL|Author Name]]
 (modified by Karl Moritz Hermann <mail@karlmoritz.com>)

If you install this plugin manually, make sure it is installed in
lib/plugins/publist/ - if the folder is called different it
will not work!

Please refer to https://www.dokuwiki.org/plugins for additional info
on how to install plugins in DokuWiki.

### Copyright and License

Copyright (C) 2010      Raphael Reitzig <code@verrech.net>

Copyright (C) 2013      Jorge Juan <jjchico@gmail.com>

Copyright (C) 2016-2021 Hans-Nikolai Viessmann <hans AT viess.mn>

See COPYING and file headers for license info.
