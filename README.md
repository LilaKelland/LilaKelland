### Hi there and welcome to my github page!

I’m currently interested in learning all the things. 

I've got 3 personal projects on the go since the pandemic start:
### UnBurnt
- To prevent burnt BBQ food, I've attached sensors (thermocouple and flame) to an arduino with wifi to send data via python API to mongoDB/ iOS app.  
- The iOS app will recieve push notifications when its time to check the food, if its too hot and when it's too cold.
- Uses state machine and background modes, so you never have to turn on or off system, it'll automatically turn on when reached min temp and off when cooled back down.
- Currently setting up supervised machine learning to determine burning point (from temp slope and temp), but am going to need much more data (and a BBQ and resoldered sensors (will revisit when back in Ottawa)
- This project is spread among 3 repositories:
- The UnBurnt repository contains the server/ API code in python. The docker scripts (to run python/ mongoDB on raspberry pi server), mongoDB schema setup and project UML diagram are also found here. 
- The other 2 repositories (UnBurntArduino and UnBurntXcode are more self explainitory containing the sensor schematic and Aruduino code and iOS code respectively)  
### Papaoutai
- An iOS app that tracks the time a partner spends (aka hides) in bathroom.  
- Uses BLE from an Arduino Nano to connect to iphone in background mode, and track time within a preset proximity. 
- On BLE disconnection, the iOS app sends time data to mongoDB via Node.js/ Express framework.  
- Currently working on figuring out how to get mongoCharts onto the iphone to display usage stats.  
- Next steps after that is to use alerts to update phone with usage stats. 

### Website [codeinterupted.com](http://www.codeinterupted.com)
- Thought I should learn some frontend code and Angular/ Typescript looked intriguing.
- It's currently masquerading as a website from the '90s.
 
