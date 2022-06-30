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
### Test 1
<iframe src="https://drive.google.com/file/d/1gbyyFrzae3G8eiwp6Yu0xKAOm2JqUQO4/preview" width="640" height="480" allow="autoplay"></iframe>

### Test 2

## Results
This is where you can view the table stastictics we found through our various test. The computer and internet specifications are The computer specifications are an HP laptop with processor: 11th Gen Intel(R) Core(TM) i7-1165G7 @ 2.80GHz 2.70 GHz, ram: 32.0 GB (31.7 GB usable), system type: 64-bit operating system, x64-based processor, graphics card: Intel iRISxe. The internet being used measured by ”Measurement LAB” had a download speed of 178.1 Mbps and an upload speed of 250.1 Mbps. Each test was also ran with a buffer size of 3m and our adapted A* algorithem.

### Table 1
Seattle Testing : 137,479.904 square ft, without energy model and using euclidean distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|18868.6986|0.0148|20.7395|
| 10 Nodes(with beizer)(without added sqrt)|18974.0368|**0.0058**|11.9932|
| 26 Nodes(with beizer)(with added sqrt)|**18589.6489**|2.8257|**11.7798**|
| 10 Nodes(with beizer)(with added sqrt)|18665.4663|0.9536|11.9952|
| 26 Nodes(without beizer)(without added sqrt)|21426.6782|0.0117|44|
| 10 Nodes(without beizer)(without added sqrt)|20762.2366|0.0178|12|
| 26 Nodes(without beizer)(with added sqrt)|19192.2423|2.8640|12|
| 10 Nodes(without beizer)(with added sqrt)|19913.7084|0.9038|12|

### Table 2
New York Testing : 202,476.83 square ft, without energy model and using euclidean distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|28135.3111|0.0602|87.1705|
| 10 Nodes(with beizer)(without added sqrt)|30308.2202|**0.0269**|100.8687|
| 26 Nodes(with beizer)(with added sqrt)|**25340.0258**|50.3640|**46.9998**|
| 10 Nodes(with beizer)(with added sqrt)|26282.4647|11.1670|46.9999|
| 26 Nodes(without beizer)(without added sqrt)|43521.8591|0.0576|219|
| 10 Nodes(without beizer)(without added sqrt)|46636.2481|0.0320|155|
| 26 Nodes(without beizer)(with added sqrt)|27195.7931|49.7136|47|
| 10 Nodes(without beizer)(with added sqrt)|30161.0173|11.1216|47|

### Table 3
Auburn Testing : 780,464.475 square ft, without energy model and using euclidean distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|46788.3796|**0.0169**|62.7928|
| 10 Nodes(with beizer)(without added sqrt)|49365.1028|0.0170|60.0000|
| 26 Nodes(with beizer)(with added sqrt)|44257.8885|114.5613|24.0000|
| 10 Nodes(with beizer)(with added sqrt)|**44231.8579**|34.8406|24.0000|
| 26 Nodes(without beizer)(without added sqrt)|51737.4913|0.0373|82|
| 10 Nodes(without beizer)(without added sqrt)|53365.8946|0.0329|60|
| 26 Nodes(without beizer)(with added sqrt)|47055.4989|130.7948|**24**|
| 10 Nodes(without beizer)(with added sqrt)|48624.4732|31.2758|**24**|

### Table 4
Seattle Testing : 137,479.904 square ft, without energy model and using manhattan distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|20609.0402|**0.0083**|27.6407|
| 10 Nodes(with beizer)(without added sqrt)|25170.8901|0.0479|73.4498|
| 26 Nodes(with beizer)(with added sqrt)|**20534.2060**|0.0821|24.7677|
| 10 Nodes(with beizer)(with added sqrt)|20722.7548|0.0212|**21.3907**|
| 26 Nodes(without beizer)(without added sqrt)|23904.7992|0.0092|50|
| 10 Nodes(without beizer)(without added sqrt)|33313.7084|0.0466|98|
| 26 Nodes(without beizer)(with added sqrt)|21963.2565|0.0859|28|
| 10 Nodes(without beizer)(with added sqrt)|23065.1803|0.0231|22|

### Table 5
Seattle Testing : 137,479.904 square ft, with energy model and using euclidean distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|**19631.7792**|**0.9207**|10.0000|
| 10 Nodes(with beizer)(without added sqrt)|20235.2898|13.1873|10.0000|
| 26 Nodes(with beizer)(with added sqrt)|19644.8975|54.8695|10.0000|
| 10 Nodes(with beizer)(with added sqrt)|20242.1704|14.5067|10.0000|
| 26 Nodes(without beizer)(without added sqrt)|20245.7593|1.0315|**10**|
| 10 Nodes(without beizer)(without added sqrt)|20927.9220|14.2147|**10**|
| 26 Nodes(without beizer)(with added sqrt)|20245.7593|55.7438|**10**|
| 10 Nodes(without beizer)(with added sqrt)|20927.9220|14.1579|**10**|

### Table 6
New York Testing : 202,476.83 square ft, with energy model and using euclidean distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|**26378.0447**|57.2290|43.0000|
| 10 Nodes(with beizer)(without added sqrt)|29202.0732|66.5170|43.0000|
| 26 Nodes(with beizer)(with added sqrt)|26563.8851|247.6823|43.0000|
| 10 Nodes(with beizer)(with added sqrt)|29017.7867|71.9563|43.0000|
| 26 Nodes(without beizer)(without added sqrt)|28146.0992|**52.4574**|**43**|
| 10 Nodes(without beizer)(without added sqrt)|30643.8600|68.3621|**43**|
| 26 Nodes(without beizer)(with added sqrt)|28146.0992|247.1492|**43**|
| 10 Nodes(without beizer)(with added sqrt)|30643.8600|61.6462|**43**|

### Table 7
Auburn Testing : 780,464.475 square ft, with energy model and using euclidean distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|46801.7540|66.8562|32.0000|
| 10 Nodes(with beizer)(without added sqrt)|49611.0153|80.4660|16.0000|
| 26 Nodes(with beizer)(with added sqrt)|**46676.1338**|352.5643|32.0000|
| 10 Nodes(with beizer)(with added sqrt)|49653.3454|69.5505|16.0000|
| 26 Nodes(without beizer)(without added sqrt)|49479.0101|**63.8973**|32|
| 10 Nodes(without beizer)(without added sqrt)|52670.5627|81.1400|**16**|
| 26 Nodes(without beizer)(with added sqrt)|49479.0101|351.2700|32|
| 10 Nodes(without beizer)(with added sqrt)|52670.5627|73.3211|**16**|
