# UBES Greenland website

This repository stores the source code for the website of the University of Bristol’s 2020 expedition to Greenland. The website can be found at [`greenland.ubes.co.uk`](https://greenland.ubes.co.uk).

## Git

The source code is managed using the Git version control system. This uses *commits* to store versions of the whole website. Whenever you make changes and are ready to save them on the website, create a commit, and then *push* it. A brief tutorial is available [here](https://rogerdudler.github.io/git-guide/). If you want to perform larger changes, create a branch, commit whenever you make part of the change, and then *merge* the final commit back into the `master` branch.

## GitHub Pages

This website is hosted using [GitHub Pages](https://pages.github.com/). This is static, meaning that the server doesn’t do any processing when you request a webpage. By default, there is no templating set up, which means that any headers and footers have to be repeated on every page. If there is only one page, then this is fine, but otherwise it would be worth using [Jekyll](https://jekyllrb.com/docs/) to provide the layout.
