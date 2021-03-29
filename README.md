### Hi there and welcome to my github page!

I’m currently learning the fundamentals of software development through projects to smooth small anoyances in daily life. 

I've got 2 personal projects on the go:
### UnBurnt
- To prevent burnt BBQ food, sensors (thermocouple and flame) are attached to an arduino with wifi to send data via python API to mongoDB/ iOS app.  
- The iOS app receives push notifications when it's time to check the food, if it's too hot, on fire and when it's too cold.
- Uses state machine and background modes, so you never have to turn on or off system, it'll automatically turn on when reached min temp and off when cooled back down.
- Currently setting up supervised machine learning to determine burning point (from temp slope and temp), but am going to need much more data (and access to a BBQ and resoldered sensors (will revisit when back in Ottawa)).
- This project is spread among 3 repositories:
- The **UnBurnt** repository contains the server/ API code in python. The docker scripts (to run python/ mongoDB on raspberry pi server), mongoDB schema setup and project UML diagram are also found here. 
- The other 2 repositories (**UnBurntArduino** and **UnBurntXcode** are more self explainitory containing the sensor schematic and Aruduino code and iOS code respectively)  
### Papaoutai
- An iOS app that tracks the time on of the adults in the house spends (aka hides) in bathroom. 
- Uses BLE from an Arduino Nano to connect to iphone in background mode, and track time within a preset proximity. 
- On BLE disconnection, the iOS app sends time data to mongoDB via ~~Node.js/ Express~~ python.  
- Currently working on figuring out how to get mongoCharts onto the iphone to display usage stats.  
- Next steps after that is to use alerts to update phone with usage stats. 

### Website [codeinterupted.com](http://www.codeinterupted.com)
- Thought I should learn some frontend code and Angular/ Typescript looked intriguing.
- It's currently masquerading as a contentless website from the '90s.
- Not yet up and running.
 
