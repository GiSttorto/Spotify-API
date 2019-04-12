# Spotify-API

<h2>Overview</h2>
An interface that allows users to search their favorite artists and albums. Here we could not use AJAX directly as now Spotify requires authentication to make a request. So here I used an URL that I passed to it all of the query strings parameters as an usual request. This URL will make a request to the Spotify search API with the parameters I specify and send back the exact JSON that Spotify responds with. Clicking any search result will redirect the user to the related artist/album's Spotify page.


<h2>Features</h2>
A message will display if there are no results for a search.
A default image will display for results that do not have any images.
Infinite scroll is possible only when the string "scroll=infinite" appears in the query string when the page loads. Infinite scroll allows the user to scroll down to the bottom of the listed results and the next page of results will automatically be loaded and appended to the latest results. As part of this functionality, the 'More' button disappears.

<h2>Technology</h2>
jQuery & AJAX



<h2>Preview</h2>
