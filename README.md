# 🎓 SmartAttendance-OpenCV 🚀
## 📸 AI-powered Face Recognition Attendance System

A real-time, automated attendance system using OpenCV, LBPH Classifier, and Haar Cascade Classifier for accurate and efficient face recognition. Seamlessly integrated with Excel for hassle-free attendance tracking.

🔹 Fast & Reliable 💨
🔹 Real-time Face Detection 🎯
🔹 Automated Attendance Logging 📊



## 🚀 How to Run

1️⃣Clone this repo:
```bash
git clone https://github.com/bhumitjoshi2003/SmartAttendance-OpenCV.git
cd SmartAttendance-OpenCV
````

2️⃣ Install dependencies:
```bash
pip install opencv-python numpy pandas
```


## 📸 **Capturing Your Photos**
🎬 Run the TakePhotos.py script
```bash
python3 TakePhotos.py
```

👤 Follow the Instructions:
1️⃣ You'll see:

> Welcome!
> Please enter your ID : 
> If this is your first time choose a random ID between 1-1000
> ID: 

➡️ Enter your unique ID and press ENTER

2️⃣ If your ID is new, you'll be prompted:

> Please enter your name:

➡️ Type your name and press ENTER

3️⃣ Next, you'll see:

> Let's capture!  
> Press the 'S' key to capture a picture.  
> (It is recommended to take at least 30-35 pictures for better recognition.)  
> Press ENTER to start when you're ready, and press 'Q' to quit when you're done!"

✅ Press ENTER to begin
📸 A green box will appear around your face
🖱 Press 'S' to capture photos
❌ Press 'Q' to exit

✅ Your face images will be saved in the faces/ folder for training.



## 🎯 **Training the Model**

Run the Train.py script to train the LBPH classifier:
```bash
python3 Train.py
```

📌 This will process the images and save the trained model in the classifier/ folder.


## 🔍**Recognizing Faces**

Run Recognize.py to identify faces in real-time:
```bash
python3 Recognize.py
```

🟢 A green box will appear around detected faces.
🏷 Your name will be displayed below the recognized face.
🎉 Congratulations! You have successfully implemented a Face Recognition Attendance System!
