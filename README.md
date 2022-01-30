# Last Mile Connectivity! 

**By: Oscar Baumann, Poornima Badrinath**

### Understanding the importance of precise navigation until the doorstep! 

Ever been really hungry, ordered food and wondered where the food delivery person got lost while picking up your food? Ever been dropped off at a wrong location and having to walk down all the way to the actual location, being thoroughly confused as to where it is? Ever had any parcel delayed because the address or the entrance of the building is not clear? Ever had to find an alternative route because the route suggested was not accessible? 

Then you understand the importance of last mile connectivity! 

Last mile connectivity is a concept exploring the need of minute and precise directions from the point you start to the point you want to reach. To have last mile connectivity means that the route suggested will include:  

- All modes of transport in the route 🚶‍♀️🚗🚆⛴
- Different profiles that include all levels of accessibility - walking paths, wheelchairs, ramps, escalators etc.
- Shows where the parking locations are for your cars 
- Lets you understand indoor navigation in big places like malls! 
- Safety necessities like lit streets at night! 


Our mapping project is aiming to understand the importance of the concept of last mile connectivity, the modes and different protocals needed for accurate navigation and how impactful it is have really good directions until the end point. We are comparing the datasets between three cities: 
- Munich, our current location
- Vienna, the city Oscar is from! 
- Bengaluru, the city which is Poorni's home! 

Selection of the cities are based on the knowledge of the places and where the missing data is and how much it can affect in routing when things are not correctly mapped! 

## About the project 

![image](https://user-images.githubusercontent.com/17887418/151412338-64e475c9-d078-4a23-a686-24b10cb610ae.png)
_The overall interface_ 


![image](https://user-images.githubusercontent.com/17887418/151412457-10755829-6379-4524-8629-d7cf7a4cf3e5.png)
_Available wheelchair data shown as purple dots and available steps and ramps data as orange lines_


![image](https://user-images.githubusercontent.com/17887418/151412599-f036ea94-7db1-46c3-92b7-b58a0ebbdb39.png)
_Comparitive routes between OpenStreetMap Api (editable route - green colour and the Mapbox Navigation API - blue colour (the non changable route)_


![image](https://user-images.githubusercontent.com/17887418/151412691-62de3bba-b71c-4d2d-894e-088bc5fda8e7.png)
_Comparitive routes shown with available accessibility data!_

![image](https://user-images.githubusercontent.com/17887418/151412794-2e62b340-3712-44c6-8bf6-2c230f88e6a2.png)
_Night map with all the lit vs non lit streets!_ 

![image](https://user-images.githubusercontent.com/17887418/151412934-2aa5ee69-23d4-4aee-814e-28eea5ddbe9d.png)
_Directions including the lit streets into consideration when suggesting navigation!_ 


## Impact 

- The routing API uses the Mapbox directions API on one end, which is the blue route that has four profiles currently. The other route (the green route) uses the OpenStreetMap routing API, which is updated faster and easier owing to millions of worldwide contributors that add the missing data. When you fill the gaps of missing accessiblity data you can see the difference between the routes and how the direction changes to inlude the newer parameters into place. 

For eg: 


![ComparisonRoutes](https://user-images.githubusercontent.com/17887418/151718824-2fb3aa92-83d4-4220-81e6-b4e06db11374.png)

With Munich and Vienna, the difference is very clear when the routes are updated. The green route or the OSM route shows a clear direction completely from origin till the end point of the destination, where the blue route or the Mapbox API restricts itself till the point where the data is available. 

However with Bengaluru, both the routes are not clear because of missing datapoints of accessibility, causing a lot of confusion in how the routes are built. 

With around 10 routes - origin and destination combinations checked across Munich, Vienna, and Bengaluru each: 

- 9/10 routes were precise in Munich with OSM API 
- 7/10 routes were precise in Vienna 
- 2/10 routes were precise in Bengaluru (the reason being a lot of missing accessibility data that hasn't been updated on the map. 

### Impact percentage: 

- Munich - **90%**
- Vienna - **70%**
- Bengaluru - **20%**


### Next actions: 

We will continue to improvise this tool and make it as a mobile API if possible. The idea is to have a clickable profile for different modes of accessibility, easier access and safety protocols for users to choose from. Specifically for continous navigation places like indoor malls for food deliveries, underground parking garages and places with multiple entries and different buildings like the TUM campus. 


![image](https://user-images.githubusercontent.com/17887418/151719306-a40132f7-c61f-4668-9ffc-961578a802f0.png)

Our end goal would be to create a complete different mode for accessibility data as seen in the above image and add a safety mode for night travel that allows us to access street safety data and the timings for night public transport options, emergency services etc. 

![image](https://user-images.githubusercontent.com/17887418/151719362-2d0036c8-804d-4658-9e53-8c049ce82f6f.png)

![image](https://user-images.githubusercontent.com/17887418/151719372-7420b065-b1b3-474a-bfd6-7554ad497b62.png)

### References: (Links to be updated)  

- Mapbox GL JS 
- Mapbox map matching API.
- Wheelchair mode activated google 
- OpenStreetMap
- Mapbox Studio
- Last mile connectivity 


Accessbility page link: https://poornibadrinath.github.io/accessibility/
