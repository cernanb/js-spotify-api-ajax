# Visualizing A Song's Popularity Using Spotify

## Objectives

Build a page that uses data from the [Spotify's API Top Tracks](https://developer.spotify.com/web-api/get-artists-top-tracks/) to render a bar chart using [Chart.js](http://www.chartjs.org/). It will display the 10 most popular Elvis Presley songs and will have track names on the x-axis and popularity on the y-axis.

![example pic](https://raw.githubusercontent.com/learn-co-curriculum/js-spotify-api-ajax/cd/new_solution/img/example.png "Pic of Example")

## Instructions

You will need to make an AJAX call using the Artist Top Tracks URL describe here [Spotify's API Top Tracks](https://developer.spotify.com/web-api/get-artists-top-tracks/)

Take a look at the `spec/spotify-chart.spec.js` file to get started. This lab isn't fully tested so while every spec may pass, you might not have a functioning product. You will only be modifying the `js/spotify-chart.js` to pass the first six tests.

The final step of this lab will be to run your server with `ruby -run -e httpd . -p 8000` and opening up [localhost:8000](http://localhost:8000/). Verify that your chart looks similar to the chart in this readme, then open `spec/spotify-chart.spec.js` and set the variable `signature` equal to your first and last names, in a string. That should make the final test pass.

**Note:** We've intentionally left out notes on using Chart.js. Be sure to [read the docs](http://www.chartjs.org/docs/) and exercise some google-foo if you run into something challenging.

## Resources

* [Spotify's API Top Tracks](https://developer.spotify.com/web-api/get-artists-top-tracks/)
* [jQuery](http://api.jquery.com/) - [AJAX](http://api.jquery.com/jquery.ajax/)
* [Chart.js](http://www.chartjs.org/docs/#getting-started) - [Bar Chart](http://www.chartjs.org/docs/#bar-chart-example-usage)
