Weather
========

![Scheme](/readmeImages/Screenshot_1480565804.png)
![Scheme](/readmeImages/Screenshot_1480565868.png)
![Scheme](/readmeImages/Screenshot_1480618685.png)
![Scheme](/readmeImages/Screenshot_1480565881.png)
![Scheme](/readmeImages/Screenshot_1480565890.png)
![Scheme](/readmeImages/final_bstSnapshot_32292.png)

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
This app is based on [Sunshine](https://github.com/udacity/Sunshine) and [Advanced_Android_Development](https://github.com/udacity/Advanced_Android_Development/).
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
Create a new resources file (using this path:/app/src/main/res/values/api_keys.xml) and put "OPEN_WEATHER_MAP_API_KEY" key value in it as string.

```
<?xml version="1.0" encoding="utf-8"?>
<resources>
    <string name="OPEN_WEATHER_MAP_API_KEY">exxxx26c4xxxxdcfd0xxxxb427xxxxe0</string>
</resources>
```

### Google Play Services

Note about google-services.json - To avoid seeing the error "GoogleService failed to initialize, status: 10" you should create a google-services.json file.
You can generate one [here](https://developers.google.com/mobile/add?platform=android)



License
-------
Copyright 2016 Angel Garcia

Licensed to the Apache Software Foundation (ASF) under one or more contributor
license agreements.  See the NOTICE file distributed with this work for
additional information regarding copyright ownership.  The ASF licenses this
file to you under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License.  You may obtain a copy of
the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.  See the
License for the specific language governing permissions and limitations under
the License.

