# Map That Shows the Cloest Distance Between Firehalls and Schools
![lab1.png](https://github.com/UBC-GEOB472-Spring2020/jl860130-web/blob/master/lab2.png)
link to the map: https://jl860130.github.io/jl860130-web/lab2.html

  In this particular map: Nearest Firehalls to Schools in Vancouver, the fire stations and schools in Vancouver are displayed. Schools have higher chance experiencing fire accidents due to 
1.	Higher population density (students and staff)
2.	Chemical substances in labs 
3.	Naughty students
  The staff in schools need to be highly aware of the issue, and they need to understand where the closest fire stations are located in order to efficiently minimize the harm and damage. To solve the problem, the users of this map can just click the school that they are staying at, and the nearest fire station will be highlighted. Meanwhile, the users can also search the locations of interest in the search-bar. For example, if the users also want to find out where the closest hospital is, he/she can search it to find out in the map. According to the reading The Geographic Information Science & Technology Body of Knowledge by 	Roth, R E, the search add/highlight a map feature of interest, and it can support searching over filtering for the goal of presentation and general users. It also could support the user to accomplish spatial search on their devices. This interface style would strengthen then interface flexibility, and would increase the accessibility for the users
  To create this map, I chose to use Mapbox GL JS. I thought Mapbox would be easier for me to edit the data and style. I found the geojson data of schools and firehalls from OpenData Vancouver, and used the Mapbox to edit the style. The Icons of firehalls is fire-station-11 and schools is school-15. In this case, the users would more easily understand what the points are indicating. The style of the map is dark Navigation. I feel like dark Navigation would be more visually appealing. For interactivity, I used turf to find the shortest distance between a firehall and a school, so the users can simply click a school icon to discover the closest fire station. 
	To improve my map, I think I can add an interactivity that would pop up the shortest route from a fire station to a school. I think this would make the map more interesting, and more visually appealing. 
	
