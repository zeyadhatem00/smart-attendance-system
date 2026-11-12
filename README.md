# Smart Attendance System 🎓

A simple attendance management system that uses **Computer Vision and Face Recognition** to automatically identify people and record their attendance.

The system captures faces through a camera, recognizes registered individuals using Python and OpenCV, and saves their names and attendance timestamps. An Arduino board can also be connected to an LCD screen to display the recognition results.

## ✨ Features

- Face Detection and Recognition.
- Automatic Attendance Recording.
- Save Names, Dates, and Timestamps.
- Display Recognition Results on an LCD Screen.
- Reduce Manual Attendance Tracking.

## 🛠️ Technologies Used

**Software:**
- Python
- OpenCV
- Face Recognition
- NumPy
- Pandas

**Hardware:**
- Arduino Board
- USB Camera / Laptop Webcam
- LCD 16x2 with I2C Module
- Breadboard
- Jumper Wires

## ⚙️ How It Works

1. The camera captures a person's face.
2. The system detects and recognizes the face.
3. The recognized person is matched with registered users.
4. Their name and attendance time are recorded.
5. The Arduino receives the result and displays it on the LCD screen.

## 🔌 System Architecture

```text
       Camera
          |
          v
   Python + OpenCV
          |
          v
   Face Recognition
          |
          v
   Attendance Record
          |
          v
  Serial Communication
          |
          v
       Arduino
          |
          v
      LCD Display
```

## 🚀 Project Goal

To develop a simple and efficient attendance system by integrating Computer Vision, Face Recognition, and Embedded Systems.

## 👥 Contributors

This project is developed collaboratively. Contributions, suggestions, and improvements are welcome.

## 📌 Project Status

Under Development 🚧
