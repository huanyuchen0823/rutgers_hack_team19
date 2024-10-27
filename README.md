
# Alpha Skin

Alpha Skin is an innovative solution designed to support spinal health by providing real-time motion analysis and corrective feedback for individuals with scoliosis and kyphotic deformities. Leveraging wearable piezoelectric textiles, a cloud-based Large Language Model (LLM), and Edge AI, Alpha Skin delivers personalized guidance to improve posture and movement patterns. The system combines cloud-based learning with real-time local processing to deliver adaptive and individualized support.

---

## Table of Contents
- [Overview](#overview)
- [Technology Stack](#technology-stack)
- [Solution Architecture](#solution-architecture)
- [Installation and Deployment](#installation-and-deployment)
- [Usage](#usage)
- [Project Repository](#project-repository)
- [Demo Video](#demo-video)
- [Working Prototype](#working-prototype)

---

### Overview

Alpha Skin uses a real-time feedback loop between wearable motion sensors and a cloud-based LLM feature extractor. The system evaluates user motion based on optimal postural alignment standards, identifies incorrect postures, and provides instant corrective guidance. By merging **cloud computing** with **Edge AI**, the platform continuously refines its models with federated learning, while also personalizing feedback at the local device level.

---

### Technology Stack

- **Language Models**: LLM API for real-time motion analysis and feedback.
- **Wearable Technology**: Piezoelectric textile sensors for detecting spinal movement.
- **Cloud Platform**: AWS or any suitable cloud provider for model hosting, data processing, and federated learning.
- **Edge AI**: Local processing on user devices for low-latency feedback.
- **Containerization**: Docker for environment consistency in cloud deployments.

---

### Solution Architecture

The architecture of Alpha Skin is built on a **cloud-edge hybrid model** to leverage both scalability and personalized, on-device functionality.

1. **Wearable Sensor Network**:
    - **Piezoelectric Sensors** are embedded in textiles worn over the shoulders, backbone, and cervical vertebrae.
    - These sensors capture real-time motion data and transfer it to a local processing unit.

2. **Edge AI on Local Device**:
    - A locally hosted model evaluates the sensor data to provide instant feedback on motion correctness.
    - The model syncs with the cloud periodically to receive updates from the general LLM feature extractor, refining it based on the user’s personalized data.

3. **Cloud-Based LLM and Federated Learning**:
    - The cloud-hosted LLM receives anonymized data from users to learn general patterns and continuously improve the general model.
    - **Federated Learning** updates the LLM without transferring sensitive user data, ensuring privacy while enhancing the model.

4. **Feedback and Visualization**:
    - Local feedback is provided through multiple modalities, including visual prompts, haptic feedback, and session summary reports.
    - Future implementations aim to add graphical representations of corrective postures and movement patterns.

---

### Installation and Deployment

#### Prerequisites
- **Python 3.8+** installed on the local machine.
- **Docker** installed for containerized deployment of cloud components.
- **LLM API Key** for accessing LLM model.
- **AWS or Cloud Provider Account** for hosting the LLM model and handling data flow.


---

### Usage

After installation, users can wear the *Alpha Skin* sensor-embedded garment and start the application. The local device processes sensor data, evaluates postural correctness, and provides corrective feedback. The cloud model periodically updates, improving the model’s general accuracy and personalization.

---

### Project Repository

The full project repository, including source code, documentation, and resources, can be accessed [here](https://github.com/huanyuchen0823/rutgers_hack_team19).

---

### Demo Video

A brief demo video showcasing *Alpha Skin*'s concept, technology stack, and healthcare impact can be accessed [here](https://github.com/huanyuchen0823/rutgers_hack_team19/blob/main/pre.mp4).

--- 


### Documentation

A brief technical documentation which shows *Alpha Skin*'s concept, technology stack, and healthcare impact can be accessed [here](https://github.com/huanyuchen0823/rutgers_hack_team19/blob/main/Final%20Project_Team19%20Rutgers%20Health%20Hack%202024.pdf).


--- 

### Documentation

Alpha Skin includes a functional prototype that showcases our cloud and Edge AI integration, highlighting how healthcare data and motion tracking can be used to provide real-time corrective feedback. This prototype consists of:

- Codebase: This repository includes the core code that powers Alpha Skin’s data processing and real-time feedback loop.
- Demo App: A demo version of the Alpha Skin app can be accessed [here](https://app.uizard.io/p/ed93eb2c/preview), showing how the user interface and interaction flow work to support spinal health.

Together, these components demonstrate how wearable technology, cloud processing, and user-centered correction converge into a single solution.

--- 
