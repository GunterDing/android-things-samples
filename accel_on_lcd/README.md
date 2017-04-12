Example of using MMA7660 and Grove Jhd1313m1 LCD.

Build and install using Android Studio:
  click on the "Run" button.

If you prefer to run on the command line, from this repository's root directory, type:
  ./gradlew jhd1313m1:installDebug

To start the activity (if not started by Android Studio):
  adb shell am start com.example.upm.androidthings.driversamples/.Jhd1313m1Activity

Be sure that you have the Grove Jhd1313m1 LCD display and the Grove
MMA7660 accelerometer connected to your I2C bus.  If you have everything
set up correctly, This display will show the x/y/z accelerations (gravity)


License
-------
Copyright (c) 2017 Intel Corporation.

Licensed to the Apache Software Foundation (ASF) under one or more contributor license agreements. See the NOTICE file distributed with this work for additional information regarding copyright ownership. The ASF licenses this file to you under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
