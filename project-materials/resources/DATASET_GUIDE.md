# LAN 120 BRIDGE-CI Dataset Guide

This guide identifies the public datasets used or considered for the BRIDGE-CI course redesign and explains how each can support an introductory IoT course. The goal is not for students to master large-scale data science. Instead, the datasets provide authentic examples that help students move from sensor readings to visualization, interpretation, cybersecurity, and scientific computing.

## 1. MetroPT-3

**Source:** UCI Machine Learning Repository  
**Dataset page:** https://archive.ics.uci.edu/dataset/791/metropt%203%20dataset  
**DOI:** https://doi.org/10.24432/C5VW3R

### What it contains
MetroPT-3 contains time-series data collected from the Air Production Unit of a metro train. The data include measurements such as pressure, temperature, motor current, and air-intake valve status.

### Why it fits LAN 120
This dataset provides a clear bridge between physical sensors and larger industrial datasets. Students can recognize familiar sensor concepts while working with data collected from an operational transportation system.

### Suggested course use
Use MetroPT-3 for the first guided Jupyter activity to:
- load and inspect a CSV dataset;
- examine time-series sensor readings;
- create line charts and other visualizations;
- calculate simple descriptive statistics;
- explore thresholds, rolling averages, trends, and unusual readings;
- discuss predictive maintenance and transportation infrastructure.

### Classroom note
The complete dataset is large for an introductory activity. A smaller instructor-prepared subset is recommended for students.

---

## 2. RT-IoT2022

**Source:** UCI Machine Learning Repository  
**Dataset page:** https://archive.ics.uci.edu/dataset/942/rt-iot2022  
**DOI:** https://doi.org/10.24432/C5P338

### What it contains
RT-IoT2022 contains network data from a real-time IoT environment with both normal and malicious activity. Devices represented include MQTT-connected temperature devices, smart bulbs, and other IoT systems. Attack examples include scanning, SSH brute force, DDoS, Slowloris, and related network activity.

### Why it fits LAN 120
This dataset connects IoT devices to networking and cybersecurity, extending the course beyond the physical sensor itself.

### Suggested course use
Use RT-IoT2022 for a guided AI/cybersecurity notebook to:
- compare normal and malicious network behavior;
- explore labeled data;
- visualize selected network features;
- examine AI-assisted or machine-learning classifications;
- interpret a confusion matrix;
- discuss false positives and false negatives;
- consider the operational consequences of incorrect classifications.

### Classroom note
Students do not need to build the machine-learning model themselves. A scaffolded notebook can provide the code so the emphasis remains on interpreting evidence.

---

## 3. TON_IoT

**Source:** UNSW Canberra  
**Dataset page:** https://research.unsw.edu.au/projects/toniot-datasets

### What it contains
TON_IoT combines multiple types of data from an IoT/Industrial IoT environment, including:
- IoT and IIoT telemetry;
- network traffic;
- Windows system data;
- Linux system data;
- normal activity and cyberattack activity.

The test environment includes IoT, edge/fog, cloud, and networked systems.

### Why it fits LAN 120
TON_IoT provides a useful example of how IoT, IT, OT, cloud computing, and cybersecurity can intersect in a larger system. It is particularly useful for making connections to critical infrastructure and Industry 4.0.

### Suggested course use
Rather than asking introductory students to work with the entire collection, use a selected instructor-prepared subset to:
- compare physical/telemetry evidence with network or system evidence;
- discuss IT/OT convergence;
- identify possible anomalous behavior;
- connect IoT security to industrial and critical infrastructure environments;
- demonstrate how larger datasets create a need for scalable computing resources.

### Classroom note
TON_IoT is best treated as an extension or case-study dataset. A carefully selected subset will make the activity much more accessible.

---

## 4. Student-Generated Arduino Sensor Data

**Source:** LAN 120 student projects  
**Public link:** Not applicable

### What it contains
Students collect a small original dataset using an Arduino-compatible sensor. Possible measurements include:
- temperature;
- humidity;
- light;
- distance;
- motion;
- soil moisture;
- sound;
- vibration;
- air quality;
- pressure.

### Why it fits LAN 120
This is the transfer step in the BRIDGE-CI learning sequence. Students apply the same basic workflow used with authentic public datasets to data they collected themselves.

### Suggested course use
For the final project, students:
1. develop a research question;
2. select and program a sensor;
3. plan a sampling method;
4. collect and save data;
5. export the data to CSV;
6. load the data into a scaffolded Jupyter notebook;
7. create visualizations;
8. interpret results and limitations;
9. connect the investigation to IoT cybersecurity or critical infrastructure;
10. communicate findings in a technical report.

---

## Recommended Sequence

| Course Activity | Dataset | Primary Purpose |
|---|---|---|
| Guided Notebook 1 | MetroPT-3 | Sensor data, time series, visualization, trends, thresholds |
| Guided Notebook 2 | RT-IoT2022 | IoT cybersecurity, anomaly detection, AI-assisted classification |
| Extension / Case Study | TON_IoT | IT/OT, Industry 4.0, critical infrastructure, scalable computing |
| Final Project | Student-generated data | Transfer the workflow to an original sensor investigation |

## Dataset Use and Attribution

When materials are shared publicly, retain the original dataset names and source links. MetroPT-3 and RT-IoT2022 are available through the UCI Machine Learning Repository and provide citation information on their dataset pages. TON_IoT is provided by UNSW Canberra; review the dataset page for its academic-use and citation guidance before redistributing any files.

For the course repository, it is usually better to link to the original dataset source rather than upload full public datasets. If small instructional subsets are included in the repository, document:
- the original source;
- which rows/columns were selected;
- any cleaning or transformations performed;
- the date the subset was created;
- the purpose of the subset.
