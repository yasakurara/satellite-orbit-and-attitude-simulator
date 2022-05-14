# satellite-orbit-and-attitude-simulator
This is my personal side project (hobby) to realize satellite orbit and attitude simulator.

I'm planning to implement the following features for now.
* Targeting low earth orbit (LEO) satellite such as cubesat and microsatellite for now but I want to support deep space environment in the future. 
* Propagate orbit element with any perturbations.
* Calculate satellite attitude dynamics with any disturbance.
* Simulate satellite sensor and actuator equipment such as gyro, compass, sun-sensor, star-sensor, magnetorquer, thruster and so on...
* Determin orbit and attitude information by using the above simulated sensor and try to control them with well-known control methods.
* Simulate two or more satellites and realize a guidance control to approach each other.
* Visualize satellite orbit and attitude informations.
* and so on...

Please feel free to contact me if you have any questions about this code implementation or if I can help you with consulting / developing satellite development :)

コードに関する質問や，人工衛星の開発で何かお手伝いできることがあれば，気軽にお問合せください！

# How to build
1. `mkdir build; cd build`
2. `cmake ..`
3. `cd src; make`
4. `./app`

# License
```
Copyright 2022 yasakura

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```