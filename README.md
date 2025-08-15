# AR Virtual Try-On

An interactive **Augmented Reality (AR) virtual try-on application** built with **Python, OpenCV, Streamlit, Mediapipe, and CVZone**.  
It allows users to:

- Apply **virtual makeup** (hair color, lipstick) to images.
- Try on **different clothes** in real time via **webcam or uploaded videos**.
- Experience a **live AR fitting room** directly in their browser.

---

## 📌 Features

### 1. **Virtual Makeup Mode**
- Upload your own photo or use a demo image.
- Change **hair color** and **lip color** using a color picker.
- Uses **semantic segmentation** to detect face parts.
- Sharpen filter applied for a more natural look.

### 2. **Virtual Clothes Mode**
- Upload a video or use your webcam.
- Try on multiple outfits (shirts, suits, tops) in real time.
- Pose detection with **Mediapipe Pose** + **CVZone overlay**.
- Dynamically adjusts clothing size & position based on body landmarks.

### 3. **About App Mode**
- Overview of the app’s purpose.
- Demo video explaining how it works.

---

## 🛠 Tech Stack

- **Python 3.8+**
- **Streamlit** – Web interface
- **OpenCV** – Image/video processing
- **Mediapipe** – Pose and face mesh detection
- **CVZone** – PNG overlay for clothes
- **scikit-image** – Gaussian filter for sharpening
- **Pillow** – Image handling

---

## 📂 Project Structure
AR_Virtual_Try_On/
│
├── app.py # Main Streamlit application
├── Shirts/ # PNG shirt images for clothes try-on
├── imgs/ # Sample images for makeup mode
├── demo.jpg # Demo image
├── demo1.mp4 # Demo video
├── cp/ # Model checkpoint for segmentation
├── test.py # Segmentation evaluation logic
└── requirements.txt # Python dependencies

---

## 🚀 Installation & Setup

### 1️⃣ Clone the repository
```bash
git clone https://github.com/its-anuskapalit/VirtualTryOn

