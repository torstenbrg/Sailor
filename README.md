# Sailing

A test app for defininng winds, boats and WayPoints

I would like to discuss a web application using Vanilla to a maximume extent.The visitor should be able to create a boat with a name as unique identifier. When a user visits he will be asked which boat he wants from a list of defined boats with an option to create a new boat. The data should be persisted in indexedDB . After having selected a boat the visitor will define his curreent position by clicking on a map and also the waypoint as BTW, bearing, and DTW, distance. Units to be used NM, kn, degrees, meter, hour, minute, second and date, the user should upload a csv-file with polar diagram for his boat which will be read (and saved) so that the current speed of the boat can be calculated with his current True Wind Angle, TWA, and true wind speed, TWS. Wind is an object having a time scale (eg every three hours) with data for TWS and True Wind Direction, TWD. The wind will be shown as arrow showing where the wind is coming from and the boat as another arrow pointing in SC. The app should calculate on which tack to start and when to change tack in order to reach the waypoint in shortest time.
