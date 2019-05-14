# IOT-Home-Appliances
The code hosts a local server in the Arduino and a device connected to the same network will be able to access the webpage by using the IP of the Arduino (Ethernet Sheild)
The IP address of Arduino is identified by running the sample script "DHCPseverIP" found in the arduino IDE.
This address is replaced in the location of IP address in the provided code
Running the code will intitalize the web server in the arduino and the web page becaomes active.
The web page can be accessed in any device, allowing you to identify the appliances that are on/off and also controlling them.
The Home sever is connected to an IOT platform (AWS services), so that the appliances can be controlled reomotely from anywhere in the globe.
*Working on Encryption for local connection safety*
