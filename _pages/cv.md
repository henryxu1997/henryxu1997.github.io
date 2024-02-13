---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

**Carnegie Mellon University - School of Computer Science**, Pittsburgh, PA  
**Master of Information Technology Strategy, Machine Learning and Data Analytics**  
*Aug. 2022 – Dec. 2023*  
- Cumulative GPA: 3.92/4.00  
- Relevant coursework: Network Analysis, ML Ethics and Society, Multimodal ML, Machine Learning, Mathematics for ML, Computations for ML, Applied Distributed Systems, Capstone  

**University of Toronto**, Toronto, Canada  
**Bachelor of Applied Science, Computer Engineering**  
*Sept. 2015 – May 2020*  
- Minor in Artificial Intelligence Engineering  

Research experience
======
### The Structure of Cross-National Collaboration in OSS 
**Nov. 2023 – Jan. 2024**  
Advised by **Prof. Patrick S. Park** and **Prof. Bogdan Vasilescu**
- Led the investigation of the structure of cross-national collaboration in open-source software development, focusing on cultural and geopolitical factors. Through analyzing the GitHub Innovation Graph dataset from 2020 to 2023, uncovered patterns such as U.S. dominance, cultural homophily, and the significant impacts of geopolitical events on OSS networks.
- First author submission titled “The Structure of Cross-National Collaboration in Open-Source Software Development” to CSCW 2024.

### Long-running Tie Project
**Aug. 2023 – Current**  
Advised by **Prof. Patrick S. Park** and **Prof. Kathleen Carley**
- Conducting a comprehensive analysis to assess whether long-standing network ties can help buffer against divergent opinions on controversial topics like COVID-19 and elections
- Developed a pipeline to match users that existed prior to 2015 with users in COVID-19 and election data for analysis
- Employed topic modeling and filtering techniques to categorize discussion topics
- Implemented a BERT-based model, fine-tuned on stances for specific topics such as masking policies, to detect and analyze the stance in discussions within the network
- Utilized validated fine-tuned stance detectors and various data analysis techniques to assess the impact of these ties on the cognitive distances of users on controversial subjects

### Misinformation in Social Media Dynamics 
**Feb. 2023 – Current**  
Advised by **Prof. Kathleen Carley**
- Working on a paper based on findings through experiments on misinformation
- Applied temporal analysis and statistical tests to analyze various metrics such as bot ratios, hashtag usage, social cybersecurity maneuvers, and engagement levels over time to understand how true and false information differ in their spread and support on social media platforms
- Cleaned and filtered tweets based on topic keywords, hashtags, and fine-tuned BERT-Based COVID Fact Checker into true and false information
- Reviewed Facebook and Twitter's misinformation policies to understand the regulatory landscape

### Emotions Analysis of Multimodal Social Media Content 
**Aug. 2023 – Jan. 2024**  
Advised by **Prof. Kathleen Carley**
- Led a multifaceted project aimed at analyzing emotions through textual, audio, and visual data, aligning with Plutchik's model of emotions and the concept of loneliness
- Conducted extensive literature reviews on various topics, including sentiment/emotions extraction from audio/visual data, hand-crafted and ImageNet features for object and facial expression analysis, and correlations between colors, scenes, and emotions
- Implemented color and HSV-based methods for image emotion analysis
- Utilized pre-trained models for place/scene and object analysis in images
- Applied a VGG-based approach for facial expression analysis and a CLIP-based method for broader image emotion analysis
- Established a prototype pipeline for text extraction and emotion identification from memes and audio data
- Developed a novel validation method for our system using the GPT-4 Vision model for API assisted data labeling

### Cyber-FIT (Forces-Interactions-Terrain) Project 
**Aug. 2023 – Jan. 2024**  
Advised by **Prof. Geoffrey Dobson**
- Collaborating in the enhancement of the Cyber-FIT framework, a response to the US Department of Defense's 2015 Cyber Strategy for advanced cyber modeling and simulation
- Coded and integrated critical components of the framework, focusing on the simulation of terrains, defenders, and attackers within the cyber operations context
- Employed agent-based modeling to incorporate psychological factors, such as stress, evaluating their impact on defender effectiveness during cyber attack countermeasures

### Camelmera—MMAE-Ctrl: Multimodal Masked Autoencoder for robotic control 
**Mar. 2023 – Apr.2023**  
Advised by **Prof. Yonatan Bisk**
- Proposed a novel Multimodal Masked Autoencoder (MMAE) architecture for robotic navigation, which effectively fuses multi-sensory inputs into latent representations for reinforcement learning (RL) agents
- Implemented a multimodal encoder (CNN + Vision Transformer with reconstruction loss) to process input data from various sources, such as a fish-eye camera, depth sensor, and LiDAR
- Implemented various RL agents that employ Conservative Q-Learning (CQL) for offline learning of navigation policies

