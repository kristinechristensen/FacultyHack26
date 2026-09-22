# FacultyHack@Gateways 2026 Curriculum Project

## Project Overview

**Project Title:** BRIDGE-CI: From Sensors to Scientific Computing

This project revises **LAN 120: IoT Fundamentals I**, an entry-level Internet of Things course at Moraine Valley Community College with no prerequisites. The course introduces students to electronics, Arduino programming, sensors, networking, IoT data, privacy, and cybersecurity.

The FacultyHack curriculum redesign expands the course by introducing students to **Science Gateways, Jupyter notebooks, public datasets, cloud computing, and High-Performance Computing (HPC) resources** in an approachable way. Students first gain guided experience working with authentic IoT, industrial, cybersecurity, and critical infrastructure datasets. They learn to run prepared notebook cells, modify selected variables, create visualizations, and interpret results without requiring prior Python or HPC experience.

Students then transfer those skills to a hands-on final project. Each student develops a research question, selects and programs an electronic sensor, collects a manageable original dataset, and uses a scaffolded Jupyter notebook to analyze and visualize the data. The final deliverable includes a technical report that explains the system, methods, findings, limitations, and potential cybersecurity or critical infrastructure applications.

The broader goal is to increase student awareness of advanced computing resources while showing that the same core process used in data-intensive research can also be applied to a small classroom project:

**Ask a question → collect data → prepare data → visualize patterns → interpret results → communicate findings**

---

## Faculty Information

**Name:** Dr. Kristine Christensen  
**Institution:** Moraine Valley Community College  
**Department/Discipline:** Computer Information Systems / Internet of Things / Cybersecurity  

### Brief Bio / CV

Dr. Kristine Christensen is a Professor of Computer Information Systems and Director of Faculty Development at Moraine Valley Community College. Her teaching and professional work span cybersecurity, networking, web development, IoT, robotics, electronics, engineering technology, manufacturing, automation, and emerging technologies. She focuses on helping students connect hands-on technical learning with real-world applications, career pathways, and interdisciplinary opportunities.

She serves as Principal Investigator and co-Principal Investigator on multiple nationally funded initiatives related to cybersecurity education, workforce development, faculty preparation, and career awareness. Her current work includes the ExploreCyber project, the NCyTE Community College Cybersecurity Faculty Fellowship, and projects involving AI, critical infrastructure, science gateways, and emerging technologies. She holds a Ph.D. in Community College Leadership and multiple graduate degrees across business, information systems, teaching and learning, and communication, and is completing an M.S. in Cybersecurity at the Georgia Institute of Technology.

### Faculty Headshot

Upload the headshot image to the repository's `/images` folder and update the filename below if needed.

`![Faculty Headshot](./images/headshot.png)`

---

## Mentorship & Support

**Assigned Technical Mentors:**  
- **Dr. John Holmen**, Oak Ridge National Laboratory (ORNL)  
- **Charlie Dey**, Texas Advanced Computing Center (TACC)  

---

## Project Goals

- Introduce entry-level IoT students to Science Gateways, public datasets, Jetstream2, Jupyter notebooks, cloud computing, and HPC resources.
- Develop foundational notebook and visualization skills through scaffolded activities designed for students with no prior Python or HPC experience.
- Help students run prepared code, modify selected variables, visualize authentic IoT and industrial data, and interpret the results.
- Introduce AI-assisted anomaly detection, cybersecurity, and critical infrastructure applications in an approachable manner.
- Guide students in transferring these skills to a sensor-based final project in which they collect, analyze, visualize, and report on their own data.

---

## Science Gateway Goal

Develop a Science Gateways-based learning experience that enables introductory community college IoT students to analyze authentic and student-generated sensor data using Jupyter notebooks and Jetstream resources, helping them understand how IoT data can be visualized, analyzed, secured, and scaled beyond a single device.

---

## Science Gateway Resources & Technology Notes

### Tools Used

**Jetstream2**  
* **Description:** A cloud-based research and education computing environment that provides access to virtual machines and advanced computing resources.
* **Course Use:** Students will be introduced to browser-based computing environments and use prepared Jupyter resources to explore public IoT and sensor datasets. The goal is to expose students to computing beyond the desktop without requiring prior HPC experience.

**Jupyter Notebooks**  
* **Description:** Interactive computational documents that combine executable code, explanatory text, data, and visualizations.
* **Course Use:** Students will use scaffolded notebooks to load datasets, run prepared Python code, modify selected variables, create visualizations, and interpret findings. Students will later adapt a notebook template to analyze data collected from their own Arduino sensor project.

**Public IoT and Industrial Datasets**  
* **Description:** Authentic datasets that allow students to explore sensor behavior, industrial systems, cybersecurity, and critical infrastructure applications.
* **Course Use:** Public datasets will provide guided practice before students collect and analyze their own data.

### Proposed Datasets

