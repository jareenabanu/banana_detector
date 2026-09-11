# BananaMath 🍌🎯

## Basic Details

**Team Name:** Innov8

### Team Members

**Team Lead:** Jareena Banu S. - Rajiv Gandhi Institute of Technology, Kottayam
**Member 2:** Anand V R - Rajiv Gandhi Institute of Technology, Kottayam

## Project Description

BananaMath is an AI-powered web application that detects bananas from uploaded images using YOLO segmentation. It analyzes the detected banana and calculates its curvature to provide a fun mathematical classification.

## The Problem (that doesn't exist)

Have you ever looked at a banana and wondered:

**“Exactly how mathematically curved is this banana?”** 🍌📐

Probably not. But we decided this extremely important problem deserved an AI solution.

## The Solution (that nobody asked for)

BananaMath allows users to upload a banana image and automatically detects the banana using a YOLO segmentation model.

The system analyzes the detected banana, calculates its curvature, and displays the detection confidence, banana count, curvature value, and a fun classification.

No image matching. No filename guessing. Every uploaded image is processed using the actual detection model.

## Technical Details

### Technologies/Components Used

### For Software:

* **Languages:** Python, JavaScript, HTML, CSS
* **Frontend:** React, Vite
* **Backend:** Node.js, Express.js
* **Machine Learning:** YOLO Segmentation
* **Libraries:** Ultralytics YOLO, PyTorch, Torchvision, OpenCV, NumPy, Multer, CORS
* **Model:** `yolo26n-seg.pt`
* **Tools:** VS Code, Git, GitHub, PowerShell, Docker

### For Hardware:

* No dedicated hardware is required.
* Computer/Laptop
* Web browser
* Internet connection
* Banana image from a phone or camera

## Implementation

### For Software:

The project works through the following process:

1. The user uploads a banana image.
2. The React frontend sends the image to the backend.
3. Node.js and Express receive the uploaded image.
4. The backend runs the Python analysis program.
5. YOLO segmentation detects the banana in the image.
6. The detected banana is analyzed for its curvature.
7. The analysis result is returned to the frontend.
8. BananaMath displays the detection confidence, banana count, curvature and classification.

## Installation

Clone the repository:

```bash
git clone https://github.com/jareenabanu/banana_detector.git
cd banana_detector
```

Install backend dependencies:

```bash
cd backend
npm install
cd ..
```

Install frontend dependencies:

```bash
cd frontend
npm install
cd ..
```

Install Python dependencies:

```bash
pip install -r requirements.txt
```

## Run

From the project root directory:

```bash
npm run dev
```

The command starts both the frontend and backend.

Frontend:

```text
http://localhost:5173
```

If port 5173 is already in use, Vite automatically selects another available port, such as:

```text
http://localhost:5174
```

Backend:

```text
http://localhost:5000
```

## Project Documentation

### For Software:

## Screenshots

![Screenshot1](screenshots/upload-page.png)

**Upload Page:** Shows the BananaMath interface where users can upload or drag and drop a banana image.

![Screenshot2](screenshots/result-page.png)

**Result Page:** Displays the analysis results including banana detection, confidence, curvature and classification.

![Screenshot3](screenshots/processed-image.png)

**Processed Image:** Shows the processed banana image generated after YOLO segmentation and curvature analysis.

## Diagrams

![Workflow](screenshots/workflow.png)

**Workflow:** Shows the complete workflow from image upload to banana detection, curvature analysis and result display.

## For Hardware:

**Not applicable. BananaMath is a software-only project.**

## Schematic & Circuit

**Not applicable.**

## Build Photos

**Not applicable.**

## Project Demo

### Video

[Add your demo video link here]

The demo video demonstrates uploading a new banana image, detecting the banana using YOLO segmentation, calculating its curvature and displaying the final result.

### Additional Demos

* GitHub Repository: https://github.com/jareenabanu/banana_detector
* Live Demo: Add the deployed website link after hosting

## Team Contributions

**Jareena Banu S.:**

* Developed the frontend interface using React and Vite
* Worked on UI design and user experience
* Worked on project documentation and presentation
* Assisted with testing and deployment

**Anand V R:**

* Worked on YOLO-based banana detection and curvature analysis
* Integrated the image upload and analysis workflow
* Worked on backend integration
* Assisted with testing and validation
