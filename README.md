# Icara Spellbook

The Icara Spellbook is a mobile-friendly spellbook for Icara Homebrew content that organizes spell lists by class and level.

See the latest compiled build here: [https://grimoire.thebombzen.xyz/](https://grimoire.thebombzen.xyz/)

The Spellbook is forked from [thebombzen/grimoire](https://github.com/thebombzen/grimoire/), which contains the official 5e content. This content is NOT official content.

## Structure
Spells can be found inside `_posts/`. Each spell gets its own post, written and stored as a [Markdown](https://daringfireball.net/projects/markdown/basics) file. The date is arbitrary and never displayed, but still necessary for [Jekyll](https://jekyllrb.com) to process the posts properly.

If you'd like to help fill out the rest of the spells from the PHB or another source, for each new spell you make:

1. Make a new post inside `_posts/` for each new spell, and copy the formatting from another spell.
2. Submit a pull request for the spell(s) when you're finished, and that's it! Thank you so much. :)

## Build Instructions
I've edited _config.yml for my own build purposes, but if you've got [Jekyll](https://jekyllrb.com) set up locally, the following should create the build from your friendly command line terminal:
`jekyll serve -Vw --no-watch --baseurl ""`
