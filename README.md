pelican_autotag
===============

Automated tagging for Pelican blogs.
------------------------------------

The goal of autotag is to provide automated generation of semantic metadata -- tags -- for 
Pelican blog content. Initially, this will be solely based on the *kales* module that implements
the *OpenCalais* API. Patches or guidance on additional methodologies is welcome and 
appreciated.

WARNING
=======

This project is on hold pending the resolution of 
[Pelican bug 224](https://github.com/getpelican/pelican/issues/224). Until Pelican can track
"new" vs. "old" articles, it is not reasonable to do online queries of article content.

Thanks, Justin