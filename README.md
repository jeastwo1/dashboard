Dashboard
=========

Copyright (c) 2014, Intel Corporation, Jaguar Land Rover

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License
[here](http://www.apache.org/licenses/LICENSE-2.0).

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

Name: Dashboard
Version: XW_TizenIVI3_0_01FEB_AGL_05MAR2015
Maintainer: Chris Lamberson <CLAMBERS@jaguarlandrover.com>
Mailing list: dev@lists.tizen.org

Build Instructions:
  * make apps - To build the wgt files for all release apps
  * make deploy - To build and copy the wgt files to the platform
  * make install.feb1 - To build and install wigits on the platform
  * make run.feb1 - To build, install and run on the platform

KnownIssues: 
  * Dashboard signals simulator plugin (randommizer)
  * Dashboard - Average consumption level is not changed when randomizer is active
  * When trying to switch between applications they hide and cannot be brought back into foreground
  * Not connected to a car

