# face-recognition-based-attendance-portal

This is a Flask-based attendance system that utilizes facial recognition to track attendance. It allows users to add people to the system, generate a dataset of their facial images, train a classifier, and perform real-time face recognition for attendance tracking.

## Features

- Add new people to the system with their name and skill.
- Generate a dataset of facial images for a specific person.
- Train a classifier using the generated dataset.
- Perform real-time face recognition for attendance tracking.
- Display a live video feed with recognized faces highlighted.
- View and clear attendance records for the current date.
- Download attendance records in excel sheets

## Uses

- Employee attendance tracking
- Student attendance tracking
- Event attendance tracking

## Skills Used

- Python
- JavaScript 
- Flask
- OpenCV
- MySQL

## Deployment

To deploy the Attendance System, follow these steps:

1. Install the necessary dependencies by running the following command:
```
pip install flask opencv-python mysql-connector-python pillow
```

2. Set up a MySQL database and update the `mydb` connection parameters in the code to match your database configuration.

3. Download the Haar cascade XML file for face detection and update the file path in the code (`face_classifier` variable).

4. Run the Flask application by executing the following command:
```
python app.py
```

5. Access the application by opening a web browser and navigating to `http://localhost:5000`.

Note: Make sure you have a webcam connected to your computer for real-time face recognition.

# Authors
# Hi, I'm bipsblip! 👋

- Pratyush Chand:  [@bipsblip](https://github.com/bipsblip)

Please feel free to contribute to this project by submitting bug reports, feature requests, or pull requests.

## 🚀 About Me
I'm a front-end web developer, with impressive problem-solving skills, tech knowledge, and hustling energy.

## 🔗 Connect With ME!
[![Github](https://img.shields.io/badge/github-000?style=for-the-badge&logo=github&logoColor=)](https://github.com/bipsblip)
[![GMAIL](https://img.shields.io/badge/Gmail-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pratyushchand.work@gmail.com)


