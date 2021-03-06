### Hi there and welcome to my github page!

I’m currently learning the fundamentals of software development through projects that smooth small anoyances in daily life. 

I've got 2 personal projects on the go:
### UnBurnt
(Repositories: **UnBurnt-iOS-App**, **UnBurntArduino** **UnBurnt-Sensor-Client** and **UnBurnt-REST-API**)
- To prevent burnt BBQ food, sensors (thermocouple and flame) are attached to an arduino with wifi to send data via python API to mongoDB/ iOS app.  
- The iOS app receives push notifications when it's time to check the food, if it's too hot, on fire and when it's too cold.
- Uses state machine and background modes, so you never have to turn on or off system, it'll automatically turn on when reached min temp and off when cooled back down.
- Currently setting up supervised machine learning to determine burning point (from temp slope and temp), but am going to need much more data (and resolder my initial sensors).
- This project is spread among 3 repositories:
- The **UnBurnt-REST-API** repository contains the Flask-RESTful python API code. Docker scripts (to run python/ SQL on raspberry pi server), SQL schema setup and project UML diagram are also found here. 
- The **UnBurnt-Sensor-Client** repository contains the code that reads and processes the sensor information from the arduino and determines cooking state based on this information.  
- The other 2 repositories (**UnBurnt-Arduino** and **UnBurnt-iOS-App** are more self explainitory containing the sensor schematic and Aruduino code and iOS code respectively)   

### Papaoutai
(Repositories: **Papaoutai-REST-API**, **Papaoutai-iOS-App** and **Papaoutai-Arduino**)
- An iOS app that tracks the time that adults in the house spend (aka hides) in bathroom. 
- Uses BLE from an Arduino Nano to connect to iphone in background mode, and tracks time spent within a preset proximity. 
- On BLE disconnection, the iOS app sends time data to Posgresql via python api.  
- Day and Week usage is displayed along with week averages on a iPhone app (similar to the "screentime" app). Currently working on combining the proximity tracking and usage display apps into one.  
- Next steps after this is to use alerts to update user with weekly usage stats and including time percentage increase or decrease. 
 

![Your Repository's Stats](https://github-readme-stats.vercel.app/api?username=LilaKelland&show_icons=true)

![Your Repository's Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=LilaKelland&theme=blue-green)
