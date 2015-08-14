## Where to begin?

- Think about a subject of your interest.
- Look into data. Learn about it.
- Does it need to be a map?
- Use some tool to manipulate, and visualize the spatial information.


## Tools

These tools/platforms allow you to use data spatially:

- [CartoDB](https://cartodb.com/)
- [MapBox](https://www.mapbox.com/)
- [QGIS](http://www.qgis.org/en/site/)

### Sample dataset

name | source | link
--- | source | ---
SF public school points* | SF gov | [link](http://apps.sfgov.org/datafiles/view.php?file=sfgis/schools_public_pt.zip)
SF private school points* | SF gov | [link](http://apps.sfgov.org/datafiles/view.php?file=sfgis/Schools_Private_Pt.zip)
Mobile Food Permit | SF OpenData | [link](https://data.sfgov.org/Economy-and-Community/Mobile-Food-Permit-Map/px6q-wjh5)
SF neighbornoods | CartoDB data library | search within CartoDB

* These datasets are sourced from the SF government. While you can find them via [SF OpenData](https://data.sfgov.org/), it seems that they are experiencing private connection issues. As a result, the data is download from the [ftp server](ttp://apps.sfgov.org/datafiles/index.php?dir=sfgis) directly.

### Create your own 

Try http://geojson.io/

## Where to go from here?

1. **Practice making simple maps.** You can follow [CartoDB tutorials](http://docs.cartodb.com/tutorials.html) that are tagged as basic. You will learn the interface of CartoDB, and hopefully understand some data concepts along the way.

2. **If you want to understand how datasets work together, learn SQL.** Check out CartoDB's medium/advanced tutorials. To get a solid grasp of SQL, Khan academy provides a great [intro course](https://www.khanacademy.org/computing/computer-programming/sql).

3. **If you want to get into map design/cartography, write more CartoCSS by hand.** Start with a map that you have made, and see how it can be visualized differently. (You can do so by adding more styles to the CartoCSS tab in CartoDB. [CartoCSS reference](https://github.com/mapbox/carto/blob/master/docs/latest.md)) 
  - If you are feeling adventurous, check out [MapBox Studio](https://www.mapbox.com/mapbox-studio/#darwin) for some serious styling.

## Readings

- https://www.mapbox.com/guides/how-web-maps-work/