# Demonstrations/Results
## Demonstrations
This is where you can view working demos of collision avoidance and the conversions from point cloud to GPS way points simulated in ARDU Pilot.
## Collision Avoidance
### Test 1
<iframe src="https://drive.google.com/file/d/1RdUg42GmiNS8l3Ck_wcyI5Mx5zzRNY2s/preview" width="640" height="480" allow="autoplay"></iframe>

### Test 2
<iframe src="https://drive.google.com/file/d/1sfoY2eX5Lp4v28I3MlnGT8bDylM5qbCA/preview" width="640" height="480" allow="autoplay"></iframe>


## ARDU Pilot Sim
### Test 1
<iframe src="https://drive.google.com/file/d/1nB6YHuIBG1JUIb8S0pdyJ2tQRUmn8bJO/preview" width="640" height="480" allow="autoplay"></iframe>

### Test 2
<iframe src="https://drive.google.com/file/d/1CZaOXvLCOHJajtcwc29G7kSrq9gfctwq/preview" width="640" height="480" allow="autoplay"></iframe>

## Full Demo
<iframe src="https://drive.google.com/file/d/1gbyyFrzae3G8eiwp6Yu0xKAOm2JqUQO4/preview" width="640" height="480" allow="autoplay"></iframe>

## Results
This is where you can view the table stastictics we found through our various test. The computer and internet specifications are The computer specifications are an HP laptop with processor: 11th Gen Intel(R) Core(TM) i7-1165G7 @ 2.80GHz 2.70 GHz, ram: 32.0 GB (31.7 GB usable), system type: 64-bit operating system, x64-based processor, graphics card: Intel iRISxe. The internet being used measured by ”Measurement LAB” had a download speed of 178.1 Mbps and an upload speed of 250.1 Mbps. Each test was also ran with a buffer size of 3m and our adapted A* algorithem.

### Table 1
Seattle Testing : 137,479.904 square ft, without energy model and using euclidean distance. 
| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|18868.698655725657|0.014852046966552734|20.73953011772769|
| 10 Nodes(with beizer)(without added sqrt)|18974.036877065577|0.0058939456939697266|11.993227904476957|
| 26 Nodes(with beizer)(with added sqrt)|18589.648978346544|2.825700044631958|11.779816936559783|
| 10 Nodes(with beizer)(with added sqrt)|18665.466363066607|0.953603982925415|11.995236019134534|
| 26 Nodes(without beizer)(without added sqrt)|21426.678230381574|0.01177215576171875|44|
| 10 Nodes(without beizer)(without added sqrt)|20762.2366364086|0.017882347106933594|12|
| 26 Nodes(without beizer)(with added sqrt)|19192.242363853322|2.8640007972717285|12|
| 10 Nodes(without beizer)(with added sqrt)|19913.70849898475|0.9038188457489014|12|

### Table 2
New York Testing : 202,476.83 square ft, without energy model and using euclidean distance. 
| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)| | | |
| 10 Nodes(with beizer)(without added sqrt)| | | |
| 26 Nodes(with beizer)(with added sqrt)| | | |
| 10 Nodes(with beizer)(with added sqrt)| | | |
| 26 Nodes(without beizer)(without added sqrt)| | | |
| 10 Nodes(without beizer)(without added sqrt)| | | |
| 26 Nodes(without beizer)(with added sqrt)| | | |
| 10 Nodes(without beizer)(with added sqrt)| | | |

### Table 3
Auburn Testing : 780,464.475 square ft, without energy model and using euclidean distance. 
| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)| | | |
| 10 Nodes(with beizer)(without added sqrt)| | | |
| 26 Nodes(with beizer)(with added sqrt)| | | |
| 10 Nodes(with beizer)(with added sqrt)| | | |
| 26 Nodes(without beizer)(without added sqrt)| | | |
| 10 Nodes(without beizer)(without added sqrt)| | | |
| 26 Nodes(without beizer)(with added sqrt)| | | |
| 10 Nodes(without beizer)(with added sqrt)| | | |

### Table 4
Seattle Testing : 137,479.904 square ft, without energy model and using manhattan distance. 
| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)| | | |
| 10 Nodes(with beizer)(without added sqrt)| | | |
| 26 Nodes(with beizer)(with added sqrt)| | | |
| 10 Nodes(with beizer)(with added sqrt)| | | |
| 26 Nodes(without beizer)(without added sqrt)| | | |
| 10 Nodes(without beizer)(without added sqrt)| | | |
| 26 Nodes(without beizer)(with added sqrt)| | | |
| 10 Nodes(without beizer)(with added sqrt)| | | |

### Table 5
Seattle Testing : 137,479.904 square ft, with energy model and using euclidean distance. 
| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)| | | |
| 10 Nodes(with beizer)(without added sqrt)| | | |
| 26 Nodes(with beizer)(with added sqrt)| | | |
| 10 Nodes(with beizer)(with added sqrt)| | | |
| 26 Nodes(without beizer)(without added sqrt)| | | |
| 10 Nodes(without beizer)(without added sqrt)| | | |
| 26 Nodes(without beizer)(with added sqrt)| | | |
| 10 Nodes(without beizer)(with added sqrt)| | | |

### Table 6
New York Testing : 202,476.83 square ft, with energy model and using euclidean distance. 
| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)| | | |
| 10 Nodes(with beizer)(without added sqrt)| | | |
| 26 Nodes(with beizer)(with added sqrt)| | | |
| 10 Nodes(with beizer)(with added sqrt)| | | |
| 26 Nodes(without beizer)(without added sqrt)| | | |
| 10 Nodes(without beizer)(without added sqrt)| | | |
| 26 Nodes(without beizer)(with added sqrt)| | | |
| 10 Nodes(without beizer)(with added sqrt)| | | |

### Table 7
Auburn Testing : 780,464.475 square ft, with energy model and using euclidean distance. 
| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)| | | |
| 10 Nodes(with beizer)(without added sqrt)| | | |
| 26 Nodes(with beizer)(with added sqrt)| | | |
| 10 Nodes(with beizer)(with added sqrt)| | | |
| 26 Nodes(without beizer)(without added sqrt)| | | |
| 10 Nodes(without beizer)(without added sqrt)| | | |
| 26 Nodes(without beizer)(with added sqrt)| | | |
| 10 Nodes(without beizer)(with added sqrt)| | | |
