# WWD-Dataset
This repository contains Wrong Way Driving Dataset.

For vehicles driving on the **wrong side** of the road, we have following 5 folders:
- Back of Sign: We can see back of road sign in the image and the WWD vehicle is facing the back of sign.
- Double Solid Line: We can see double solid line in the image and the WWD vehicle is driving to the left of double solid line.
- Pavement Marker: We can see pavement markers like left only or right only sign on the road and the WWD vehicle is driving against the sign.
- Signal Light: We can see traffic light signals and the WWD vehicle is driving to the left of such signals.
- WWD Sign: We can see “Do Not Entry” or “Wrong Way” sign and the WWD vehicle is driving towards such signs.

Each of these folders contain: 
1) png images that show vehicle driving on the wrong side
2) an excel file that contains the thinking content for each image describing why is the vehicle on the image categorized as a wrong way driving vehicle
3) an xml file containing bounding box annotation for wrong way driving vehicle and different visual cues like back of sign, pavement marker, and so on.


For vehicles driving on the **correct side** of the road, we have following 3 sub-folders under the folder Right-Figure:
- Front of Sign: We can see the front of road sign in the image and the RWD vehicle is traveling towards the front of sign.
- Pavement Marker: We can see pavement markers like left only or right only sign on the road and the RWD vehicle is driving towards the sign.
- Signal Light: We can see traffic light signals and the RWD vehicle is driving directly below of such signals.

Each of these sub-folders contain: 
1) png images that show vehicle driving on the correct side of the road
2) an excel file that contains the thinking content for each image describing why is the vehicle on the image categorized as a right way driving vehicle
3) an xml file containing bounding box annotation for right way driving vehicle and different visual cues like front of sign, pavement marker, and so on.
