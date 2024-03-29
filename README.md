# Puerto Rico

This is my final project for Puerto Rico

## ADMINISTRATIVE SUBDIVISIONS
![](Rplot07.png)
### Puerto Rico is an island and U.S. territory located in the Caribbean Sea in Central America. The political subdivisions of Puerto Rico consist of international borders and 78 different municipalities. Each municipality elects a mayor and legislature to govern and control day to day life in the municipality. I selected the municipality of Caguas, Puerto Rico for my project. Caguas is located on the eastern side of Puerto Rico and shares its northern border with the municipality of San Juan. Caguas also shares its border with the municipalities of Aguas Buenas, Cidra, and Cayey to the west, and San Lorenzo, Gurabo, and Trujillo Alto to the east. 
![](Caguas_Zoom.pdf)

## POPULATION OF MUNICIPALITIES
### The population of Puerto Rico is three million and is greatly affected by the topography. Puerto Rico is very mountainous in its southern and central regions, resulting in the most populous areas to be located towards the north. 

![](puert_map_contour.png.pdf)

### Of Puerto Rico's municipalities, San Juan is the most populated. This is expected because San Juan, the capital of Puerto Rico is located in the municipality. San Juan is by far the most densely populated municipality in Puerto Rico, with Bayamón, the second most dense municipality, a little more than half as densely populated.
![](puert_pop19.png)
#### These plots exemplify the population density of each of the municipalities.
![](puert_bplt.png)

### Puerto Rico's population mostly lives in towns and villages across rural areas. A dense population lives in large cities like San Juan and Caguas, but the population is smaller compared to the Puerto Ricans living in smaller towns. 

#### I used data taken from satellite images to determine the different population densities of Puerto Rico
![](Rplot.pdf)
#### I also used the satellite data to determine the correspondence between night time lights (ntl) and the population in Puerto Rico
![](puert_pop19_graph.png)
### The follow plots are my population plots using my mean data of Puerto Rico. These were my most accurate plots. I was able to tell which of my models was the most accurate due to the magnitude of error of each one. My model produced by my mean data had the smallest magnitude of error with 4458076. My model produced by my logpop data was the second most accurate with 4458910, and my sum data was the least accurate with 33632241. I had trouble with my data initially because I was getting the same return for all of my data sets. I switched commands from `bind_cols` to `merge` which allowed me to differentiate my data. 
![](Rplot02.png)
![](pop_sum.png)
![](diff_mean3d.png)

## HUMAN SETTLEMENTS, ROADWAYS, AND HEALTHCARE FACILITIES 
### Caguas’ topography consists of mountainous regions, which determine the location of facilities in the municipality. The development of urban populations has been impacted by the topography because the larger populated area in the south is built up of smaller communities and not as connected as the populated urban area in the north due to the challenge of building infrastructure in mountainous regions.

![](Proj3_p2.png)

### The roads and hospitals are located in less mountainous areas due to the difficulty of building infrastructure in uneven surfaces and higher elevation.Producing my three-dimensional map resulted in a better understanding of the population in Caguas, Puerto Rico. I was able to interpret the southern urban population as a large area yet not very dense due to the mountainous terrain in most of the region. The northern urban populations have a much smaller area yet they are much more dense due to the low elevation. Infrastructure is much more easily built in the northern areas of Caguas, making cities more abundant and population denser. 

![](CaguasProj4.png)

### The level of service in Caguas, Puerto Rico is, at best, decent. The southern population has a higher level of service because they are connected with roads that go towards the healthcare facilities. The northern population has a lower level of service in the municipality of Caguas due to the lack of roads and the mountains blocking them from the healthcare facilities; however, the population in the north tends not to use the healthcare facilities in the south, instead they use the facilities in the municipality of San Juan and Aguas Buenas. 


||Caguas, Puerto Rico|
|:----------:|:----:|
|Total Population|144,779|
|Urban Areas|6|
|Total Roadway Networks|9 Primary Roads|
|Total Health Care Facilities|7 Hospitals, 3 Clinics|
|Level of Service|Higher level of service in the south compared to the north|


### In conclusion, the human development in Puerto Rico ranges from densely populated cities, like San Juan and Caguas, to scarcely populated small towns in the rural regions. Due to the large impact of mountains, the majority of the population in Puerto Rico lives in small towns in rural areas. This observation is demonstrated in the municipality of Cagaus. Most of the population in Caguas lives in two main areas, one in the north and one in the south. The regions are separated by mountains that block roads and means of transportation. The southern population has a large area and is located in a more rural area. The northern population is much smaller and located in the urban city of Caguas. The population in the south is much greater than the population in the north.



