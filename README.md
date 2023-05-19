# Markdown
Forked library to parse Markdown in Luau.

I haven't bothered looking into cleaning it up. Instead of returning raw text,
provides a array of Nodes which can be used to easily iterate upon and create
Instances. Types are being used to make it easier to iterate through it.

I haven't bothered figuring out all the hidden bells and nickels this can do,
but it should be able to at least parse basic markdown without links.