# Project Info

## 3D UAV Path Planning Using Aerially Obtained Point Clouds
_Abstract:_ With the growing use of unmanned aerial vehicles UAVs for commercial and military operations, path efficiency remains an utmost concern for battery and time preservation. This paper presents a method for three dimensional 3D path planning using point clouds obtained from the USGS 3DEP United States Geological Survey 3D Elevation Program dataset via Open Topography. The path itself is obtained using the A* algorithm, with additional modifications implemented to account for path smoothing, UAV size, and energy consumption. We also introduce a collision avoidance method using the precomputed data to account for unforeseen obstacles not rendered within the point cloud. The method presented is designed specifically for point clouds obtained via LiDAR Light Detection and Ranging scans from aircraft, where cavities may be present underneath the surface layer. Simulations and physical testing using way point transmission show the validity of this method.

## Software and Equipment Used

| Software/Equipment  | Reasoning |
| ------------- |:-------------:|
| OpenTopography      | Used to access all point cloud datasets for testing purposes. OpenTopography API was used to access datasets remotely.     |
| UTM      | Python library used to convert WGS84 encoded coordinates to latitude and longitude to send to the UAV.     |
| LASzip      | Used initially to unzip .laz files to .las and ASCII formats.      |
| Open3D | Python visualization library used due to its available functionality for point cloud operations. |
| ARDU Pilot | Used for communication from computer to UAV and for simulated UAV testing purposes. |
| Mission Planner | Simulation and transmission software that can control UAVs for realistic simulation testing. |
| MAVProxy | In-between software that allows for ARDU Pilot and Mission Planner to communicate and link over network IP addresses. |
| 2D LiDAR Scanner | Equipped to the UAV for collision detection and avoidance testing. |

### [Pseudocode](/pseudocode.md)
Contains pseudocode snippets from our paper detailing the algorithms used in our process.

### [Visualization](/visualization.md)
Contains images and diagrams to aid with understanding.

### [Demonstration](/demonstration.md)
Contains videos of demonstrations of our prcess.

### [GitHub Repository](https://github.com/alecstem/2022-REU-on-Smart-UAVs)
View source code at the repository.
