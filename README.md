# Face-Recognition-Attendance-System

This project is a **Face Attendance System** using Python, OpenCV, `face_recognition`, and `Tkinter`. It recognizes faces from a webcam and marks attendance in an Excel sheet.

## 📁 Project Structure

```
📂 FaceAttendanceProject/
│
├── faces_encoding.ipynb      # Script to load and encode known faces
├── GUI.ipynb                 # GUI app for live face recognition and attendance marking
├── encodings.pkl             # Auto-generated file that stores face encodings
├── D:\Attendance\persons     # Folder that contains images of known people
└── README.md                 # You're here!
```

##  Step-by-Step Usage

### 1. Add Person Images
- Go to `path\to\your\images`
- Add clear, front-facing images of each person.
- Each image file name must be the person's name (`John Doe.jpg`,`Mark John.jpg`,....).

### 2. Encode Faces
```bash
python faces_encoding.ipynb
```

### 3. Run the GUI
```bash
python GUI.ipynb
```

### 4. Attendance Output
- Excel file will be saved to your Desktop as `FaceAttendance_Project.xlsx`

## 🛠️ Requirements
```bash
pip install opencv-python face_recognition pandas openpyxl pillow
```
