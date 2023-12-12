# DHVS + Tracker
 This repository contains an implementation of visual servoing designed for compatibility with diverse robot types. Moreover, the tracker package is implemented to track modules and bolts.

![agilus](https://github.com/aaflakiyan/HDVS/assets/48828461/d63e1d04-7f5c-4fc8-a9a7-5cfc2962b8d4)

 ## Installation 

1. Clone this repository to the `src` folder of your ros workspace. 
2. Unzip the visp_ros.zip file inside this repository to your src folder in your ros workspace. 
The zip file contains visp_ros and vision_visp ros nodes based on the VISP library [GitHub Pages](https://github.com/lagadic).
3. Catkin_make.

## Usage 
The package produces Cartesian velocity commands through three distinct topics, supporting various visual servoing methods, including:
IBVS: "IBVS/command"
PBVS: "PBVS/command"
DHVS: "DHVS/command"

The Model-Based Tracker package improves the setup by providing the 3D positions of tracked models (battery module and bolt).

![tracker](https://github.com/aaflakiyan/HDVS/assets/48828461/40b8e254-9400-4d3b-960a-8af46830da85)
