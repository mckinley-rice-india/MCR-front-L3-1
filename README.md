
# Mckinley & Rice Front End Coding Challenge

> Welcome to the Mckinley & Rice Coding Challenge!


## Overview

To complete this challenge, you will need to write a  web app, and provide us the source files to be built.


This challenge is expected to take about 2-4 hours.



Build an application that does the following things

1.  A call to action button that says "Search for artist"
2.  When user clicks on this link, page opens in an overlay without page refresh or redirection
3.  Overlay should have form which asks for artist name and limit(no of tracks to be fetched)
4.  When user clicks on submit validate that artist name is "jack" and limit is 4
5.  Use those parameters to construct the url [http://itunes.apple.com/search?term=jack&limit=4](http://itunes.apple.com/search?term=jack&limit=4)
6.  Make AJAX call to the url.
7.  On successful submission, overlay closes but page is not refreshed or redirected.
8.  Construct maximum of four tabs in the page (original page on which "search for artist" link was visible)
9.  Artist name will be visible on these tabs.
10.  On clicking the tab AJAX call will be made to url [http://itunes.apple.com/search?term=artistName&limit=1](http://itunes.apple.com/search?term=%20%20artistName&limit=1) where artistName is the name visible on that tab
11.  JSON returned should be shown to the user as view for that tab (The only difference from normal tab functionality is that data is not statically populated for tabs, instead it is fetched from the above mentioned ajax url)
12.  Use: {artistName, trackName, artworkUrl30} info to display in a tab for a given artist

**Note**

If you are using jQuery $.ajax() to fetch the records from iTunes, then specify the _datatype_ parameter as **jsonp** and set _crossdomain_ parameter to **true** so that you can make cross domain ajax requests.

**Screenshots**

The below given screen shots are only representative of the problem, you are required to make better and more beautiful pages.

The search button

![Screen 1](http://i.imgur.com/rkTQ4wN.png)

The form that takes an artist name and limit

![Screen 2](http://i.imgur.com/4SnRWj6.png)

The tabs showing details of the 4 entries fetched from iTunes

![Screen3](http://i.imgur.com/eKFZMrM.png)

**Resources**

1.  **jQuery**: [https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js](https://ajax.googleapis.com/ajax/libs/jquery/1.7.1/jquery.min.js)
2.  **jQuery-ui**: [https://ajax.googleapis.com/ajax/libs/jqueryui/1.8.17/jquery-ui.min.js](https://ajax.googleapis.com/ajax/libs/jqueryui/1.8.17/jquery-ui.min.js)
3.  **Bootstrap**: [http://netdna.bootstrapcdn.com/twitter-bootstrap/2.2.2/css/bootstrap-combined.min.css](http://netdna.bootstrapcdn.com/twitter-bootstrap/2.2.2/css/bootstrap-combined.min.css), [http://netdna.bootstrapcdn.com/twitter-bootstrap/2.2.2/js/bootstrap.min.js](http://netdna.bootstrapcdn.com/twitter-bootstrap/2.2.2/js/bootstrap.min.js)
4.  Other JavaScript libraries can be found here [http://cdnjs.com/](http://cdnjs.com/)

You can add images by uploading on [http://imgur.com](http://imgur.com) or other similar sites and linking in the html/css/js file. Similary, you can link to any external css or js resource using the link/script tag. You can also upload js files to [http://yourjavascript.com](http://yourjavascript.com) and link appropriately in the document.
