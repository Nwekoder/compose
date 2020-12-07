+++
title = "Search"
description = ""
weight = 8
+++

Compose implements `fuse.js` to enable search functionality. At the time of this writing, search on these theme takes either of this forms:

### 1. Passive search

This occurs only when the user loads the search page i.e `/search/`. They can directly navigate to that url. Alternatively, the user can type you search query on the search field and click enter. They will be redirected to the search page which will contain matched results if any.

### 2. Live search

This behaviour will be obvious as the user types a search query on the search field. All search queries, will yield a list of `quick links` or a simple `no matches found`. Else, the user will be prompted to continue typing.

> Please note that the results under quick links will be a truncated list of the most relevant results. Only a maximum of 8 items will be returned. This number is pragmatic at best if not arbitrary. On the search page, the number is set to 12.

Note that live search on the search page will behave differently than on the other pages. Nonetheles, the pages applies the same live search principle.

> Hitting enter while typing on the search page will be moot.

### Customize search feedback labels

Use the `i18n` files to do so.

<!-- ### scoped search
#### Searching within a specific/current page
I think the other 3 are not only related, but can be for the most part be achieved using the good old-fashioned CTRL/CMD + F.

(1) multilingual sites
(2) blog/events sections that are separate from the docs section -->