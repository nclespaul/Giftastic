# Giftastic

- Author:  Darrell Freeman
- Date:
- Tools Used:  HTML, CSS, Javascript, JQuery, AJAX, Giphy API
- Website URL:  

This project uses AJAX to query an API using either pre-loaded or user determined search terms.  The search term is sent to the API when a button is clicked, and the response from the site is used to display 10 images having that search term as a parameter.  If the user clicks on one of the images, the still is replaced by an animated gif corresponding to that image.  

A situation that I ran into that I had not encountered was that of mixed content.  My site didn't function as intended because the API that was used for the query is not a secure site, and I was trying to pass that through the secure Github connection.  I resolved the problem by removing the "http" from the API address.  I don't know if this was the optimal path, but it did fix the problem with my site.
