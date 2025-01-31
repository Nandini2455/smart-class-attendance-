# Smart Class Attendance System

![Smart Class Attendance](https://your-image-url.com/banner.png)

## 📌 Overview
The **Smart Class Attendance System** is an AI-powered facial recognition attendance system designed to automate and streamline attendance tracking in classrooms. It ensures accuracy, reduces manual work, and improves record-keeping through real-time face detection and recognition.

## 🚀 Features
- 🎭 **Face Recognition:** Captures and verifies student faces for attendance marking.
- 🔒 **User Authentication:** Secure login system for students and administrators.
- 🗄 **Database Integration:** Stores student details and attendance records in MySQL.
- 📸 **Real-time Camera Capture:** Detects and recognizes faces instantly.
- ⚙️ **Preprocessing:** Face cropping and grayscale conversion for better accuracy.
- 📝 **Attendance Storage:** Saves attendance records in a structured MySQL database.
- 🖥 **User-friendly Interface:** Built using Tkinter for easy navigation.

## 🛠 Technologies Used
- **Programming Language:** Python 🐍
- **GUI Framework:** Tkinter 🖥
- **Database:** MySQL 🗄
- **Face Detection & Recognition:** OpenCV 📷
- **Image Processing:** PIL (Pillow) 🖼

## 🔧 Installation
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/your-repo/smart-class-attendance.git
cd smart-class-attendance
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Setup Database
1. Create a MySQL database named `face`.
2. Configure your credentials in `database.py`:
   ```python
   db = mysql.connector.connect(
       host="localhost",
       user="root",
       password="Nandini@24",
       database="face"
   )
   ```
3. Execute the provided SQL script to create necessary tables.

### 4️⃣ Run the Application
```sh
python main.py
```

## 🎯 Usage
1. **Login:** Start the system by logging in as an administrator.
2. **Register Students:** Capture and store student images for future recognition.
3. **Take Attendance:** The system captures faces and marks attendance.
4. **View Records:** Check and export attendance records from the database.

## 📂 Folder Structure
```
smart-class-attendance/
│-- main.py               # Main application script
│-- database.py           # MySQL database connection script
│-- face_recognition.py   # Face detection & recognition logic
│-- ui/                   # Tkinter GUI files
│-- data/                 # Stored face images
│-- README.md             # Project documentation
│-- requirements.txt      # List of dependencies
│-- sql/                  # SQL scripts for database setup
```

## 🌟 Future Enhancements
- 📊 **Integration with Google Sheets** for real-time attendance tracking.
- 📩 **Notifications via Email/SMS** for absent students.
- 🤖 **Enhanced Accuracy** using deep learning models.
- 📱 **Mobile App Support** for attendance tracking via smartphone.

## 👥 Contributors
- **Nandini** - [GitHub Profile](https://github.com/Nandini2455)

## 💬 Contact
For queries, reach out via email at [your-email@example.com](mailto:pathivadanandini24@gmail.com) or open an issue on GitHub.

---
Made with ❤️ by Nandini 🚀

