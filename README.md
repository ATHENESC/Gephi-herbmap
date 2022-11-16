# this is where I will be putting the preliminary files for the graphing in the netowrk until I clean th efiles up and sort them into more legible gorupings, I will also add the presets below for gephi 

FOR IPNI NETWORK:
1. load ipni node file first before adding any layouts into the node tab in gephi
2. add ipni edge file next so that the ID on the node and edge files map 
  - if you have multiple workspaces going this wont work unless it is in the first workspace as gephi does continuous ID numbers, first node in the gephi node column must show as 0 or edges wont be able to locate the nodes 
3. graph will show up as swaure of dots in the overview, this is fine for now 
4. chose layout 'Map of Countries' and have projection as 'Mercator' (default) with the centre otion unticked 
5. run layout 
6. go back to data laboratory and copy the data from the latitude and longitude columns to the lat/lng columns (lat/lng columns only appear after the map of countries layout has been run 
7. Go back to overview and now change the layout to 'Geo Layout' and change the projection to 'winkel triple'
8. change the latitude and longitutde option to select the lat/lng columns and keep the centre box checked 
9. run layout and the map of countries should line up with the node coordinates
10. change node colour to make network more clear 
11. et voila! you can filter out the null lat/lng in the queries tab 
