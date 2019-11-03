# Assignment#7 Mobile-First Design 
---a one page website including a map and a chart
<br>Click on the link to view the webpage:<br> https://joyce630.github.io/joyceassignment.github.io/assignment7_MobileFirst/index2.html

<br><b>Introduction</b>
<ol>
<li>I used a template on startbootstrap.com as a basic template for my website. It took a fairly long time to deconstruct the origin css and apply new style. A map and a bar chart were embedded. Data was fetched using getJson method. 
Something strange happened when viewing the site in Safari. 
Here is the screenshot:(The first image is the problematic one, the second is the correct version.)
        
![image](https://joyce630.github.io/joyceassignment.github.io/assignment7_MobileFirst/img/NavBarProblem.png)
![image](https://joyce630.github.io/joyceassignment.github.io/assignment7_MobileFirst/img/Correct.png)
The bug comes out when I scroll up to the top manually, but it won't happen when I go up to the top by clicking on "Home" on the navbar. Is it the rendering problem of the shrink effect in css?...

<li>Map: Besides the basic layer and markers, two more layers (street and satellite layers) were added to the map. And  because I want to show data in five cities, I applied a "choropleth map" to highlight specific provinces and users can simply click on the highlighted area to zoom in conveniently. The method to add these features were acquired from the leaflet website. But I didn't figure out how to control the automatically zoom in level of the "choropleth map": the map is not big enough after being zoomed in, so users stil need to do it manually.
<li>Bar Chart: The chart is roughly done. It only shows data of one city. The legend below was supposed to labeled by names of month. But when I used the name of month, the bars couldn't show orderly by month. It dosen't have a correct x axis scale. And as a result the toolip is shown as grouped. It would be much better if developed into a combined chart (bar and line with data of rainfall and temperature) with a dropdown filter (so that chart of different cities can be shown in one section).
</ol>



<br><b>Source data</b>
<li>Map-Destination information:https://airtable.com/invite/l?inviteId=invXuTgar6Wj3Eglp&inviteToken=13deb5959d2f530f0498b0ccb71a5e236200fa76c9f1f01086a5a0016355f3b5
<li>Map-Italy GeoJSON (I didn't use all geojson in the final web because it is too much and only the data of related provinces were kept): https://github.com/openpolis/geojson-italy/blob/master/geojson/limits_IT_provinces.geojson
<li>Bar chart: https://airtable.com/invite/l?inviteId=invjb7aCmr9H31NUl&inviteToken=984f5b442f174cb7f335423f336bc5721b3f540e073b999bf8c55ffc99b83556

        