| Dataset | Hosted By | What It Contains | Planned Course Use |
|---|---|---|---|
| **MetroPT-3** | UCI Machine Learning Repository | Time-series sensor data from a metro train air-production system, including pressure, temperature, motor current, and equipment status signals | Introduce Jupyter, sensor-data exploration, descriptive statistics, time-series visualization, thresholds, and anomaly identification |
| **RT-IoT2022** | UCI Machine Learning Repository | IoT network traffic with normal activity and labeled cyberattacks | Guided introduction to AI-assisted cybersecurity analysis, normal vs. malicious behavior, and false positives/false negatives |
| **TON_IoT** | UNSW Canberra | IoT/IIoT telemetry, network traffic, and Windows/Linux system data across edge, fog, and cloud layers | Demonstrate connections among IoT, IT, OT, cybersecurity, AI, and critical infrastructure |
| **Student-Generated Sensor Data** | LAN 120 students | Small datasets collected from student-selected Arduino sensors | Final project in which students develop a research question, collect data, visualize results, interpret findings, and write a technical report |

### Implementation Notes

* **Session 1:** Explore Science Gateway and HPC concepts, account requirements, Jetstream2 access, and possible classroom workflows for a no-prerequisite community college course.
* **Session 2:** Review beginner-friendly Jupyter notebook structures, visualization activities, and public IoT/industrial datasets that can be adapted for guided student practice.
* **Session 3:** Develop a scaffolded progression from public datasets to student-generated sensor data, including notebook templates, variable modification, visualization, and final-project assessment.
* **Ongoing:** Refine account setup, reusable environments, notebook distribution, dataset preparation, and strategies for maintaining the materials in future course sections.

---

## Science Gateway Resource Needs / Questions

- Guidance selecting an appropriate Science Gateway, cloud, or HPC environment.
- Assistance setting up instructor and student accounts and educational access.
- Help creating a beginner-friendly, browser-based Jupyter environment.
- Recommendations for introductory IoT, sensor, cybersecurity, and critical infrastructure datasets.
- Support adapting or developing scaffolded notebooks for data exploration and visualization.
- Guidance for allowing students to upload and analyze data collected from their own sensors.
- Recommendations for maintaining and reusing the environment and notebooks in future semesters.

---

## Planned Learning Progression

### 1. Awareness and Exploration

Students are introduced to:

- Science Gateways
- Cloud and HPC resources
- Public research datasets
- Jupyter notebooks
- Data visualization
- AI-assisted analysis
- IoT cybersecurity
- IT/OT environments
- Critical infrastructure applications

### 2. Guided Notebook Practice

Students use scaffolded notebooks to:

- Open and run notebook cells
- Load and inspect a dataset
- Select variables
- Filter data
- Calculate simple descriptive statistics
- Create and modify visualizations
- Change selected analysis parameters
- Interpret patterns and anomalies

### 3. Student Sensor Investigation

Students transfer the same workflow to a manageable final project:

1. Develop a research question.
2. Select an Arduino-compatible sensor.
3. Build or simulate the circuit.
4. Program the Arduino.
5. Determine a data-collection method and sampling interval.
6. Collect and export a small dataset.
7. Load the data into a scaffolded Jupyter notebook.
8. Clean, summarize, and visualize the data.
9. Interpret the results.
10. Explain limitations and possible next steps.
11. Connect the sensor or analysis to IoT cybersecurity or critical infrastructure.
12. Communicate findings in a technical report.

---

## Student Assessment

Students will be assessed on their ability to apply the process rather than on producing a large dataset or advanced machine-learning model.

### Guided Activities

Students will demonstrate that they can:

- Navigate and run a Jupyter notebook.
- Modify selected variables.
- Create appropriate visualizations.
- Interpret what the data show.
- Recognize anomalies and limitations.
- Explain the purpose of Science Gateways, HPC, and public datasets.

### Final Project

The final project will assess:

- **Research question and project plan**
- **Electronics and Arduino programming**
- **Data collection and organization**
- **Jupyter notebook use**
- **Visualization and interpretation**
- **Cybersecurity / critical infrastructure connection**
- **Technical report and communication of findings**

---

## Deliverables Checklist

- [ ] **Original Syllabus:** [original_syllabus.pdf](./original_syllabus.pdf)
- [ ] **Revised Syllabus:** [revised_syllabus.pdf](./revised_syllabus.pdf)
- [ ] **Gateways 2026 Poster:** [poster_final.pdf](./poster_final.pdf)
- [ ] **SGX3 Blog Post Draft:** [blog_post.md](./blog_post.md)
- [ ] **Guided Jupyter Notebook(s):** [notebooks](./notebooks/)
- [ ] **Final Project Notebook Template:** [student_sensor_project.ipynb](./notebooks/student_sensor_project.ipynb)
- [ ] **Dataset Documentation:** [datasets](./datasets/)
- [ ] **Student Project Instructions:** [project_instructions.md](./project_instructions.md)

---

## Event Details

* **Virtual Hackathon:** August 3–14, 2026
* **In-Person Conference:** [Gateways 2026](https://na.eventscloud.com/ereg/newreg.php?eventid=874568&#) | September 23–25, 2026 | Washington, D.C.

---

## Event Citation

This project was developed as part of **SGX3's 5th Annual FacultyHack@Gateways 2026**. FacultyHack is a hands-on program designed to empower educators across disciplines to integrate High-Performance Computing (HPC) and Artificial Intelligence (AI) tools directly into their curricula.

For more information, event archives, and resources, please visit the official event site:

**[FacultyHack@Gateways 2026 Official Site](https://hackhpc.github.io/facultyhack-gateways26)**
