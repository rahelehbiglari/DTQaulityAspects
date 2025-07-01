# Purposes for creating DTs
Mainly taken from 
* [The PhD thesis from Randy Paredis](http://msdl.uantwerpen.be/people/rparedis/phd) 
* parts published in the publication [Modelling and Simulation-Based Evaluation of Twinning Architectures and Their Deployment](https://doi.org/10.5220/0012865300003758)
* and further additions made in discussions with and by the original authors that are not published yet

The purposes are divided into the different phases

## Design

| Purpose | Description | 
|:-------------------|:-------------------------------------------------------|
| Virtual Proptotyping | make a digital archetype/exemplar to analyse and verify a prototype version quickly  |
| Variation Analysis, Design Space Exploration | explore any number of variations to check their accuracy; typically iteratively |

## Operation

| Summarizing Purpose |  Purpose | Description | 
|:-------------------|:-------------------|:-------------------------------------------------------|
| Data Allocation, Persistence | Memorization | keeping track of the current runtime information |
|   | Data Recording | historical data |
|   | Knowledge Collection | context about data |
| Data Processing, Data Analysis | Verification & Validation, Consistency Monitoring | verified that the actual system and the digital twin are accurate and represent the same kind of system |
| |State Estimation | predict future situations based on historical data |
| | Anomaly Detection, Fault Detection| identify a drift between the Actual System and the Digital Twin |
| | Fault Diagnosis | identify the reason for a drift |
| Forecasting | Behaviour Prediction, Process Prediction | predict a future for the Actual System |
| | What-If Simulation | explain and predict several situations in the system |
| Modification | Control | sending control commands to the Actual System |
| | Optimization | sending an external process update to improve the Actual System |
| | Self-* | automated modification, which includes, e.g., self-adaptation, self-control, self-healing, self-reconfiguration, self-learning |


## Maintenance
|  Purpose | Description | 
|:-------------------|:-------------------------------------------------------|
| Predictive Maintenance | predict when a system will fail and suggest time when maintenance is needed |
| Fatigue Testing, Damage Evaluation| testing the sturdiness or wear and tear |
| Lifecycle Management | relation between the lifecycle of the Actual System and the Digital Twin |


## Visualization (overarching over time phases)

| Summarizing Purpose |  Purpose | Description | 
|:-------------------|:-------------------|:-------------------------------------------------------|
| Static Visualization | Console | text-based tool that either logs the current state, or allows you to browse this state|
| | Dashboard | Graphical User Interface in a more user-friendly manner |
| Dynamic Visualization | 2D Animation, Live Plots| visualization reduced to two dimensions, e.g., plots of maps |
| | 3D Animation | showing all spatial dimensions, typically combined with possibilities to rotate the object or zoom in/out |
| | Mixed Reality, AR / VR / XR| integrated into more context or the actual world |
