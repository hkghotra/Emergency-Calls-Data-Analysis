# Emergency Calls Data Analysis

## Data Overview
For this project I will be analyzing 911 emergency call data from Montgomery, PA. It has about 100,000 rows of data for dates between December 2015 to September 2016.
This dataset contains the following fields:

* lat : String variable, Latitude
* lng: String variable, Longitude
* desc: String variable, Description of the Emergency Call
* zip: String variable, Zipcode
* title: String variable, Title
* timeStamp: String variable, YYYY-MM-DD HH:MM:SS
* twp: String variable, Township
* addr: String variable, Address
* e: String variable, Dummy variable (always 1)

## Conclusions and Insights

* The following zip codes are hotspots for all types of emergency calls: 

|Zip|Count of Emergency Calls|
|-------|---------------------------|
| 19401 | 6979                      |
| 19464 | 6643                      |
| 19403 | 4854                      |
| 19446 | 4748                      |
| 19406 | 3164                      |


* The most common reason for an emergency call is EMS (49%), then Traffic (36%), and lastly Fire (15%). Under each reason, these descriptions account for the most number of calls:
  * EMS: Respiratory Emergency, Cardiac Emergency, Fall Victim
  * Fire: Fire Alarm, Vehicle Accident, Fire Investigation
  * Traffic: Vehicle Accident, Disabled Vehicle, Road Construction

* The most common emergency call description is a vehicle accident. They are most likely to occur during weekday afternoons in these areas:

|Zip|Count of Emergency Calls|
|-------|---------------------------|
| 19401 | 1218                      |
| 19446 | 1039                      |
| 19464 | 980                      |
| 19454 | 884                      |
| 19403 | 876                      |

* The number of emergency calls are highest during the month of January and July. In particular, traffic accidents are the highest in January due to winter weather conditions. Fire emergencies are the highest in July because of the dry and warm weather.
* The number of emergency calls decline in December due to the holiday season and work/school schedules.
* During weekdays emergency calls peak from 3:00 to 5:00pm. This could be due to a number of reasons such as school dismissal times, workday commutes, social activities after work. etc.
