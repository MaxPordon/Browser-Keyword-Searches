# Browser Search Shortcuts
[Keyword searching](https://kb.mozillazine.org/Using_keyword_searches) made easy with importable out-of-the-box html-files.

The bookmark-importable html file features:
- an extensive list of recommended, obvious Keyword Searches, such as `y` for YouTube (with the first letter as keyword if possible). (Recommendations welcomed!)
- multi-parameter search terms for e.g. Google Maps navigation: `navi startpoint endpoint`


## What are Keyword Searches?
As explained in [this](https://kb.mozillazine.org/Using_keyword_searches) source:

> What makes keywords very powerful is that if you add a “%s” at some place in your bookmark’s URL, it will be replaced by the words you type in after the keyword. (These are sometimes called “Quicksearches”.) For example, if we were to modify the bookmark mentioned above so that it pointed to “http://google.com/?q=%s”, we can type “g mozilla” into the Location Bar to arrive at “http://google.com/search?q=mozilla”. 

## Reasoning
### Multiparameter keyword searches explained
The multiparameter keyword searches can accept both **comma**-separated and **space**-separated search parameters. Examples withthe included `navi` Keyword for navigation using Google Maps:
- `navi <starting point>, <end point>`: recognizes `<starting point>` as the first parameter i.e. the starting point, and `<end point>` as the endpoint
- `navi <startingpoint> <endpoint>`: recognizes `<startingpoint>` as the first parameter, and `<endpoint>` as the endpoint
### Navigate Google Maps
Apart from the `navi` keyword, also the following keywords exist for their respective transportation method:
- `naviw`: walking
- `navib`: bicycling
- `navip`: public transport
- `navic`: car
### Dictionary searches
Keywords follow format `<origin><target>`, e.g. English-French -> `ef`.
### for-dutch
Same as the base html, but includes Dutch dictionaries.

## Installation
### Importing in Firefox
1. Copy [the link to the html file from this repo](https://github.com/MaxPordon/browser-search-shortcuts/blob/main/_recommended-bookmarks.html)
2. Open Firefox
3. Press `Ctrl + Shift + O` to open bookmarks (or instead click the hamburger (top right) -> *Bookmarks* -> *Manage bookmarks*)
4. Press `Alt + I` to navigate to *Import and Backup*
5. Press `I` to select *Import Bookmarks from HTML...*
6. Press `Ctrl + V` and `Enter` to paste the link to the Recommended Keyword Searches html file from this repo and to Open it

### Importing in other browsers
Unfortunately, at least to the author's knowledge, currently other browser don't allow html-importation of keyword searches (or their equivalent). However, manual, one-by-one adding is possible in [Chrome (scroll down to "How to fill out text fields")](https://support.google.com/chrome/answer/95426?hl=en&co=GENIE.Platform%3DDesktop#zippy=%2Csearch-engine-field%2Cshortcut-field%2Curl-with-s-in-place-of-query-field).

## Tips
- When setting up a keyword for a(nother) website, remember than search filters, etc. are often saved in the URL. So set these filters to what you most often use, and _then_ set the keyword search, so that these filters are saved as well.
