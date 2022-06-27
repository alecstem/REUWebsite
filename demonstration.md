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
| 26 Nodes(with beizer)(without added sqrt)|28135.31118257428|0.06022977828979492|87.17051904697485|
| 10 Nodes(with beizer)(without added sqrt)|30308.22020291801|0.02690577507019043|100.8687685813384|
| 26 Nodes(with beizer)(with added sqrt)|25340.02580527548|50.36409831047058|46.99989661332926|
| 10 Nodes(with beizer)(with added sqrt)|26282.46478711936|11.167004346847534|46.999999721009054|
| 26 Nodes(without beizer)(without added sqrt)|43521.859112274265|0.05768775939941406|219|
| 10 Nodes(without beizer)(without added sqrt)|46636.2481734264|0.03206968307495117|155|
| 26 Nodes(without beizer)(with added sqrt)|27195.793150890087|49.7136812210083|47|
| 10 Nodes(without beizer)(with added sqrt)|30161.017305526642|11.121684551239014|47|

### Table 3
Auburn Testing : 780,464.475 square ft, without energy model and using euclidean distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|46788.379610688215|0.016933679580688477|62.7928246659058|
| 10 Nodes(with beizer)(without added sqrt)|49365.102807652926|0.01703810691833496|60.00000000104088|
| 26 Nodes(with beizer)(with added sqrt)|44257.88851205062|114.56138706207275|24.00000000018884|
| 10 Nodes(with beizer)(with added sqrt)|44231.85790133184|34.840612173080444|24.000000000164167|
| 26 Nodes(without beizer)(without added sqrt)|51737.491399905644|0.03738260269165039|82|
| 10 Nodes(without beizer)(without added sqrt)|53365.8946290544|0.03297543525695801|60|
| 26 Nodes(without beizer)(with added sqrt)|47055.49893676754|130.79488945007324|24|
| 10 Nodes(without beizer)(with added sqrt)|48624.47327281727|31.27583122253418|24|

### Table 4
Seattle Testing : 137,479.904 square ft, without energy model and using manhattan distance. 

| Testing Style  | Distance(m) | Computational Time(s) | Elevation Change(m) |
| ------------- |-------------|------------- |:-------------:|
| 26 Nodes(with beizer)(without added sqrt)|20609.040201573272|0.008338212966918945|27.640724727329903|
| 10 Nodes(with beizer)(without added sqrt)|25170.890118871146|0.04794955253601074|73.44982528470416|
| 26 Nodes(with beizer)(with added sqrt)|20534.20600708232|0.08215522766113281|24.767798112255118|
| 10 Nodes(with beizer)(with added sqrt)|20722.75485884391|0.021234989166259766|21.390755608295773|
| 26 Nodes(without beizer)(without added sqrt)|23904.799220629026|0.009230375289916992|50|
| 10 Nodes(without beizer)(without added sqrt)|33313.708498984684|0.04663205146789551|98|
| 26 Nodes(without beizer)(with added sqrt)|21963.256572914215|0.08598971366882324|28|
| 10 Nodes(without beizer)(with added sqrt)|23065.180361560888|0.023107528686523438|22|

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
