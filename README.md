# Bellamar Villas website
Static site (index.html + assets/). Bookings go to Booking.com and Agoda.
Publish with GitHub Pages: Settings > Pages > Deploy from a branch > main / (root).

## Showing prices
In index.html find `var RATES={booking:null,agoda:null};` and set each platform's nightly rate in PHP, e.g. `{booking:3500,agoda:3350}`. The results page then shows totals and marks the lower price.
