Weather
========

![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/device-2016-11-29-193842.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/device-2016-11-29-194050.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/device-2016-11-29-194120.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/device-2016-11-29-194229.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/device-2016-11-29-194243.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/final_bstSnapshot_32292.png)

Sample application for Android concepts:
- List view
- Detail view
- Fetch data from an API
- Google design concepts
- Database storage (SQLite)
- Content Providers
- Loaders
- Services and Notifications
 
Weather is the companion Android app for the Udacity course [Developing Android Apps: Android Fundamentals](https://www.udacity.com/course/ud853).
This app is based on [here](https://github.com/udacity/Sunshine).




### Open Weather Map API Key is required.

In order for the app to function properly as of October 18th, 2015 an API key for openweathermap.org must be included with the build.

It's recommended to obtain a key via the following [instructions](http://openweathermap.org/appid#use), and include the unique key for the build by adding the following line to [USER_HOME]/app/build.gradle

```
buildTypes.each {
        it.buildConfigField 'String', 'OPEN_WEATHER_MAP_API_KEY', '"UNIQUE_API_KEY"'
    }
```


