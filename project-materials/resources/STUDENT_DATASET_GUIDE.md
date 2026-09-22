# 📊 LAN 120 Dataset Guide  
## BRIDGE-CI: From Sensors to Scientific Computing

Welcome to the **LAN 120 Dataset Guide**! In this course, you will work with real-world IoT and cybersecurity datasets before collecting and analyzing data from your own Arduino sensor project.

The goal is not to become a data scientist or HPC expert. Instead, you will learn how to:

- explore real sensor and IoT data;
- create and interpret visualizations;
- recognize patterns and unusual behavior;
- understand how AI can assist with anomaly detection;
- connect IoT data to cybersecurity and critical infrastructure;
- apply the same process to data you collect yourself.

---

## 🧭 The BRIDGE-CI Data Journey

You will move through the course in stages:

> **Explore real data → Practice in Jupyter → Investigate patterns → Examine anomalies → Collect your own data → Analyze and explain your results**

Each dataset below supports a different part of that journey.

---

# 🚆 Dataset 1: MetroPT-3

### What is it?

**MetroPT-3** contains sensor data collected from the air production system of a metro train.

The dataset includes measurements such as:

- pressure;
- temperature;
- motor current;
- valve status;
- operating conditions over time.

### Why are we using it?

This dataset is a good starting point because it looks a lot like the type of information an IoT sensor might collect, but at a much larger scale.

You will use it to practice:

- opening a dataset in Jupyter;
- inspecting rows and columns;
- creating time-series graphs;
- identifying normal patterns;
- looking for thresholds or unusual readings;
- thinking about how sensor data can support maintenance and transportation systems.

### What you should focus on

You do **not** need to understand every column in the full dataset.

Instead, focus on questions such as:

- What does this sensor measure?
- How does the value change over time?
- What looks normal?
- What looks unusual?
- What might cause a sudden change?
- Why would this matter in a transportation system?

### 🔗 Dataset Link

[MetroPT-3 - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/791/metropt%203%20dataset)

---

# 🛡️ Dataset 2: RT-IoT2022

### What is it?

**RT-IoT2022** contains network data from a real-time IoT environment.

It includes both:

- **normal IoT activity**, and
- **cyberattack activity**.

Examples of attacks in the dataset include:

- scanning;
- SSH brute-force attempts;
- DDoS activity;
- Slowloris;
- other suspicious network behavior.

### Why are we using it?

This dataset helps connect **IoT devices to cybersecurity**.

You will use it to explore how a system may distinguish between normal and suspicious behavior.

### What you will practice

- comparing normal and malicious activity;
- examining selected network features;
- viewing AI-assisted classifications;
- reading a confusion matrix;
- understanding **false positives** and **false negatives**;
- considering what could happen if a cybersecurity system makes the wrong decision.

### Key idea

> **AI can help identify patterns, but its output is evidence to examine, not automatic truth.**

You will be expected to interpret the results and explain what they mean.

### 🔗 Dataset Link

[RT-IoT2022 - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/942/rt-iot2022)

---

# 🏭 Dataset 3: TON_IoT

### What is it?

**TON_IoT** is a larger dataset that combines several types of information from an IoT and Industrial IoT environment.

It includes:

- IoT and IIoT sensor data;
- network traffic;
- Windows system data;
- Linux system data;
- normal activity;
- cyberattack activity.

### Why are we using it?

TON_IoT helps show how IoT fits into a much larger system.

Instead of looking only at one sensor, we can start thinking about how:

- IoT devices;
- IT systems;
- operational technology (OT);
- cloud systems;
- cybersecurity tools

can all interact.

### What you should focus on

You will work with a **smaller instructor-prepared subset**, not the entire dataset.

You may be asked to think about questions such as:

- Can sensor data and network data tell us different parts of the same story?
- What could indicate that a device is behaving abnormally?
- How might cyber activity affect a physical system?
- Why might a large organization need cloud or HPC resources to analyze this amount of data?

### 🔗 Dataset Link

