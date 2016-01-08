# ASP inside HTML (.ascx & .aspx) language support in Atom

Adds syntax highlighting (and maybe eventually snippets) to ASP files in Atom.

Originally forked from the [PHP Atom package](https://github.com/atom/language-php).

Contributions are greatly appreciated. Please fork this repository and open a
pull request to add snippets, make grammar tweaks, etc.

--------------

I just pulled this from PHP because the php highlighting worked well with `if` statements using curly braces, whereas the ASP languages I have looked into [don't tend to do that well](https://github.com/jbalboni/atom-language-aspx/issues/5).

I know NOTHING about language packages going into this, so you might find some strange leftovers from PHP in here...

As of now, it does the proper highlighting where `<% if (bool) { %> HTML <% } %>` is concerned. So that is a win.