### Study of Everyday User Auditing of Large Language Models 
**Mar. 2023 – Apr.2023**  
Advised by **Prof. Hoda Heidari**
- Investigated how everyday users audit ChatGPT and its backend, the GPT3.5/4 models
- Employed both qualitative and quantitative methodologies to analyze the types of errors made by ChatGPT
- Utilized LLM errors and jailbreaking prompts dataset to track users’ prompts to examine their evolution over time
- Applied topic modeling to cluster failures for manual inspection with T-SNE and LDA
- Discussed the implications of our findings and suggested future research directions to enhance LLM auditing processes

### Privacy in Users’ Mental Models of Home Assistant Devices 
**Oct. 2022 – Dec.2022**  
Advised by **Prof. Norman Sadeh** and **Prof. Hana Habib**
- Analyzed and reviewed privacy laws and policies of various Home Assistant Devices manufacturers
- Designed user survey to collect data on users’ mental models of Home Assistance Devices from 60 participants
- Demonstrated the users’ lack of understanding of the operations of these smart home devices and the need for better default settings, privacy laws, and privacy policies

### IoT Anomaly Detection 
**Mar. 2021 – Jan. 2022**  
Advised by **Prof. Alberto Leon-Garcia** and **Prof. Mehdi Shajari**
- Devised a convolutional autoencoder that encodes the spatial patterns of signature matrices from byte and packet count information across time segments, resulting in a lightweight system that is effective at performing anomalies detection on IoT device network traffic
- Implemented machine learning models in Pytorch and performed architecture search to optimize for model performance
- Researched and assessed the viability of various datasets for IoT device network traffic in relation to anomalies detection

### PhysarumSM: P2P Service Discovery and Allocation in Dynamic Edge Networks 
**Aug. 2019 – July 2020**  
Advised by **Prof. Alberto Leon-Garcia**
- Created a data collection system to monitor the network health, gathering metrics such as link latencies and memory usage
- Wrote a prototype heuristic algorithm for scheduling microservice instances, powered by the metrics provided by the monitoring system
- Work presented at IEEE IM 2021 Conference under the same name.

Work experience
======
**Telus | Data Analyst II**  
*Toronto, Canada | Jan. 2022 – Aug. 2022*  
- Worked as a Data Analyst II on the IP Multimedia Subsystem (IMS) team.  
- Designed and created tools and dashboards for KPI monitoring for VoLTE, UMTS, and VoWiFi communications.  
- Performed forecast, anomalies detection, and optimization on network data to improve user call quality.  
- Worked with Professor Alberto Leon-Garcia's research team from the University of Toronto and Montreal city government to integrate Telus cell-tower data with Montreal and Toronto city data as part of a Smart City integration project.

**Coursera | Software Engineer**  
*Toronto, Canada | July 2020 – Feb. 2021*  
- Performed service decoupling of existing services for learner enrollment, invitation, and membership in Scala to make the services more standalone, more efficient, and easier to maintain.  
- Refactored caching for learner enrollment from in-memory caching to distributed caching to minimize the risk of cache setup blocking user services.  
- Created and maintained new API for contract, enrollment, and course classification to serve customer needs.

**Amazon | Software Development Engineer Intern**  
*Berlin, Germany | June 2019 – Aug. 2019*  
- Designed and implemented a solution in Java using MapReduce framework that ran on Amazon Web Services Elastic MapReduce (AWS EMR) for performing the offline indexing of events related to customer-generated content: allow for cost-efficient creation of index snapshots, which can serve as the basis for performing the real-time indexing on a significantly smaller set of the most recent events that occurred after the snapshot.  
- Performed unit tests using JUnit 5 to ensure production-level code quality.

**Xilinx | SerDes Applications Engineering Intern**  
*San Jose, CA | May 2018 – Apr. 2019*  
- Created a scripting framework using Python, Batch, and Perl that automatically generates test parameters and collects results: improved the current FPGA hardware correlation testing flow through reducing testing overheads by 84%.  
- Enhanced signal distortion hardware testing flow by generating output data in a new format and automating the data interpretation process: reduced data collection and data interpretation overheads by 71%.  
- Built an automated regression testing system for Xilinx’s Vivado software to ensure update compatibility.


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
