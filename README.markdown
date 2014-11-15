# cr (Ribbon Theme) - Slide Show (S9) Template Pack

## What's Slide Show (S9)?

A Ruby gem that lets you create slide shows and author slides in plain text
using a wiki-style markup language that's easy-to-write and easy-to-read.
More [Slide Show (S9) Project Site](http://slideshow-s9.github.io)

## Intro

Note, the package is configured to use the following headers in `slides.html.erb`:

    author: Your Name Here
    title: Your Slide Show Title Here
    lang: Your Language Here

## Try It Yourself - How To Use the Template Pack

If you want to try it yourself, clone the template pack using `hg`. Issue the commands:

    $ cd ~/.slideshow/templates
    $ hg clone ssh://firefly.cr.ie.u-ryukyu.ac.jp/~one/hg/Members/atton/slideshow-cr

To check if the new template got installed, use the `list` command:

    $ slideshow list

Listing something like:

    Installed templates include:
       cr.txt (~/.slideshow/templates/slideshow-cr/cr.txt)

Now you're ready to use it using the `-t/--template` switch. Example:

    $ slideshow build tutorial -t cr

That's it.
