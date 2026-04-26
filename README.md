# AIMS AI AGENT

### **What is the AIMS AI Agent?**
Agent AIMS powers the Advanced Imaging Medical System with advanced predictive analytics and intelligent analysis. Built on dlib, Eigen, and a custom AI reasoning engine, it delivers reliable mission-critical insights. 

## Developer Setup

---
### PACKAGE INSTALLATION
**-go to install-package.txt and download one of the zips via the drive link and extract folder in jetson orin nano**
    ```
---

---
### Hardware Deployment (Jetson)
To deploy AIMS to your physical hardware:
1  **Initialize the Hardware**:
    ```bash
    chmod +x jetson_dependencies.sh
    ./jetson_dependencies.sh
    ```
3.  **Launch the Mission**:
    ```bash
    ./aims-ai
    ```
3.  **Launch the Mission**:
    ```bash
    ./aims-ai
    ```
---

##   Project Structure
*   `intelligence/ai-src`: The C++ "Brain" of the system.
*   `intelligence/ai-include`: Core headers and library interfaces.
*   `intelligence/ai-include/visualizer/win`: Windows-specific assets and QML.
*   `intelligence/ai-include/visualizer/flex`: Jetson-specific assets and QML.
*   `aimsys`: Incoming telemetry data drops.
*   `forecasting`: AI-generated mission reports.

---

## The Vision
AIMS AI is more than just a prediction engine. It is a regression-based inference system designed to combine analytical prediction with adaptive reasoning.

<img width="620" height="256" alt="image" src="https://github.com/user-attachments/assets/4f1cbe3f-b55c-4b95-aa90-72c4995a63b0" />


## Pure Quality UI
The AIMS Visualizer is built on **Qt 6 (QML)** specifically for the AIMS Agent. The custom augmented inferface is made to match our frontend dashboard. 

*   **Dynamic Dashboard**: Real-time stats on telemetry ingestion and crew activity. 
*   **Predictive Engine**: Visual forecasts for medication and supply depletion.
*   **Audit Logs**: Deep-trace capabilities for historical mission data.
*   **Hardware Parity**: The `win` and `flex` directories ensure the UI looks identical whether you're on a desktop or an embedded ARM device.

<img width="624" height="272" alt="image" src="https://github.com/user-attachments/assets/517be9d9-2878-4d39-9463-8aa911048593" />

## The Tech Stack
*   **Core Engine**: C++17 (Optimized for both x86_64 and ARM64).
*   **Intelligence**: 
    *   **Dlib**: For advanced statistical modeling.
    *   **Eigen**: For high-performance linear algebra.
*   **UI Framework**: Qt 6.5+ (Quick/QML).
*   **Database**: Localized `.yaml` and `.csv` deep-storage for air-gapped security.

---

**Status**: Mission Ready.
**Developed in**: CLion 2026.1.1
=======
# AIMS-AGENT
AI-powered thinking, analysis, regression!
