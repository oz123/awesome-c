# Contribution Guide #

First of all, thank for your contribution! I can't manage this whole thing
alone, and I welcome pull requests. To make sure that we're all on the same
page, here are some guidelines to follow for submitting pull requests for this
list.

## What would be great ##

Obviously, it's your choice what you want to contribute - or not
contribute. However, if you're looking for something that would help awesome-c,
check the current issues, especially those tagged with 'help wanted'. Pull
requests addressing these are particularly great!

Additionally, if you found (or wrote!) a useful C tool, library, or anything
else, please contribute it! Even if it falls short, we would be happy to help
you improve, possibly by contributing ourselves.

Lastly, if you notice that something is dead, or of poor quality, we would love
contributions that _remove_ anything like that. We can't maintain the entire
list without your help, and would appreciate more vigilant eyes and minds!

## The scope of this list ##

As per the name, ``awesome-c`` is about the C programming language.
Specifically, any of the following are in scope:

* Libraries and frameworks for C
* Tutorials, books or other reference material for or about C
* Tooling designed for use with C (even if it's not written in C)

The following are expressly _not_ in scope for this list:

* Scripting languages that can be embedded into C

The following _may_ be in scope, but not necessarily:

* Programs written in C, but not specifically for work in C

Avoiding scope creep is important, and such avoidance begins with you. If in
doubt, keep in mind Antoine de Saint-Exupéry's famous statement:

_''Perfection is attained not when there is nothing left to add, but when there
is nothing left to take away.''_

## How to contribute ##

Now for the mechanics of the process, and some do's and don't's.

### Ensure that code you link to is open-source ###

This is highly important - this list *only* contains open-source things!
If you are sending a pull request linking to code, ensure it is licensed under
an open-source license. This includes, but is not limited to:

- Anything on the [OSI license list][1]
- Creative Commons Zero

If you're not sure, better to ask first. If it's not on the list above
especially.

### Ensure that non-code you link to comes from non-evil sources ###

While there is no open-source requirement for non-code things, including
documentation, tutorials, learning resources, and so forth, it is essential that
it comes from sources which aren't evil. Things which are evil include, but are
not limited to:

* Amazon
* Anything behind a paywall
* Anything written by bigots

If in doubt, ask!

### Maintain a level of quality ###

While it isn't possible to curate everything on the list, and occasionally poor
things will slip through, it's essential that only good stuff ends up on this
list. To this end, use the following questions as a guide to whether something
is good:

1. Does it contain documentation, both reference and tutorial?
1. Does it have its own dedicated page (not just a repo)?
1. Is this something you would use, or have used in the past, and found it good?
1. Is it being regularly maintained? Are no issues rotting? Has it been updated in
   the last few months?
1. Does it have unit tests, CI, or any other code quality checks? Do they pass?
   Are they thorough?
1. If code, is this work under an SPDX license? If it isn't, is it something
   fairly similar to an SPDX license?

The more of these questions have 'yes' answers, the more likely it is that
whatever you're submitting is good.

### Indicate the license for anything you add clearly ###

Ensure that you label licenses correctly. ``awesome-c`` now uses [SPDX][2]
license labels, so please use those. If the license is weird or not on the list,
label it as clearly as possible. Also check if the license is in use
already - if it is, don't create another link to it. License links are named the
same way as the license itself: if you want to link to the ``GPL-3.0-or-later``
license, you format the link as 
 
    [``GPL-3.0-or-later``][GPL-3.0-or-later]

Sometimes, libraries or frameworks will contain documentation or code under
different licenses to the library itself (such as tests or examples). There is
no need to indicate their licenses in that case. However, if the program itself
is what is being put on the list, *obviously* its license matters.

### Maintain alphabetical order within sections ###

Pretty self-explanatory, really. Numbers are considered to be higher-ordered
than anything else, and otherwise, lex order.

### Give a clear commit message ###

The commit message should state clearly *what* you did (adding, removing,
clarifying, etc.), with *what* (usually by giving the name of the entry), in the
present continuous tense (i.e. 'adding' not 'added').

### Keep to the same style as other entries

This includes, but is not limited to:

* The order of entries is: name with link, description, license link
* Avoid starting descriptions with 'a', 'an' or 'the'
* License link text should be backtick-wrapped
* If something has a dedicated site, link to that in preference to a Github or
  other repo page

Read some of the other entries to see how to format any new ones.

[1]: https://opensource.org/licenses 
[2]: https://spdx.org/licenses/ 
