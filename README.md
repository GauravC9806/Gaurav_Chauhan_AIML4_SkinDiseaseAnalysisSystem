# Skin_Disease_Analysis System
# 📸 Dermacare

Detect Skin Diseases with help of AI.

**Created by:**  

 GAURAV CHAUHAN (roll no: 2401730146)

 MEHUL (roll no: 2401730266)

 HARSHDEEP SINGH (roll no:2401730219)

 TOYASH(roll no: 2401730203)


## Features

* 🖼️ Upload images for skin disease type detection.
* 📹  Capture live picture feed from your webcam for real-time skin disease type detection.
* ⚙️ Further details and confidence threshold.
* ✅ Shows issues and medications with dermatologists informations.
* 📁 Detection history to review previous analyses.
* 🚀 Contact best dermatologists recommended.
## Installation

_______CURRENTLY ON OFFLINE SERVERS DUE TO DOMAIN ISSUES_______

HERE'S THE LINK TO ACCESS IT : https://mydermacare.netlify.app/

## Usage

The application has three main tabs:

* **Upload Image:** Upload an image from your computer for skin disease detection.
* **Webcam Capture:** Capture an image from your webcam for real-time detection.
* **Detection History:** Review your previous detection results.

Use the sidebar to adjust settings like image quality and confidence threshold, and whether to display bounding boxes.

## Workflow

1.  **Input:**
    * Upload an image or capture from your webcam.
2.  **Detection:**
    * Click the "Detect disease" button.
    * The input is sent to the ML Model for processing.
3.  **Results:**
    * Detected skin issue types and their confidence levels are displayed.
    * If issues are severe, dermatologists are recommended with more warning of mandatory checkup.
4.  **History:**
    * View previous inputs and results in the "Detection History" tab.

## Supported Formats

* Images: `.jpg`, `.jpeg`, `.png`
## 📽Video Presentation Of Project
  

## 🔗For Full Video Go to Drive Link
[Link](https://drive.google.com/file/d/1c_wjRgn-fU4IBQI4yxlB_iGfp9cWOTbx/view?usp=drive_link)

##  🔁WorkFlow

```doctor
flowchart LR
    A[User Input] --> B{Input Method}
    B -->|Upload Image| C[Load Image File]
    B -->|Use Webcam| D[Capture Image from Webcam]
    C --> E[Save Temp Image]
    D --> E
    E --> F[Send to ML Model for Prediction]
    F --> G[Receive Predictions]
    G --> H[Ensure disease effect is either bad or worse]
    H --> I[Display Results and recommend doctors and medicines]
```
