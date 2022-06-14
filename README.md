# Mapping_Earthquakes

## Purpose

This project was created to display interactive earthquake data from the USGS website. The info presented is from using JavaScript Leaflet including map styles from Mapbox. The map display is a world map that highlights locations and magnitudes of Earthquakes that have taken place. The lines on the map are the tectonic plates that add another layer of info to the displayed map.  

## Results 

How to run the map-
Download the static folder and index.html file from the main branch of this repo. After getting an API key from Mapbox, create a file called "config.js" and place it inside of the js folder, which is found inside of the static folder. Use the template below for your config.js file. It is important to note, do not share an API key with anyone for security reasons relateable to your own project. Open a new terminal at the Earthquake_Challenge folder and run the following command to start a live server:

python -m http.server

This should produce the map in a web browser.
If not.. 
The command above will usually return “port 8000” , if it's a different port, no worries. Simply copy the address that is returned (Example: http://[::]:8000/ ) and paste into your browser. You should now see the map in your web browser. 

The screenshots below are of the final product of the map and the different color modes available taken from my produced web browser.

<img width="1377" alt="Screen Shot 2022-02-03 at 10 37 21 PM" src="https://user-images.githubusercontent.com/86068655/152468155-9191611c-be2f-43cb-a6ee-67367883f981.png">


<img width="1387" alt="Screen Shot 2022-02-03 at 10 37 11 PM" src="https://user-images.githubusercontent.com/86068655/152468019-2aea2a07-4b07-479a-b279-d808b77419d3.png">


<img width="1379" alt="Screen Shot 2022-02-03 at 10 37 25 PM" src="https://user-images.githubusercontent.com/86068655/152468053-adfe46be-bd81-45e4-b2b3-364b6bf25c79.png">

