# Prototype-files
This contains the prototype for AI Based Traffic System for Smart India Hackathon 2024.

Team Name : PixelPirates

About the SUMO simulation files :
1. The map.osm file contains a .osm file from OpenStreetMap India for a locality of Banglore.
2. The map.net.xml contains the netowrk file for the same map.osm file (Converted using netconvert command)
3. The map.rou.xml and map.trips.xml are random trips and routes generated from randomTrips.py (File given in SUMO repository)
4. The map.sumo.cfg file is the simulation file which can be fed to SUMO for the simulation.

About the Object Detection Model :
Used Vehicle_Detection.ipynb to detect vehicles and classify them based on their weights
Has integrated YOLOv8 model in it.

About sumo_run.py :
Used this file to extract CSV file including all the metadata of simulation.
