# ASP inside HTML (.ascx & .aspx) language support in Atom

Adds syntax highlighting to ASP files in Atom.

Originally forked from the [PHP Atom package](https://github.com/atom/language-php).

> Thank you to all who have downloaded and found this package useful. It was made because of my own frustrations working on a bunch of legacy code, and a year later it's been downloaded over 1,500 times.

Contributions are greatly appreciated. Please fork this repository and open a
pull request to add snippets, make grammar tweaks, etc.

--------------

I just pulled this from PHP because the php highlighting worked well with `if` statements using curly braces, whereas the ASP languages I have looked into [don't tend to do that well](https://github.com/jbalboni/atom-language-aspx/issues/5).

I know NOTHING about language packages going into this, so you might find some strange leftovers from PHP in here...

As of now, it does the proper highlighting where `<% if (bool) { %> HTML <% } %>` is concerned. So that is a win.

--------------

# Change Log
## 0.3.0
* Supports comment tags. `<%-- COMMENT HERE --%>`. Works over multiple lines. It does still highlight certain bits of code inside comments, but it is still pretty readable. Again, I am claiming ignorance.
* Don't worry. It's still got tons of useless PHP holdovers included. And zero applicable tests. Woot!

## 0.2.0
* Supports `if` blocks properly. Or at least mostly.