[TON_IoT - UNSW Canberra](https://research.unsw.edu.au/projects/toniot-datasets)

---

# 🔧 Dataset 4: Your Own Arduino Sensor Data

This is the dataset you will create for your **final project**.

You will select an Arduino-compatible sensor and collect your own measurements.

Possible sensor topics include:

- 🌡️ temperature;
- 💧 humidity;
- 💡 light;
- 📏 distance;
- 🚶 motion;
- 🌱 soil moisture;
- 🔊 sound;
- 📳 vibration;
- 🌫️ air quality;
- 🌬️ pressure.

---

## 🎯 Your Final Project Data Workflow

You will:

1. **Develop a research question**
2. **Select a sensor**
3. **Build and program your Arduino system**
4. **Choose a sampling method**
5. **Collect data**
6. **Save or export the data as CSV**
7. **Open the data in Jupyter**
8. **Create visualizations**
9. **Interpret what the data show**
10. **Discuss limitations**
11. **Connect your project to IoT cybersecurity or critical infrastructure**
12. **Explain your findings in a technical report**

---

# 🧪 What Is a CSV File?

A **CSV file** is a simple text file used to store data in rows and columns.

CSV stands for:

> **Comma-Separated Values**

A sensor dataset might look like this:

```csv
timestamp,temperature,humidity
10:00:00,22.4,41.2
10:00:10,22.5,41.0
10:00:20,22.7,40.9
```

Each row is one observation.

Each column is one variable.

---

# 📓 What Will We Do in Jupyter?

You will use **Jupyter notebooks** to work with the datasets.

You will not be expected to write an entire Python program from scratch.

Instead, you will use **scaffolded notebooks** that contain prepared code.

You may be asked to:

- run a code cell;
- change a filename;
- choose a column;
- adjust a threshold;
- change a graph;
- compare two variables;
- interpret a result.

### Example

```python
data.plot(x="timestamp", y="temperature")
```

You might later modify `"temperature"` to another sensor variable and explain how the visualization changes.

---

# 🤖 Where Does AI Fit?

AI will be introduced as a tool that can help identify patterns or possible anomalies.

You may use prepared examples that show how an AI or machine-learning model classifies data.

You are **not** expected to build an advanced AI model.

Instead, focus on:

- what the model identified;
- whether the result makes sense;
- what evidence supports the result;
- what a false positive means;
- what a false negative means;
- what the consequences could be in an IoT or critical infrastructure environment.

---

# 🏗️ Why Does Critical Infrastructure Matter?

IoT sensors are used in many systems that support everyday life, including:

- transportation;
- energy;
- water;
- manufacturing;
- buildings;
- agriculture;
- communications.

Your classroom project may be small, but the same types of sensors and data-analysis processes can appear in much larger systems.

A useful question to keep asking is:

> **What could happen if this sensor produced incorrect data, stopped reporting, or was manipulated?**

---

# 🧠 Questions to Ask When Exploring Any Dataset

Whenever you work with data, ask:

### About the Data
- What does each column represent?
- What units are being used?
- How often was the data collected?
- Are any values missing?
- Are there values that look unusual?

### About the Pattern
- What looks normal?
- What changes over time?
- Are there spikes, drops, or repeated patterns?
- Could there be a reasonable physical explanation?

### About the Evidence
- What does the visualization actually show?
- What does it **not** prove?
- What additional data would help?

### About Security
- Could incorrect or manipulated data affect a decision?
- Could unusual data indicate a cyberattack?
- Could it simply be a sensor failure?

---

# ✅ Recommended Course Sequence

| Activity | Dataset | Main Focus |
|---|---|---|
| **Guided Notebook 1** | MetroPT-3 | Sensor data, time series, visualization, trends |
| **Guided Notebook 2** | RT-IoT2022 | IoT cybersecurity, anomaly detection, AI-assisted analysis |
| **Extension / Case Study** | TON_IoT | IT/OT, critical infrastructure, larger computing environments |
| **Final Project** | Your sensor data | Apply the complete process to your own investigation |

---

# ⭐ Remember

You are **not** being graded on having the largest dataset or the most complicated code.

You are learning how to follow a sound process:

> **Ask a question → collect data → organize it → visualize it → interpret it → explain what it means**

That process is useful whether you are working with:

- 100 Arduino sensor readings,
- thousands of IoT network records, or
- millions of measurements in a scientific computing environment.

---

## 📚 Public Dataset Sources

- [MetroPT-3 - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/791/metropt%203%20dataset)
- [RT-IoT2022 - UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/942/rt-iot2022)
- [TON_IoT - UNSW Canberra](https://research.unsw.edu.au/projects/toniot-datasets)

---

**LAN 120: IoT Fundamentals I**  
**BRIDGE-CI: From Sensors to Scientific Computing**  
Moraine Valley Community College
