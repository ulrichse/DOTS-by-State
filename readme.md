# <span style= "color:steelblue">Map of </span> <span style= "color:orange">Male </span><span style= "color:steelblue"> and </span><span style= "color:purple"> Female </span> <span style="color:steelblue"> DOTS by U.S. State</span>💪

You can explore this map [here](index.html).

#### <span style= "color:indigo">Lab 04 Deliverable for GHY 5818</span>
Sarah Ulrich

<img src= "https://cdn.dmcl.biz/media/image/276774/o/Amanda.jpg" width=250/>

This side-by-side panel choropleth map shows the average Dynamic Object Team Rating System (DOTS) score among all male and female drug-tested raw lifters who competed in a sanctioned powerlifting competition between 2020 and 2023. Average male scores are shown on the right side panel and average female scores are shown on the left side panel. The DOTS coefficient was implemented in 2019 as a way to compare powerlifting performances across gender and weight class. DOTS are used in powerlifting meets to determing Best Lifter awards. A higher DOTS score indicates a greater strength per lb of bodyweight. Nonbinary or gender nonspecified (Mx) division competitors are not included in the data used for this map. 
 
#### <span style="color:indigo">Functions</span>

This webmap is structured using HTML. CSS is used within the <*style*> tags to structure the size, color, alignment, and other features of the text included in the map. JavaScript is used within the <*script*> tags to create and structure elements of my webmap, including the basemap and data in GeoJSON format. JavaScript is also used to add map interaction elements including a sliding display panel and formatting popups that appear over each state and display relevant information.  


## <span style="color:indigo">Data & Libraries</span>
The basemap used in this project came from the <a href="https://leafletjs.com/index.html"><span style="color:darkgreen">Leaflet</span></a> library. 
<a href="https://www.w3schools.com/cssref/index.php"><span style="color:teal">W3Schools</span></a> for css styling functions. 
Powerlifting data are from <a href="https://www.openpowerlifting.org/">OpenPowerlifting</a> a community service project to create a permanent, open archive of the world's powerlifting data. All data are available for use by the public. 
Side-by-side map panels are structured using <a href="https://github.com/digidem/leaflet-side-by-side"><span style="color:orange">leaflet-side-by-side</span></a>, a Leaflet control that adds a split screen to compare two map overlays.
