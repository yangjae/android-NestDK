# Android NestDK

Android sample code using the Nest Firebase APIs and Nest oauth implementation.  This sample code also includes an Android wrapper library that abstracts the redirect URL authentication flow and Firebase APIs to create native Java objects to represent Thermostats, Structures and Smoke/CO alarms. To get started you'll need a Nest developer account and register a client.  When registering the client be sure to select the redirect URL authentication flow and select any URL of your choice. Be sure to update the Constants.java file within the testapp module with the client id, client secret and redirect URL respectively.

## Building

The project can be imported through Android Studio or Intellij by selecting File > Import Project and selecting the build.gradle file within the NestSamples directory

## Running

After importing the application, select 'run' and select any Android emulator or device that is running API level 14 (Ice Cream Sandwich, Android 4.0) or greater.


## License
Copyright 2014 Nest Labs Inc. All Rights Reserved.
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at
http://www.apache.org/licenses/LICENSE-2.0
Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.