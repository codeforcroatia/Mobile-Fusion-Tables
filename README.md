Mobile Fusion Tables
====================

This is a mobile-ready template using Google Maps and Fusion Tables, based on Derek Eder's [Fusion Table Searchable Map Template](https://github.com/derekeder/FusionTable-Map-Template).

Demos
-----

- US Health Centers: http://codeforsanfrancisco.org/Mobile-Fusion-Tables/demo-USHealthCenters.html
- SF Bank Locations: http://codeforsanfrancisco.org/Mobile-Fusion-Tables/demo-SFBanks.html
- SF Food Inspections: http://codeforsanfrancisco.org/Mobile-Fusion-Tables/demo-SFFoodInspections.html
- SF Liquefaction Data: http://codeforsanfrancisco.org/Mobile-Fusion-Tables/demo-SFLiquefaction.html
- SFCTA Projects: http://codeforsanfrancisco.org/Mobile-Fusion-Tables/demo-MyStreetSF.html


Setup
-----

**To use this template for your own Fusion Table data:**

1. Clone this repository.
2. Replace the FusionTable ID at the top of fusiontable_settings.js to point to your own table.

That's it.  You now have a working site that uses your own table's data, title, description, and infobox style, with a search field for each column.  Once you open the webpage on your device and hit "Add to Home Screen", you should have something that looks and feels like a mobile app.

If you want to make your app even sexier, explore the rest of the settings file to customize your content and behavior.  See the "samples" folder to see how the above demos were customized. 


Walkthrough
-----------

Here's what the main (map) page looks like.  You can customize the contents of the infobox using Handlebars.

![Map](http://sfbrigade.github.io/Mobile-Fusion-Tables/readme-images/map.png)

There are four buttons for navigating:
- **Search**: customizable search page for filtering and finding
- **List**: shows results in a customizable list view
- **Nearby**: takes you to your current location (you can opt-out of using current location in the settings file)
- **About**: fill this with your custom description and links

By default, the search page gives you a range slider for every number/date column in your table, and a text field for every string column (plus an address for centering your search).

![Default Search](http://sfbrigade.github.io/Mobile-Fusion-Tables/readme-images/search-default.png)

You can customize your search page with drop-downs, overrides, and other options:

![Custom Search](http://sfbrigade.github.io/Mobile-Fusion-Tables/readme-images/search-custom.png)

The address field uses geocomplete, which lets you auto-complete an address:

![Geocomplete](http://sfbrigade.github.io/Mobile-Fusion-Tables/readme-images/geocomplete.png)

The list view shows the data / search results by row (whose contents you can also customize). Clicking on a row will take you back to the map and highlight the pin with an infobox.

![List View](http://sfbrigade.github.io/Mobile-Fusion-Tables/readme-images/listview.png)


Get Involved
------------

If you have a customization that you'd like to share here, we'd be happy to add it to the "samples" folder.

Please raise any issues or suggestions for improvement.  Or if you think this is great as-is, you might as well star it.  :)
