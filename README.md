# Trakt Collection Remover

Remove movies from Trakt collection in batches with a countdown display

## Prerequisites

-   A Userscript extension installed into your browser _(this was tested using ViolentMonkey)_
    -   Chrome: [ViolentMonkey](https://chromewebstore.google.com/detail/violentmonkey/jinjaccalgkegednnccohejagnlnfdag?hl=en) or [TamperMonkey](https://chromewebstore.google.com/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo?hl=en)
    -   Firefox: [GreaseMonkey](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/)

## Process

-   Copy the code from the [script.js](/script.js) file and add it to your Userscript extension
-   Go to the trakt.tv collections page for movies
-   Click the _'Remove Movies from Collection'_ button
-   A popup window will appear for you to enter the number of movies to remove in this batch (_or all on page_)
-   Click _'OK'_ and the Script will begin removing items from your collection
-   You will see a countdown appear under the button showing the progress

![img2.png](/Documentation/img2.png)

![img1.png](/Documentation/img1.png)

## TODO:

-   [ ] Enhancement: Update to remove TV Shows _(may already work but is untested)_
-   [ ] Enhancement: Add functionality to progress to next page
-   [ ] Bug: Button disappears when going to next page, requires user to refresh page
-   [ ]
