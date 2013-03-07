Slugify
=======

A string extension to create slugs for your web apps.

## How to use it

It's pretty simple really, it's a string extension so you just put the code into a file and make sure it's resolved. Then you just add .Slugify() onto a string.

    var title = "This is an url unfriendly title";
    var slug = title.Slugify();

    // if we were to output slug we would get

    this-is-an-unfriendly-title

Slugify also removes any non alphanumerical characters, allowing only dashes to persist. Any other characters will be converted to a dash. Any repeated dashes will be trimmed down to a single dash.