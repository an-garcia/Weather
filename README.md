Weather
========

![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/Screenshot_1480565804.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/Screenshot_1480565868.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/Screenshot_1480616478.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/Screenshot_1480565881.png)
![alt tag](https://github.com/an-garcia/Weather/blob/master/readmeImages/Screenshot_1480565890.png)
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
- Widgets
 
Weather is the companion Android app for the Udacity course [Developing Android Apps: Android Fundamentals](https://www.udacity.com/course/ud853).
This app is based on [here](https://github.com/udacity/Sunshine)  [here](https://github.com/udacity/Advanced_Android_Development/).
Synchronizes weather information from OpenWeatherMap on Android Phones and Tablets.


Pre-requisites
--------------
- Android SDK 25 or Higher
- Build Tools version 21.1.2
- Android Support AppCompat 25.0.1
- Android Support Annotations 25.0.1
- Android Support GridLayout 25.0.1
- Android Support CardView 25.0.1
- Android Support Design 25.0.1
- Android Support RecyclerView 25.0.1
- Google Play Services GCM 10.0.1
- BumpTech Glide 3.7.0

### Open Weather Map API Key is required.

In order for the app to function properly as of October 18th, 2015 an API key for openweathermap.org must be included with the build.

It's recommended to obtain a key via the following [instructions](http://openweathermap.org/appid#use), and include the unique key for the build by adding the following line to [USER_HOME]/app/build.gradle

```
buildTypes.each {
        it.buildConfigField 'String', 'OPEN_WEATHER_MAP_API_KEY', '"UNIQUE_API_KEY"'
    }
```


