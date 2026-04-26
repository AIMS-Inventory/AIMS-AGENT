---

# AIMS AI AGENT

### **What is the AIMS AI Agent?**
Agent AIMS powers the Advanced Imaging Medical System with advanced predictive analytics and intelligent analysis. Built on **dlib**, **Eigen**, and a custom AI reasoning engine, it delivers reliable mission-critical insights.

---

## Developer Setup

### Package Installation
1. Go to `install-package.txt`.
2. Download one of the `.zip` or '.7z' file via the provided Drive link.
3. Extract the file as a folder into your **Jetson Orin Nano**.

### Hardware Deployment (Jetson)
To deploy AIMS to your physical hardware:

1. **Initialize the Hardware**:
    ```bash
    chmod +x jetson_dependencies.sh
    ./jetson_dependencies.sh
    ```
2. **Launch the Mission**:
    ```bash
    ./aims-ai
    ```

---

## Project Structure
* `intelligence/ai-src`: The C++ "Brain" of the system.
* `intelligence/ai-include`: Core headers and library interfaces.
* `intelligence/ai-include/visualizer/win`: Windows-specific assets and QML.
* `intelligence/ai-include/visualizer/flex`: Jetson-specific assets and QML.
* `aimsys`: Incoming telemetry data drops.
* `forecasting`: AI-generated mission reports.

---

## The Vision
AIMS AI is more than just a prediction engine. It is a regression-based inference system designed to combine analytical prediction with adaptive reasoning.

<img width="655" height="280" alt="image" src="https://github.com/user-attachments/assets/e6e9a5ff-d2b6-4d44-ad46-535af181279c" />


---

## Pure Quality UI
The AIMS Visualizer is built on **Qt 6 (QML)** specifically for the AIMS Agent. The custom augmented interface is designed to match our frontend dashboard.

* **Dynamic Dashboard**: Real-time stats on telemetry ingestion and crew activity.
* **Predictive Engine**: Visual forecasts for medication and supply depletion.
* **Audit Logs**: Deep-trace capabilities for historical mission data.
* **Hardware Parity**: The `win` and `flex` directories ensure the UI looks identical whether you're on a desktop or an embedded ARM device.

<img width="694" height="857" alt="image" src="https://github.com/user-attachments/assets/1ab4a6bc-8a44-4c86-baae-cd7c8f018e8f" />

---

## The Tech Stack
* **Core Engine**: C++17 (Optimized for both x86_64 and ARM64).
* **Intelligence**:
    * **Dlib**: For advanced statistical modeling.
    * **Eigen**: For high-performance linear algebra.
* **UI Framework**: Qt 6.5+ (Quick/QML).
* **Database**: Localized `.yaml` and `.csv` deep-storage for air-gapped security.

<img width="640" height="670" alt="image" src="https://github.com/user-attachments/assets/170e9d36-5ae2-4b64-b1eb-cd4083289f3e" />

---

**Status**: Mission Ready  
**Developed in**: CLion 2026.1.1  

# AIMS-AGENT
> AI-powered thinking, analysis, regression!
