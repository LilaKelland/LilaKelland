### Hi there and welcome to my github page!

I’m currently learning the fundamentals of software development through projects that smooth small anoyances in daily life. 

I've got 2 personal projects on the go:
### UnBurnt
(Repositories: **UnBurnt-iOS-App**, **UnBurntArduino** and **UnBurnt-REST-API**)
- To prevent burnt BBQ food, sensors (thermocouple and flame) are attached to an arduino with wifi to send data via python API to mongoDB/ iOS app.  
- The iOS app receives push notifications when it's time to check the food, if it's too hot, on fire and when it's too cold.
- Uses state machine and background modes, so you never have to turn on or off system, it'll automatically turn on when reached min temp and off when cooled back down.
- Currently setting up supervised machine learning to determine burning point (from temp slope and temp), but am going to need much more data (and access to a BBQ and resoldered sensors (will revisit when back in Ottawa)).
- This project is spread among 3 repositories:
- The **UnBurnt-REST-API** repository contains the API code in python. Docker scripts (to run python/ mongoDB on raspberry pi server), mongoDB schema setup and project UML diagram are also found here. 
- The other 2 repositories (**UnBurnt-Arduino** and **UnBurnt-iOS-App** are more self explainitory containing the sensor schematic and Aruduino code and iOS code respectively)  
- A testless spaghetti mess of code - next steps refactor/restructure, now that I've learned some things. 

### Papaoutai
(Repositories: (**Papaoutai-REST-API**, **Papaoutai-iOS-App** and **Papaoutai-Arduino**)
- An iOS app that tracks the time that adults in the house spend (aka hides) in bathroom. 
- Uses BLE from an Arduino Nano to connect to iphone in background mode, and tracks time spent within a preset proximity. 
- On BLE disconnection, the iOS app sends time data to Posgresql via python api.  
- Day and Week usage is displayed along with week averages on a iphone app (similar to the "screentime" app). Currently working on combining the proximity tracking and usage display apps into one.  
- Next steps after this is to use alerts to update user with weekly usage stats and including time percentage increase or decrease. 

### Website [codeinterupted.com](http://www.codeinterupted.com)
- Figured I should learn some non-iOS frontend code and Angular/ Typescript looked intriguing.
- It's currently masquerading as a contentless website from the '90s.
- Not yet up and running.
 

![Your Repository's Stats](https://github-readme-stats.vercel.app/api?username=LilaKelland&show_icons=true)

![Your Repository's Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=LilaKelland&theme=blue-green)
