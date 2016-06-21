---
title: Handlebars Helpers in Metalsmith
date: 2016-06-08
collection: articles
---
Over the past year or so, Metalsmith has become by go-to static site generation
system due to its modular setup that does exactly what you want. I have robust
front-end tooling already so I don't need to be dealing with all the systems a
lot of the static generators throw at you. I really only need something to
handle the template system and generation of collections. Of course Metalsmith
has these features if you wish to use their workflow, but it's easy to avoid it
if you don't.

With the abandonment of Swig, I've generally switched over to the dumber but
powerful-enough Handlebars templating engine. One of the major upsides to
Handlebars is its usage of helpers to extend functionality which is a very easy
plugin system to tie into compared to some other options out there. With a few
simple Metalsmith plugins, you can also tie into this system for creating
powerful Handlebars plugins for your own usage or including the vast library of
existing helpers as well.
