# Temperature Controlled Fan System

# 1. Introduction
## 1.1 Context
&ensp;&ensp;&ensp;&ensp;&ensp;
This project aims to develop an intelligent system for monitoring the temperature and humidity in its vicinity, collecting information in real time form sensors, storing this information on a cloud platform, and 
finally displaying to the user through an Android mobile application the current state of the temperature and humidity, as well as the fan's status (ON/OFF).

&ensp;&ensp;&ensp;&ensp;&ensp;
For this project a Raspberry Pi board along with a DHT11 humidity sensor and a **insert fan name here** are used to centralize and distribute data. The information collected from the sensor and displayed to the user is the ambient 
temperature, the relative humidity of the air and the status of the fan.

&ensp;&ensp;&ensp;&ensp;&ensp;
In order for this data to remain saved and can be accessed from anywhere, the **AWS Cloud Management Platform** is used, which acts as an intermediary between the physical system and the mobile 
application. Thus, the user will be able to access current data about the relative humidity and temperature and will receive the status of the fan accordingly, which are all saved in the database.
